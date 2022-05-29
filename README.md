# What makes a movie successful
* Oleksandra Aliyeva

![](Images/Movie-video-editing-logo-design.png.jpeg)


I was hired to produce a MySQL database on Movies from a subset of IMDB's publicly available dataset. Ultimately, I will use this database to analyze what makes a movie successful and will provide recommendations to the stakeholder on how to make a successful movie.
 
**SPECIFICATIONS**

Stakeholder only wants me to include information for movies based on the following specifications:

* Exclude any movie with missing values for genre or runtime
* Include only full-length movies (titleType = "movie").
* Include only fictional movies (not from documentary genre)
* Include only movies that were released 2000 - 2021 (include 2000 and 2021)
* Include only movies that were released in the United States

## **PART 1 - Initial Data Processing**

IMDB Provides Several Files with varied information for Movies, TV Shows, Made for TV Movies, etc.

 Overview/Data Dictionary: https://www.imdb.com/interfaces/
 
 Downloads page: https://datasets.imdbws.com/

I will use files below for this project:
* title.basics.tsv.gz
* title.ratings.tsv.gz
* title.akas.tsv.gz

## **PART 2 Extracting DATA from TMDB**

After investigating the preview of my data from Part 1, my stakeholder realized that there is no financial information included in the IMDB data (e.g. budget or revenue).

The Movie Database (TMDB) was identified as a great source of financial data (https://www.themoviedb.org/). I will use an API for extracting the budget, revenue, and MPAA Rating (G/PG/PG-13/R), which is also called "Certification".

## **PART 3 Exploratory Data Analysis**


## **PART 4 Creating a MySQL database**

I will normalize all movie data in a MySQL Database.

## **PART 5 Hypothesis Testing**

I will then use the MySQL database to answer several hypotheses about movie success.

**Does the MPAA rating of a movie (G/PG/PG-13/R) affect how much revenue the movie generates?**

* Null Hypothesis - The MPAA rating of a movie ('G', 'NC-17', 'NR', 'PG', 'PG-13', or 'R) does not affect how much revenue the movie generates.
* Alternate Hypothesis - The MPAA rating of a movie ('G', 'NC-17', 'NR', 'PG', 'PG-13', or 'R) does affect how much revenue the movie generates.

**Do movies that are over 2.5 hours long earn more revenue than movies that are 1.5 hours long (or less)?** 

* Null Hypothesis - movies that are over 2.5 hours long earn same revenue than movies that are 1.5 hours long (or less).
* Alternate Hypothesis - movies that are over 2.5 hours long earn different revenue than movies that are 1.5 hours long (or less).

**Do movies released in 2020 earn less revenue than movies released in 2018?**

* Null Hypothesis - movies released in 2020 have same revenue than movies released in 2018.
* Alternate Hypothesis - movies released in 2020 have different revenue than movies released in 2018.


## **PART 6**
