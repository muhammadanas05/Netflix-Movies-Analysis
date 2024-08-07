# Netflix Movies Analysis
This repository contains a Python script for analyzing Netflix movie data. The script performs various operations on a dataset of Netflix movies, including filtering, aggregating, and visualizing the data.

## Requirements
Python 3.x
Pandas
Matplotlib

## Data
The script uses a CSV file named netflix_data.csv. Ensure that this file is in the same directory as the script.

## Code Overview
Loading Data

The script reads the CSV file netflix_data.csv into a DataFrame using Pandas.
Filtering Movies

Filters the dataset to include only movies (type == 'Movie').
Creates a subset with relevant columns: title, country, genre, release_year, and duration.
Analyzing Data

Filters movies from the 1990s.
Finds and prints the most frequent movie duration in the 1990s.
Creates a histogram to visualize the distribution of movie durations in the 1990s.
Counting Short Movies

Filters and counts the number of short action movies (duration < 90 minutes) from the 1990s.
## Visualizing Data

Creates a scatter plot showing the duration of movies by release year in the 1990s, color-coded by genre:
Green for Children/Documentaries
Blue for Stand-Up
Red for Other Genres
## Results
Most Frequent Movie Duration in the 1990s: Prints the duration that appears most frequently.
Histogram: Displays the distribution of movie durations in the 1990s.
Short Action Movies Count: Prints the number of short action movies from the 1990s.
Scatter Plot: Visualizes movie duration by release year, with color-coding for genres.



Feel free to customize the README file according to your preferences or any additional information you want to include.
