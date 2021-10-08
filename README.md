# Microsoft Movie Analysis

**Authors:** Elena Burlando

## Overview

The objective of this project is to analyze movie data to provide insights on movie types that have performed best in the past decade. 

As an outcome of this analysis we are hoping to get: 
* Releases: 
 * Top 10 most produced genres during 2010-2020 (by entry count).
 * Top 2 most produced genres for each year (by entry count).
* Popularity: 
 * Top 10 most popular movies and genres during 2010-2019 (by number of votes). 
* Rating:
 * Top 10 highest rated genres during 2010-2019.
 * Top 10 highest rated movies during 2010-2019. 
 * Correlation between ratings and number of votes. 
* Gross Income and ROI:
 * Movies/genres with the highest domestic gross income. 
 * Movies/genres with the highest foreign gross income.
 * Movies/genres with the highest worldwide gross income. 
 * Correlation between domestic and foreign gross income.
 * Movies/genres with the highest ROI (return on investment). 

## Business Problem

Microsoft following the success of other big tech companies is considering setting up a movie studio. This project is aiming to provide valuable information to the head of Microsoft's new movie department in the areas of movies, genres, and ROI. 

***
One of the main business pain points related to this project is lack of experince in the movie industry and using 
data from other sources since it doesn't have any of its own. I picked the questions above as I think the answers to those would be the most beneficial when starting from scratch. They will provide high level overview of the industry and trends. 
***

## Data Understanding and Methods

For this project we will be using data from: 
* [IMDB](https://www.imdb.com/)
* [Box Office Mojo](https://www.boxofficemojo.com/)
* [The Numbers](https://www.the-numbers.com/)

Variables included: movie titles, release year, genres, runtime minutes, ratings, number of votes, and gross income (domestic and foreign) made of movies from 2010 through 2020.
***
* Using these sources we would be able to answer our questions listed above. 
* The target variables are the top performing movie titles and genres. 
* We used descriptive analitics, averages(mean), max, and Pearson correlation to answer questions in these four categories that are outlined in the Overview section. 
***

## Data

***
* Over 140K data entries for movie titles, genres, and release dates from 2010-2020. 
* Over 73K data entries for average ratings and number of votes. 
* Over 2,800 data entries for movie budgets, domestic/foreign/worldwide gross.
***

## Exploratory Findings

### RELEASES
***
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Release.png)

For this analysis we used data of over 140,736 movies.  
Documentary and Drama have been the most released movie genres in the past decade. 
***

## POPULARITY
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Popularity.png)

For this analysis we used data of 73,052 movies.  
Action, Adventure, Sci-Fi, Fantasy, Mystery, and War have been the most popular movie genres in the past decade. 

