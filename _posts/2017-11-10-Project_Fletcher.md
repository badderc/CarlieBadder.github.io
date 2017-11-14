---
layout: post
title: Wine Recommender
---


## An exploration into the world of oenology
I love wine. I like to drink wine, I like to enjoy wine
with good food and good company, and I like to pretend I
know things about wine. 

![_WineGlassDark]({{ site.baseurl }}/images/dark_glass.jpg)

In reality though, I am no wine connoisseur and I often 
do not really know what the back of the wine bottle is 
telling me or what the sommelier is saying at the restaurant. 
And to be honest, I've always wondered if the descriptions 
given by these experts truly distinctly describe the specific 
wine, or if they simply offer a general or basic idea of the 
wine and then you just have to taste it for yourself to know 
(not that I've ever complained about tasting a wine). You have
to wonder, how do all sommeliers taste the same thing and how 
can they accurately distinguish tens of thousands of different 
wines with only a couple sentences of description?

![_WineWordCloud]({{ site.baseurl }}/images/winetrans.png)

## So, I did some wine research
First, the word in the first header, 'oenology', means 'the
study of wines' and is pronounced 'ee-nol-uh-jee'. Second,
I discovered that all wines are typically described by [five
basic characteristics]
(http://winefolly.com/review/wine-characteristics/):
sweetness, acidity, tannin, fruit,
and body. That helps to know that there is some sort of 
formula that somms follow when describing a wine, but are
there really enough unique combinations of those five traits
for each wine out there and if there are, do descriptions of
similar wines demonstrate a trend in the characteristics?

![_WineCharacteristics]({{ site.baseurl }}/images/characteristics-of-wine-tasting-wine1.jpg)

## And I set some goals
In order to answer these questions, I decided to break down
the issues into slightly smaller chunks:

1. Acquire a lot of data including different wines and their
descriptions
2. Transform the text data from the document space into vector
space using natural language processing techniques
3. Use unsupervised learning, specifically topic modeling, to
project the vector into the topic space
4. See if two clusters create interpretable topics, ideally
corresponding to the division of red vs. white wines
5. See if nine clusters create interpretable topics, ideally 
corresponding to the [nine primary wine styles]
(http://winefolly.com/tutorial/the-9-major-wine-styles/), including 
full-bodied reds, medium-bodied reds, light-bodied reds, rosé wines,
full-bodied whites, light-bodied whites, aromatic whites, dessert
and fortified wines, and sparkling wines
6. If the descriptions can successfully distinguish trends in
wine types, build a recommendation system for user-generated
descriptions

![_ManyWines]({{ site.baseurl }}/images/manywines.jpg)

## The Data, the Preprocess, and the Model
The wine descriptions came from [Wine Enthusiast Magazine](http://www.winemag.com/)
and were scraped from the week of June 15th, 2017 and compiled 
into a dataset on [Kaggle] (https://www.kaggle.com/zynicide/wine-reviews). 
There were over 150K rows of data, which were narrowed down 
to just over 97K after removing duplicates. There were over 600
grape varietals and over 50 countries represented in the dataset. The
wines also came with tags for Region 1 and Region 2, price, points, 
winery, province, and designation. I stored all of the data in a 
collection on MongoDB, but only pulled the descriptions and the 
grape varietals to start. I preprocessed the descriptions by 
removing capital letters, punctuation, numbers, and stop and common
words, such as 'wine', 'flavor', and 'taste', that had little 
semantic value in the given context. Then I used a TF-IDF vectorizer
(with unigrams, a minimum document frequency of one, and ASCII-mapping 
for stripping accents) to one-hot encode all of the descriptions, 
or 'documents', into a document-term matrix. For the next
steps, I used scikit-learn's TruncatedSVD module to perform latent
semantic analysis on the document-term matrix and reduce it
into a topic space with varying numbers of topics.

![_RedWhiteGrapes]({{ site.baseurl }}/images/rwgrapes.jpeg)

## Simplifying Varieties: The Noble 18 Grapes
Because there were over 600 grape varietals, I tried
aggregating them by variations of the same names, but
I still had 300+ different kinds of grapes to look at.
In order to simplify the interpretation of my topic
modeling, I decided to focus on how each model clustered
the Noble 18 Grapes. The [Noble 18 grapes]
(http://winefolly.com/update/the-18-noble-grapes-wine-challenge/)
include 18 major grapes that are readily available and 
represent a distinct flavor of wine. They cover a large 
spectrum of wines, which encompasses the major flavor 
profiles of most red and white wines in the world. They
were also easily labeled in the list of over 97K wines, 
which made them ideal for checking the model clusters.

![_Noble18]({{ site.baseurl }}/images/noble18info.jpg)

## Two Topics: Red vs. White Wines
The Truncated SVD with two topics did a pretty great
job separating red from white wine like I'd hoped. The
plot below is colored according to the 18 Noble Wines, 
which I labeled by red and white.

![_TwoTopics]({{ site.baseurl }}/images/noble18plotrw.png)

The topic displayed on the y-axis shows the clearest
distinction between red and white wines. And, when I 
looked at the most common words in the descriptions at
the extremes of the of the y-axis, the words from the top
sounded notably like white wine-descriptors, while the words
from the bottom sounded more like red wines.

![_TopBottom]({{ site.baseurl }}/images/topbottom.png)

The topic on the x-axis, however, was not so clear. There
is some pattern from left to right, but it affects both
the red and the white wines. When I inspected descriptions 
from the extremes, I could see a large difference in the 
most common words. Some of the words on the left side were
not even real words and most of them were not obviously 
related to wine. I determined that the second topic was
distinguishing unconventional and uncommon wine descriptions
from more traditional and basic ones. It was most likely
picking up on the descriptions that included more information
about the vineyard or the circumstances surrounding the 
production of that specific wine rather than information on
the taste.

![_LeftRight]({{ site.baseurl }}/images/leftright.png)

The two topics got even more interesting once I colored the
data points by the specifc wines of the Noble 18. The 
animation below shows the wines colored in gradients of green 
and purple, for white and red wines respectively, where the gradients
correspond to the weights of the wines, ie. Pinot Grigio is the
lightest-bodied wine of the whites and is colored the lightest. 
As the animation cycles through the description clusters, it 
reveals a pattern: the wines rotate clockwise about the origin
from lightest white at the top to darkest red at the bottom. I 
did not expect to see this result because almost none of the descriptions
explicitly label the wines' weights. This colorized plot demonstrates
that the weight could potentially be extrapolated from the 
rest of the description. This finding encouraged me to explore 
topic modeling with a greater number of topics (hopefully that
correspond to more specific styles of wines).

<iframe width="560" height="315" src="https://www.youtube.com/embed/gF675nRLCeQ" frameborder="0" gesture="media" allowfullscreen></iframe>

## Nine Topics: The Spectrum of White to Red Wines
![_NineWinesGif]({{ site.baseurl }}/images/animated-gif-winestyles.gif)

definitely something there - interesting to look at 
8, 7, 6, and 5 topics as well - removing one topic at 
a time to account for lower representation of rosés,
sparkling wines, and dessert wines and for the blending
between aromatic and light whites and light to medium
bodied whites, which were not as easily distinguishable

![_NineTopicsDivider]({{ site.baseurl }}/images/wines8.jpg)

## A Simple Recommendation System
<iframe width="560" height="315" src="https://www.youtube.com/embed/go4VzEt7KWY" frameborder="0" gesture="media" allowfullscreen></iframe>




