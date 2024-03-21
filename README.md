# Phase 1 Project Description

## Project Overview

For this project, I used exploratory data analysis from other movie datasets to generate insights for Microsoft's New studio director; to help in the production of original video content for the first time. 

### Business Problem

Microsoft wants to join the movie entertainment industry and take part in creating original video content but they don’t know anything about creating movies.


### Business Understanding

Microsoft aims to venture into movie production by creating a new movie studio without any knowledge on this. Through exploring what types of films are doing the best from Box office and presenting insights, we get to know what films to produce to achieve success in this industry.

The ***MAIN objective*** is for Microsoft's new studio to be established in the entertainment industry through movie production by referring to the findings after analyzing successful films in the industry.

Some of the ***key points*** to look into in the analysis are total gross revenue, ratings, number of votes and popular genres

## Key business questions

1. What are the trends in audience preferences, genres, and consumption habits?

2. When and how will the studio distribute its films to audiences?

3. What is the projected budget for the studio's operations and film productions?

### The Data Understanding

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

The datasets used for this specific project: tmdb.movies.csv.gz and im.db.zip

The ***Data Tools*** used are: Pandas, Numpy, Seaborn, Matplotlib and SQL


## Data Analysis

## FINDING 1

![image](https://github.com/Kelsey-Maina/movie_data_analysis/assets/162282707/d7333c79-5bcd-41f5-9ce2-12b6c5f5b18c)

From this bar graph, movies with ***the combination of genres (Action, Adventure and Sci-fi) are the most popular***.

Thus, I would recommend that Microsoft's studio produce movies with this mix.

To achieve the above result, I found the mean data of genres column in correspondence to the number of votes from numvotes column.

## FINDING 2

![image](https://github.com/Kelsey-Maina/movie_data_analysis/assets/162282707/c522546e-8229-42ee-a774-0833ff21595a)

From the bar plot , we discover that most movies are released in the month of December and the last quarter of the year.

I would recommend the Microsoft's new studio ***to release movies mid year to avoid competition for viewership***.

To achieve this result, I checked from the release_month column which I created from the pre-existing release_date column; the month with the highest number of movie releases.

## FINDING 3

![image](https://github.com/Kelsey-Maina/movie_data_analysis/assets/162282707/f4534987-f5a8-457f-b8c1-0b913a67c393)

Production budget and worldwide gross have a ***positive relationship*** as the points on the scatter plot slop from the left to right upwards. This means that when the production budget increases, the worldwide gross revenue also increases.

The plot also displays a ***strong relationship*** between the two variables as many points are closely clustered in a clear pattern.

So it is safe to conclude that ***spending or investing more on film production budget-wise, will most likely yield an increased worldwide gross revenue***.

To achieve this result, I first, calculated the correlation between Production budget and worldwide gross which was 0.75 and then plotted a graph showing their relationship so as to understand if their dependent of each other.

## CONCLUSION

1. Popular trends in audience preference, genres which in this case I would recommend focusing on the popular movie genres which in our case is the combination of Action, Adventure and Sci-fi and the second highest combination being Action, Thriller.

2. Mid-Year Release Strategy for Optimal Showcasing as most movies are released at the last months of the year. I would recommend avoiding release of movies mainly on December since there is competition for audience attention and lack of theatre availability.
   
3. Production Budget Increase for Higher Revenue Potential.
   













