# FilmIndustryProject
By: Liliana Emfinger

## Overview

Microsoft is a multinational tech company. They produce everything from software to computers, to games and gaming consoles. Now Microsoft wants to take a new venture and break into the Movie industry! This project analyzes data from IMBD and The-Numbers.com. Microsoft can use this analysis to enter and be competitive in the movie industry worldwide.The analysis of this data shows that Microsoft can enter and succeed in the movie industry if they enter the market with an Adventure Animation movie that runs for about 125 minutes with a production budget of 175,000,000.
Movie-art-clip
Business Problem

Microsoft would like to enter the movie industry and be competitive with other veteran studios. In order to enter competitively Microsoft would like to make their movie a success. Analyzing Data from movies, we can find what profitable actions microsoft can take to enter this industry and be successful!
Data Understanding

(data explanation, exploration, and cleaning)
The Data used:

    The-Numbers.com Data
    IMBD Data

IMBD data has multiple tables attached and related to each other. The tables in the IMBD Data are movie_basics, directors, known_for, movie_akas, movie_ratings, persons, principals, and writers. The tables used in this analysis are movie basics, movie ratings and The-Numbers.com which was re-named to movie_budgets. Movie_budgets(The-Numbers.com) contains movie titles their release dates budgets and gross for each movie. Movie_basics contains movies released from 2010-2019. Movie_basics columns are movie id, primary title, original title, start year, runtime of the movie, genres for each movie . Movie_ratings contains a movie id, average rating (weighted average of all the individual user ratings, ratings are measured 1-10) and number of votes each movie received. The movie rating metric is out of 10.

## Metrics for success of a movie are ROI and ratings.

    ROI = Net Return on Investment- was calculated by taking worldwide gross subtracting production budget thus getting the return on investment. Net ROI was chosen as a metric for success because businesses (especially multinational) are about making a profit.
    Ratings = are a weighted average of all the individual user ratings. Ratings are measured 1-10. Ratings was chosen as a measure of success because people will pay to watch movies that they like, thus bring more popularity to the movie and ultimately more profit over time.

GOAL: is to use the data to find

    The average ratings per Genre
    The average and total ROI per Genre
    Top 50 movies with the highest ROI vs Runtime

