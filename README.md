# Movie-Ratings---Analytics

An analysis of 5000 movies aiming to identify patterns in ratings, popularity, and genre.


## Overview
This project analyzes 5000 movies, focusing on their ratings.  
Key questions:
- Are there any factors that correlate with higher ratings?
- Do more votes mean a higher rating?
- Does genre affect ratings?
- Are there any 'underrated' movies?

## Preparing Data
The dataset comes from Kaggle: IMDb Top 5000 Movies.
It contains the IMDb ID, title, year, genre, rating, number of votes, runtime, and other metadata.

Steps taken to prepare the data:
- Load raw file – The CSV was imported into spreadsheets.
- Removed unneeded columns.
- Checked for missing values or values outside of expected ranges.

## Findings
### Ratings Correlations

![Total Names per Year](Plots/ratingsCorr.png)

###
![Total Names per Year](Plots/votesbyRating.png)

![Total Names per Year](Plots/runtimebyRating.png)

###
![Total Names per Year](Plots/ratingsbyYear.png)

![Total Names per Year](Plots/moviesbyYear.png)

###
![Total Names per Year](Plots/underratedMovies.png)
