---
layout: post
title: Challenge 1
---
## a.k.a. Exploring MTA Turnstile Data
## a.k.a. My first crack at data cleaning and analysis and the 'pandas-monium' that ensued

### Project Objectives
1. Get familiar with some basic, but essential data science tools
2. See what it feels like to work with real world data

### My First Attempt...it was not very pretty
Being excited and nervous about the first project/challenge was not exactly a recipe for success
right away. I dove into the data on the first night and immediately starting making dictionaries
out of lists, writing tons of for loops, copying and pasting code, and plotting things randomly.
Long story short, I wrote a long, messy Jupyter Notebook that didn't do much.

### My Second Attempt...not so bad
I took a step back after we covered more Python Pandas functionality in lecture and after I thought
about some of the problem areas with the data and took some time to organize.
1. I organized the values of my dictionary into data frames instead of lists.
    * This helped eliminate some of the for loops and take some of the guessing out of following the 
    shape and size of the data.
2. I binned the times of turnstile entries.
    * Sometimes cumulative entries were recorded more than 6 times in one day, which lead to some
    issues, especially with plotting. I used pd.resample() to bin the times and entries into the 
    same four hour intervals throughout the six weeks I decided to look at.
3. I eliminated outliers, especially the ones that suggested that half the world used the same 
subway station during a four hour period.
    * Clearly the turnstiles were not always the most accurate as there were occaisonal values
    in the high hundreds of millions of entries. Those values a) did not make sense in terms of
    real life, b) made visualizations look shoddy, and c) skewed the data from giving any useful
    information. So, I went through six weeks of entry data, by the 4 hour time periods, to find
    the max value of each time chunk for each turnstile. I wanted to get an idea of what a 
    reasonable value was for one turnstile during one interval. I decided to cap entries per 
    interval at 10,000 because that fell in between where the majority of values were and the 
    20 or so significant outliers.
4. I also eliminated turnstiles that had all zero entries for all six weeks.
    * It seemed unlikely that no one would enter a station for six weeks and since it was not a
    huge fraction of the turnstiles, I felt comfortable assuming that those units were either 
    broken or removed at some point.
    
### Some closing thoughts
In the end when I took ridership totals across the six weeks, I came up with some expected 
stations, but also without some. Penn Station did not make my top ten, neither did Grand
Central, and Times Square barely squeezed in there. I am not sure where I went wrong yet,
but I cannot contribute those red flags to it being a weird spring of 2017. I am looking 
forward to learning more and starting the next project. I feel a little more comfortable
with a couple Python tools and plotting data, but data cleaning, justifying decisions, and
coding ettiquette still have a long way to go.

Thanks!
