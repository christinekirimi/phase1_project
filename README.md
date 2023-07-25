# Microsoft Movie Studio Project.


## Overview
This project analyzes the performance of movies from different studios, genres and years. For this project, I use exploratory data analysis to generate insights for a business stakeholder. I use three data sets i.e; imdb.title.basics, imdb.title.ratings and bom.movie_gross.This project uses bar graphs, histograms and scatterplots for visualization. 

## Business Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies.I am charged with exploring what types of films are currently doing the best at the box office. I must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Data Understanding
##### 1. bom_movie_gross_csv
It contains 5 columns i.e; title, studio, domestic-gross(revenue) and foreign_gross(revenue) and year
#### 2. title.ratings.csv
It contains 6 columns i.e; tconst(string): It is an alphanumeric unique identifier of the title. original_title is the original title,in the original language.Start_year represents the release year of a title. In the case of TV Series, it is the series start year.runtime_Minutes:primary runtime of the title, in minutes.Genres includes up to three genres associated with the title.
#### 3. title.ratings.csv
It contains 3 columns i.e; tconst:alphanumeric unique identifier of the title. Averagerating: weighted average of all the individual user ratings. numVotes: number of votes the title has received

## Results
##### In the Analysis above we have come to the following Conlusions:
1. The domestic revenue and foreign revenue have a strong positive correlation meaning the movies that had a high domestic revenue are more likely to have a high foreign revenue.
2. Comedy, Documentary and Fantasy had the highest average rating of 9.40,followed by Documentary, Family, Musical had the second highest rating of 9.30.And History and Sport had the third highest rating of 9.20.
3. Action, Adventure and Sci-Fi received the highest number of votes followed by Action Adventure and Animation second highest and Adventure, Animation and Comedy third highest.
4. There is a week correlation between number of votes and average rating, hence the number of votes do not necessarily influence the rating of a movie.
5. Adventure, Animation and Comedy had the highest total revenue followed by Action Adventure and Sci-fi, Then Action Adventure and Fantasy came in third.

## Recommendations

###### The following are my recommendations to microsoft movie studio:
1. The microsoft movie studio should not produce movies with a very long runtime since the movies that have average runtime of below 100 minutes have more revenue compared to those with very high runtime.
2. Microsoft Movie studio should be keen to produce the following movie genres that had the most revenue:
                    a). Adventure, Animation and Comedy had the highest total
                    b). Action Adventure and Sci-fi.
                    c). Then Action Adventure and Fantasy came in third.
3. The genres with high number of votes are also the movie genre that attracted the highest revenue, so they should be keen to produce movies with high number of votes.This genres are: a). Action, Adventure and Sci-Fi b). Action Adventure and Animation c). Adventure, Animation and Comedy third highest.
4. Microsoft Movie studio should produce movies that will appeal to both their domestic audience and foreign audience since the domestic revenue and foreign revenue have a strong positive correlation.

