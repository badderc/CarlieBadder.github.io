---
layout: post
title: Wine Recommender
---


## An exploration into the world of oenology
I love wine. I like to drink wine, I like to enjoy wine
with good food and good company, and I like to pretend I
know things about wine. In reality though, I am no wine
connoisseur and I often do not really know what the back
of the wine bottle is telling me or what the sommelier is
saying at the restaurant. And to be honest, I've always 
wondered if the descriptions given by these experts truly
distinctly describe the specific wine, or if they simply
offer a general or basic idea of the wine and then you just
have to taste it for yourself to know. You have to wonder, 
how do all sommeliers taste the same thing and how can they
accurately distinguish tens of thousands of different wines
with only a couple sentences of description?

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



