

# ...mostly rotten
It turns out that predicting Rotten Tomato scores for scary movies is not
that easy to do!

## Quick Recap of Project Motivations
It's almost Halloween and I like to watch scary movies to get into the 
spooky spirit. It's also important to me to watch the best scary movies,
so I turn to Rotten Tomatoes to clue me in on which movies will scare and
entertain me the most. This lead me to wonder if I could predict the score
of a movie before it hit the theaters.

Thinking outside my personal motivations, there is a business case for 
being able to predict Rotten Tomatoes scores too. In 2016, Fandango bought
Rotten Tomotoes and started posting movie scores next to ticket sales on 
their website. As it turns out, those scores had a big influence on opening 
day ticket sales for movies. Movie production companies took notice when 
their marketing predictions for opening day totals became obsolete relative
to predictions based on Rotten Tomatoes score. If production companies could
predict the Rotten Tomato score of their films before they come out, they
could modify their marketing plans and even identify the movie features that
generate the best scores and make sure to implement them for ultimate movie
success!

## How Rotten Tomatoes Scores Work
Critics certified by Rotten Tomatoes go to advanced screenings of new films
and send in their reviews to Rotten Tomatoes. Critics are certified after 
going through a fairly rigorous vetting process, which requires them to have
a certain number of followers and traction in the movie critique world. Once
Rotten Tomatoes receives the reviews, they are divided into mostly positive
or mostly negative critiques, fresh or rotten, respectively. Once divided, 
the reviews are aggregated into one percentage of freshness, which is the 
movie's overall Rotten Tomatoes score. It should be noted that the score 
really just provides a general consensus about a film because the way the 
reviews are divided diminishes the potential impact of very negative or 
very positive reviews. 

## Creature Features
After pulling together data from Box Office Mojo and IMDB, I was overwhelmed 
with features to use to predict the scores. I was able to eliminate several 
variables that provided information that wouldn't be available at the time 
of Rotten Tomatoes scoring like total gross or number of theaters during widest
release. I also had to remove features that were not easily quantifiable, like 
director and actors. And then I had to narrow the list of 131 subgenres to the
top 34 most prevelant. My final list of features included:
* Runtime
* Production Budget
* Release Year
* Release Month
* Subgenres

## First Linear Regression
Just to get an idea of what I was working with, I put all my data with all my
features into a basic linear regression and found that there was not a lot
of correlation between my model and my target variable, Rotten Tomato score.
While the correlation wasn't great, the root mean squared error was better than
the error of the baseline model (where the predicted target is just the mean). In
points, the RMSE of the linear regression was off by about 24 percentage points,
whereas the baseline model was off by about 28. 

## Could there be a better model?
I wasn't satisfied with the first linear regression model, so I tried a *few* things:
1. Transform the variables for runtime and production budget because they were 
slightly skewed right
2. Further narrowing down the list of subgenres from 34 to the top 10
3. Using a standard scalar transformation to account for the large size difference
between production budget numbers and everything else
4. Applying a second degree polynomial transformation
5. Selecting the features with the lowest p-values and largest coefficients and 
running a linear regression on that set of features
6. Reorganizing the release years into categorical variables of decade and removing 
the subgenre variables because in theory most subgenres of horror films could 
be labeled by decade
7. Removing release month and creating the variable released in the fall or not
8. Some more tinkering
9. Dividing the data into two sets; one for pre-2000 movies and one for post-2000

## So what I actually found
Transforming and eliminating various combinations of features did not end up 
improving my model very much. The initial linear regression with all the
features and untransformed variables created the best model overall, but I did
discover some interesting things:
1. Despite having a low correlation, runtime was the top predicting feature. I 
am not sure why, but maybe there is some interaction between quality of scary movie
and the length, where shorter films aren't as well-developed or good.
2. There were 7 subgenres that had significant positive influence on the score
and 5 subgenres that had significant negative influence on the score. These features 
were part of the subset of features with low p-values and high coefficients. 
Separately, they were not highly correlated with the Rotten Tomato score, but in
combination they strongly affect the score. With further research and manipulation
I would hope to figure out the interaction between those subgenres that demonstrates
their combined effect on the score and improve my original model.
3. Dividing the data into pre- and post-2000 movies and building two separate models
resulted in even better R^2 and RMSE values. Rotten Tomatoes launched in 2000, which
is why I chose to investigate the difference between those two groups. In future 
studies I would like to further develop the two models and better understand the 
reasoning behind the divide.

## Future Future Work
In addition to the yera 2000 split model, I think the best plan to improve my model
would be to incorporate the individuality of the critics. I think the reason that
numbers and dates and subgenres couldn't properly predict Rotten Tomatoes scores is
that the scores are really dependent on an exclusive group of critics who have
highly variable opinions, tastes, and interests in films and, on top of that, many 
scary movies are totally divisive when determining what makes a scary movie good.
If time permitted, I would make a model that incorporated each of the top critics,
what their preferences are (judging from past reviews) and features of the movie.
Then, depending on which combination of critics review a certain film, I could
predict whether their review would be mostly positive or mostly negative, and then
aggregate those results into the overall score. As an extension of identifying the
preferences of each critic, I could also use those preferences to pin down some of 
the most common features of the highest rated films. But all that is for another
day and another project.

## Happy Halloween!
### Creep it real, folks



