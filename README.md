# udacity-investigate-a-dataset

## Overview

In this project I analysed the TMDB dataset form a csv file dowloaded from [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata/data). The dataset contained 5000+ movies with data covered untill 2015 and their rating and basic move information, including user ratings and revenue data. 

I used python 3 to interact with the dataset. To run the scripts just open the .ipnb file then follow the flow. 

The dataset contains some metrics that can be used when judging if a movie was successfull or not.

Any of the metrics can be used to check how successfull a movie was. Is there any factors that may be might influence the results ? is there any corelation between the basic information provided ? Those are some of the questions that one may ask.

## Questions

How was the popularity of a movie over the years ? - Considering the five recent years, how is the distribution of revenue in different score rating levels ? how is the distribution of revenue in different popularity levels ? What kinds of properties are associated with movies that have high popularity? What kinds of properties are associated with movies that have high voting score? How many movies are released year by year ? What are the keywords trends by generation ?

## Findings

* The movie popularity rend is growing over the years from 1960.
* Movies with high revenue have higher popularity in the recent five years
* Movies with higher revenue don't have the significant high score rating

* The properties associated with higher popularity movies are `high budget levels` and `longer run time`. 
* Cast associated with high popularity movies are `Robert de niro` and `Bruce willis`
* The director associated with high popularity movies is `Steven Spielberg`
* Genres associated with high popularity moviesare `drama, comedy, and thriller` however they also appear in the most unpopular ones
* Keywords associated with high popular movies are `Based on novel` and `Dystopia`
* The producer associated with high popularity movies are `Warner Bros`, `Universal Pictures` and `Paramount Pictures`
* The low / high budget level may not directly predict that a movy had higher ratings.
* Martin Scorsese and Clint Eastwood are the rockstar directors since the 60s

* Over the years, the number of move realeases kept increasing and it is an accelerated groth trend. 
* In the 90s and 70s the top keword was `based on novel`, in 80s was `Nudity`, in 90s `Independant films` and after 2000 the movies with the feature women director were released the most.
* Only the 80s were dominated by comedy. the other generations were dominated by drama. 

For further details, read the .html file.


## Ressources that I used

* [Anonymous link](https://carlyhochreiter.files.wordpress.com/2018/05/investigating-movie-dataset.pdf)
* [Grant Patience's Blog](https://grantpatience.com/2019/07/16/project-data-analysis-of-movie-releases-in-python/)
* [Spare Space](https://static1.squarespace.com/static/55bfa8e4e4b007976149574e/t/5b998f398a922d8eaecaefd2/1536790332004/investigate-dataset-movies.pdf)
