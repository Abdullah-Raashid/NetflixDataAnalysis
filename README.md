# Movie Data Analysis

## Overview
This project analyzes a movie dataset to extract insights about movie genres, popularity, and release trends. It involves data cleaning, categorization, and visualization using Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib. 5 Questions were answered:
Q1: What is the most frequent genre in the dataset?
Q2: What genre has the highest votes?
Q3: What movie got the highest popularity? what's its genre?
Q4: What movie got the lowest popularity? what's its genre? 
Q5: Which year has the most filmed movies?" 

## Dataset
The dataset used is `mymoviedb.csv`, containing information on various movies, including their genre, popularity, release date, and vote average.

## Features and Preprocessing
- **Removed unnecessary columns**: `Overview`, `Original_Language`, `Poster_Url`
- **Converted `Release_Date` to datetime format**
- **Extracted only the year from `Release_Date`**
- **Handled missing and duplicate values**
- **Categorized `Vote_Average` into four groups**: `not_popular`, `below_avg`, `average`, `popular`
- **Split the `Genre` column** (which contained comma-separated values) into separate rows using `explode()`

## Exploratory Data Analysis (EDA)
Several visualizations were created to explore the dataset:
1. **Most frequent movie genres**
2. **Distribution of vote averages**
3. **Movie with the highest and lowest popularity**
4. **Year with the highest number of movies released**

### Key Findings
- **Most frequent genre**: Drama appears the most frequently in the dataset.
- **Highest vote category**: Around 25.5% of movies are categorized as "popular".
- **Most popular movie**: *Spider-Man: No Way Home* (Genres: Action, Adventure, Science Fiction).
- **Least popular movie**: *The United States, Thread* (Genres: Music, Drama, War, Sci-Fi, History).
- **Most active movie release year**: 2020 had the highest number of films released.

## Visualizations
- Count plots for `Genre` and `Vote_Average` distributions
- Histogram for `Release_Date`
- Identification of most/least popular movies

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Conclusion
This project provides valuable insights into movie trends, allowing for better understanding of audience preferences based on popularity, votes, and genre distribution.
