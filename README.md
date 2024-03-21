# Phase 1 Project Description

## Project Overview

For this project, I am using exploratory data analysis from other movie datasets to generate insights for Microsoft's New studio director; to help in the production of original video content for the first time. 

### Business Problem

Microsoft wants to join the movie entertainment industry and take part in creating original video content but they don’t know anything about creating movies.


### Business Understanding

Microsoft aims to venture into movie production by creating a new movie studio without any knowledge on this. Through exploring what types of films are doing the best from Box office and presenting insights, we get to know what films to produce to achieve success in this industry.

The MAIN objective is for Microsoft's new studio to be established in the entertainment industry through movie production by referring to the findings after analyzing successful films in the industry.

Some of the key points to look into in the analysis are total gross revenue, ratings, number of votes and popular genres

## Key business questions

What are the trends in audience preferences, genres, and consumption habits?

When and how will the studio distribute its films to audiences?

What is the projected budget for the studio's operations and film productions?

### The Data Understanding

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

The datasets used for this specific project: tmdb.movies.csv.gz and im.db.zip

The Data Tools used are: Pandas, Numpy, Seaborn, Matplotlib and SQL


## Data Analysis

## FINDING 1

![image](https://github.com/Kelsey-Maina/movie_data_analysis/assets/162282707/d7333c79-5bcd-41f5-9ce2-12b6c5f5b18c)

From this bar graph, movies with the combination of genres (Action, Adventure and Sci-fi) are the most popular.

Thus, I would recommend that Microsoft's studio produce movies with this mix.

To achieve the above result, I found the mean data of genres column in correspondence to the number of votes the movies got.

## FINDING 2

![image](https://github.com/Kelsey-Maina/movie_data_analysis/assets/162282707/c522546e-8229-42ee-a774-0833ff21595a)

From the bar plot , we discover that most movies are released in the month of December and the last quarter of the year.

I would recommend the Microsoft's new studio torelease movies mid yearto avoid competition for viewership.

To achieve this result, I checked from the release date the month with the highest number of movie releases.

## FINDING 3













