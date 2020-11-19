# Movie Analysis

## Project Overview

The MovieAnalysis project involves gathering data from APIs and webscraping. After the data was gathered, exploratory data analysis was used to generate insights for making recommendations for the new Microsoft Movies team. 

### Presentation Link:
  * https://docs.google.com/presentation/d/1vO2e7Su6gVlR2l-b_L3V1aV8nKcpk4_h_4QEDuCrOiU/edit?usp=sharing

### Data

#### Movie datasets are collected from:
  * IMDB website with Beautiful Soup
  * https://www.themoviedb.org/ with API call

#### The visuals were provided by manipulating the following variables:
  * Genres
  * Gross Revenues
  * Release Month
  * IMDB Ratings
  * TMDB Popularity
  * Runtime

### Graphs / Findings

#### Gross Earnings Distribution
This graph demonstrates the skewed distribution of gross earnings.
![gross_earnings_distribution](graphs/gross_earnings_distribution.jpg)

#### Distribution of Genres
This graph demonstrates the popularity of each genre from the TMDB database. Drama, thriller, and comedy are the three most popular genres based on our findings. 
![distribution_genre](graphs/Distribution_genre.png)

#### Median Gross Earnings for each Genre
Adventure, family, animation, and action movies are the genres with the largest revenues. 
![average_gross_earnings](graphs/median_genre.PNG)

#### Mean IMDB Rating for each Genre
This boxplot demonstrates the IMDB Ratings of each genre. War movies have the highest IMDB ratings as well as the greatest range.
![average_rating](graphs/Average_IMDB_Ratings.png)

#### Mean TMDB Popularity for each Genre
Family movies have the highest TMDB popularity rating, followed by animation movies.
![TMDB_popularity](graphs/Average_TMDB_Popularity.png)

#### Monthly Median Gross Earnings for each Genre
This graph shows the median gross earnings for each genre and month.  For example, in November, animation, family, and adventure movies generated the most revenue. 
![month_genre_gross_median](graphs/Median_Gross_Revenue.png)

#### Runtime Through the Decades
This graph demonstrates the runtime of a movie throughout the last 100 years.
![runtime_decades](graphs/runtime_decades.JPG)
