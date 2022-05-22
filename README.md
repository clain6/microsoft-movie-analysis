# MICROSOFT MOVIE ANALYSIS

## Overview
This project analyzes movies from different data sources in order to find the best films currently at the box office and recommend what type of films to be created by the stakeholder.

## Business Problem
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## The Data
The data contains movie details from various datasets. The datasets were sourced from:
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB
* The Numbers.

##Methods
* **Data preparation**
Cleaned the data by removing duplicates and checking and removing missing values where necessary.
* **Analysis**
Performed analysis for the most popular and best rated movies as well as movie genres. Went further and analyzed the movies that were produced after the year 2010 so as to get the current movie trends in the market.
* **Visualization**
Drew visualizations on some of the analysis.

## Conclusion
After the analysis that was done on the TheMovieDB dataset, most movies that are currently trending in the market belong to **Superhero, Science fiction and Fantasy** genres.

On the other hand, Rotten tomatoes dataset shows that the most popular movie genres are **Action and Adventure, Comedy|Drama|Romance, Action and Adventure|Art House and International, Art House and International| Documentary, Action and Adventure|Mystery and suspense**. 

*However, TheMovieDB dataset was limited in that the movies were not classified in the genre names they belong to. Therefore, the analysis was limited based on this classification and I had to make my own conclusions on the genre the top movies belong to.*

## Repository Stucture
```
├── data
├── images
├── README.md
├── Presentation.pdf
└── microsoft_movie_analysis.ipynb
```
