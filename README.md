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

One of the main business pain points related to this project is lack of experince in the movie industry and using 
data from other sources since it doesn't have any of its own. I picked the questions above as I think the answers to those would be the most beneficial when starting from scratch. They will provide high level overview of the industry and trends. 

## Data Understanding and Methods

For this project we will be using data from: 
* [IMDB](https://www.imdb.com/)
* [Box Office Mojo](https://www.boxofficemojo.com/)
* [The Numbers](https://www.the-numbers.com/)

Variables included: movie titles, release year, genres, runtime minutes, ratings, number of votes, and gross income (domestic and foreign) made of movies from 2010 through 2020.

* Using these sources we would be able to answer our questions listed above. 
* The target variables are the top performing movie titles and genres. 
* We used descriptive analitics, averages(mean), max, and Pearson correlation to answer questions in these four categories that are outlined in the Overview section. 


## Data

* Over 140K data entries for movie titles, genres, and release dates from 2010-2020. 
* Over 73K data entries for average ratings and number of votes. 
* Over 2,800 data entries for movie budgets, domestic/foreign/worldwide gross.


## Exploratory Findings

### RELEASES

![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Release.png)

For this analysis we used data of over 140,736 movies.  
Documentary and Drama have been the most released movie genres in the past decade. 

## POPULARITY
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Popularity.png)

For this analysis we used data of 73,052 movies.  
Action, Adventure, Sci-Fi, Fantasy, Mystery, and War have been the most popular movie genres in the past decade. 

## RATING 
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Rating.png)

For this analysis we used data of 28,628 movies with over 100 votes. 
Documentary, Music, War, Adventure, and Drama have been the highest rated movie genres in the past decade. Their average rating is 8.9. However other 10 genres are  not far behind and rated around 8. 

## CORRELATION BETWEEN RATING AND POPULARITY
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Correlation%20bw%20Rating%20and%20Popularity.png)

There is a little positive correlation (0.13) between rating and population indicating that these two variables have to be considered independently. 

## COMPARISON OF TOP GENRES IN THREE CATEGORIES:
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Comparison%20in%20Released%2C%20Popularity%2C%20Rating.png)

In the category of the most Released genres, the winners are Documentary and Drama. We used the largest sample (population data) we could get from IMDB dataset of around 140K of entries to answer this question. Historically, these two genres have been leading the top 10 from 2010 through 2020.

Under the most Popular category, the top 5 are occuied by Action, Adventure, Sci-Fi, Mystery, Fantasy, War, and Drama. We can also see below that these categories are the most profitable as well. For this analysis, we used data of over 73K data entries. However, we have used only one data source.

In the Rating category: Documentary, Comedy, Fantasy, Musical, History, Sport, Game-Shows, Drama, Reality-TV, News have been the highest rated. However, over hundred genre combination have been performing above 7.

## DOMESTIC GROSS
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Domestic%20Gross.png)

Family, Fantasy, Musical, and Romance are performing best financially in domestic market with at or over $400M gross. 

## FOREIGN GROSS
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Foreign%20Gross.png)

Fantasy, Romance are performing best financially with over $800M foreign gross. Adventure, Fantasy, Musical, Family are the next highest performing genres with about $500M in foreign gross. 

## WORLDWIDE GROSS
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Worldwide%20Gross.png)
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20Worldwide%20Gross_2nd%20dataset.png)

For this analysis we used data two datasets: Box Office Mojo and The Numbers.  We are getting very similar results per genre or a combination of genres even though some data per genre is missing in one dataset or the other. 
Fantasy & Romance genres have over $1.2B worldwide gross. Family, Fantasy, Musical are close to $1B. Documentary, Drama, Sport, and Sci-Fi are producing over $0.8B in worldwide gross. 

## ROI
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Top%2010%20by%20ROI.png)

Fantasy and Romance (aka ’Frozen’) are by far the most profitable genres. On average a combination of these genres is responsible for over $1B in ROI. Family, Fantasy, Musical are the second on the list with ROI over $0.8B.

## CORRELATION BETWEEN DOMESTIC AND FOREIGN GROSS 
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Correlation%20bw%20Domestic%20and%20Foreign%20Gross.png)
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Correlation%20bw%20Domestic%20and%20Foreign%20Gross_2nd%20dataset.png)

After analyzing two dataset with financial data: The Numbers and  Box Office Mojo, 
we  discovered that there is a strong positive correlation between domestic and foreign gross.
Domestic gross is responsible  for 47%  of worldwide gross when Foreign gross is responsible for 53%.  

## COMPARISON ON TOP GENRES IN GROSS INCOME AND ROI:
![alt text](https://github.com/rusalka013/microsoft-movie-analysis/blob/main/Images/Comparison%20in%20Release%2C%20Popularity%2C%20Rating.png)

Fantasy, Romance, Family, Musical, Action, Adventure, and Sci-Fi make up the top 10 most profitable genres. 

## Conclusions

There is a little positive correlation between rating and population indicating that these two variables have to be considered independently as we did. 

We do see some correlation between most released genre and the highest rated: Documentary. But there might be other factors outside of Rating contributing to Documentary and Drama to be the most released genres.  

Business Suggestions: 
* Action, Adventure, Sci-Fi, Fantasy, Mystery, and War are the most popular. They also make up the top 10 most profitable genres. 
* Fantasy and Romance are the most profitable genre combo followed by  Family/Fantasy/Musical 
and Action/Adventure/Sci-Fi. 
* Release a movie in both domestic and foreign markets to get the maximum gross. Foreign gross is responsible for over half of worldwide income (~53%). 

Next Steps: 
* To analyze the trends in genres over the years. 
* To get more recent data through APIs to see how pandemic has shaped a movie industry. 
* To perform more in-depth analysis on ROI per genre. 
* To look into a cast and directors whose movies are the most popular and profitable. 



