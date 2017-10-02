---
layout: post
title: Scary Good...or Just Rotten
---

## Webscraping with Selenium and Beautiful Soup and Linear Regression Models

### It's almost Halloween!! (sort of)
I love Halloween and to get into the spirit, I like to watch a lot of scary movies.
Since there are so many out there, I use Rotten Tomatoes scores to help narrow down 
my search. 

### Objective:
Can I predict a scary movie's current Rotten Tomato score based on information 
from it's opening weekend?

### The Data:
I compiled a list of almost 1000 movies in various scary movie genres using the 
website: www.boxofficemojo.com
And I gathered the Rotten Tomatoes scores from: www.rottentomatoes.com

### Webscraping:
This part was completely new to me and took a bit of time to figure out. I started
with Box Office Mojo, picked the Horror R-Rated genre to start with, and then inspected
the page's html code with Beautiful Soup. Using Beautiful Soup's tag name search, I was 
able to make a list of all the links to the pages of the movies listed under Horror 
R-Rated. 

Having a list of links was great, but next I needed to make sure I could actually scrape 
the feature data I wanted from each individual movie page. Not all pages contain the same
amount of information, but I was able to generalize my code to collect (when available):
movie title, domestic total gross, distributor, release date, runtime, production budget, MPAA
rating, subgenres, domestic lifetime gross, foreign lifetime gross, opening weekend gross, 
widest theater release, time in release, directors, writers, actors, and composers.

Each observation (movie plus all the features above) was stored in a data frame through a 
for loop of all the unique movie links. Selenium allowed me to run a loop that opened each
individual link in a new page, scrape the data, close the window, and move to the next link.
It didn't take that long.

The second half of data scraping, took place on the Rotten Tomatoes website. This for loop
takes far longer than the Box Office Mojo process. I used Selenium again to help me open a
new Rotten Tomatoes window for each movie, but then within each new page, I have to search
for the movie, find the correct one in the list of search options, and then pull the score.

Once all the data is cleaned up, I will begin the linear regression modeling process! 

