## Comprehensive Analysis of Netflix Data

### Introduction
This report documents the analysis of a Netflix dataset to explore characteristics of TV shows and movies, focusing particularly on short-duration movies. The analysis involves filtering data, descriptive statistics, and visualizing movie durations over time by genre.

### Sections

#### 1. Dataset Overview
- **Objective**: Provide an overview of the dataset.
- **Dataset**: A CSV file containing Netflix data.
- **Method**: Load the dataset using Pandas and examine its structure.

#### 2. Filtering TV Shows and Movies
- **Objective**: Separate the dataset into TV shows and movies for focused analysis.
- **Method**:
  - Filter the dataset to create subsets for TV shows and movies.
  - Further filter movies to include only relevant columns (`title`, `country`, `genre`, `release_year`, `duration`).

#### 3. Analyzing Short Movies
- **Objective**: Identify and analyze movies with a duration of less than 60 minutes.
- **Method**:
  - Filter the `netflix_movies` dataset to include only movies with a duration of less than 60 minutes.
  - Print the subset of short movies to identify trends in country and genre.

#### 4. Descriptive Statistics
- **Objective**: Validate observations about short movies using descriptive statistics.
- **Method**:
  - Use the `describe` function on the `genre` and `country` columns of the `short_movies` dataset.
- **Outcome**: The descriptive statistics confirm that most short movies are from the United States and belong to the genre of Documentaries.

#### 5. Visualizing Movie Durations by Year and Genre
- **Objective**: Visualize the relationship between movie duration and release year, colored by genre.
- **Method**:
  - Assign colors to movies based on their genre.
  - Create a scatter plot with release year on the x-axis and duration on the y-axis.
  - Use Matplotlib to generate the plot and add a legend indicating genres.

#### 6. Evaluation of Movie Duration Trends
- **Objective**: Assess whether movies are getting shorter over time.
- **Method**: Examine the scatter plot and analyze the distribution of movie durations by release year.
- **Outcome**: The analysis suggests that we cannot conclusively determine that movies are getting shorter based on the available data.

### Conclusion
The analysis of the Netflix dataset reveals key characteristics of short-duration movies, particularly their prevalence in the United States and the genre of Documentaries. The scatter plot visualization provides insights into the trends of movie durations over the years, though it does not conclusively support the notion that movies are getting shorter.

This comprehensive analysis leverages descriptive statistics and visualization techniques to explore Netflix movie data, providing valuable insights into the characteristics and trends of movie durations.
