# Investigating-The-Movie-Database
This is my first project as a student in the Udacity ALX-T Data Analyst Nanodegree Program

## Introduction
The dataset used in this project includes a list of movies and their ratings from the year 1960 to 2015 as collected from The Movie Database(TMDb). The data includes information on the release date, release year, directors, cast, popularity, genre, revenue and budget, amongst other line items.

I analyzed this data to generate insights, particularly focusing on the questions below:
>1. Are there specific months that generate the highest movie ratings?
>2. What movie genres received the highest average rating?

The libraries required are: pandas, numpy, seaborn, matplotlib, plotly and datetime.

My approach takes into account data wrangling, data cleaning and exploratory data analysis.

## Findings
Insights generated from the month of release of the movies were as below. From these, one could conclude that the best month to release a movie would be December, because this month shows up in the top 3 of almost all categories of analysis.
>1. September, October and December generated the highest movie releases in total.
>2. December, September and November had the highest vote average in general.
>3. June, November and December have the highest average movie popularity ranking.
>4. June, May and December have both the highest average budget and revenue.
>5. June, May and July as having the highest average movie vote count.
>6. December, September and May as having the highest average movie runtimes

>**Limitations:**
>1. My analysis did not factor in directors/cast. It's possible to have the same genre produced by different directors and cast and have a variation in the quality of movie.
>2. It is possible that a month like February has fewer movie releases because it has the shortest days in a year, which could directly influence the number of movies released.
>3. The data does not consider only one movie release per day, per month. There could be several movies released in one day in a particular month, thus explaining why some months have higher movie releases.


Insights generated from movie genres when ranked according to the vote average included:
>1. The genre with the highest average rating is Drama|Horror|Mystery|Science Fiction|Thriller.
>2. A majority of the movies with high ratings were released from the year 2000 onwards.
>3. The most popular movie genre is Action|Thriller|Science Fiction|Mystery|Adventure, and this is also the genre with the highest vote count in the top ten.
>4. There is a positive relationship between the budget and revenue.

>**Limitations:**
>1. My analysis focuses only on the top 10 movie genres in the data set, in terms of average vote rating. It is possible to have developed greater insights had more data been used in the analysis.
>2. Having a high vote rating does not necessarily mean that the movie was top rated. For some of the genres such as Action|Thriller|Science Fiction|Mystery|Adventure, there is a high vote count. It is possible that this genre received low ratings but had a few high outliers which brought up the mean rating.
