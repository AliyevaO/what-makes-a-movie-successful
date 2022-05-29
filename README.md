# What makes a movie successful

![](Images/Movie-video-editing-logo-design.png.jpeg)

Oleksandra Aliyeva

I was hired to produce a MySQL database on Movies from a subset of IMDB's publicly available dataset. Ultimately, I will use this database to analyze what makes a movie successful and will provide recommendations to the stakeholder on how to make a successful movie.
 
**SPECIFICATIONS**

Stakeholder only wants me to include information for movies based on the following specifications:

* Exclude any movie with missing values for genre or runtime
* Include only full-length movies (titleType = "movie").
* Include only fictional movies (not from documentary genre)
* Include only movies that were released 2000 - 2021 (include 2000 and 2021)
* Include only movies that were released in the United States

**PART 1 - Initial Data Processing**

IMDB Provides Several Files with varied information for Movies, TV Shows, Made for TV Movies, etc.

 Overview/Data Dictionary: https://www.imdb.com/interfaces/
 
 Downloads page: https://datasets.imdbws.com/

I will use files below for this project:
* title.basics.tsv.gz
* title.ratings.tsv.gz
* title.akas.tsv.gz

**PART 2 Extracting DATA from TMDB**

After investigating the preview of my data from Part 1, my stakeholder realized that there is no financial information included in the IMDB data (e.g. budget or revenue).

The Movie Database (TMDB) was identified as a great source of financial data (https://www.themoviedb.org/). I will use an API for extracting the budget, revenue, and MPAA Rating (G/PG/PG-13/R), which is also called "Certification".

**PART 3 Creating a MySQL database**

I will normalize all movie data in a MySQL Database.

**PART 4**

**PART 5**

**PART 6**
