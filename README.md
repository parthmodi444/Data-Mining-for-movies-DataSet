This project involves fetching movie data from the **TMDB (The Movie Database) API**, processing it, and performing data analysis. The goal is to extract insights from popular movies, including their genres, and visualize the data to draw meaningful conclusions.

## Overview

### Step 1: Fetching Popular Movies Data
- The TMDB API is called to retrieve data about popular movies.
- Data is fetched in terms of pages to handle large datasets.
- A short delay is added between API calls to avoid overwhelming the server.

### Step 2: Fetching Genre Data
- Another API call is made to fetch the list of movie genres along with their IDs.
- A mapping function is created to map genre IDs to their corresponding names.
- This mapping is applied to the original dataset to replace genre IDs with genre names.

### Step 3: Data Processing and Analysis
- The processed data is saved into a CSV file.
- The CSV file is read in another script for further cleaning and transformation.
- Data visualization is performed to analyze trends and patterns.
- Conclusions are drawn based on the analysis.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - `requests` for making API calls.
  - `pandas` for data manipulation and analysis.
  - `matplotlib` and `seaborn` for data visualization.
- **API**: TMDB API

## Installation

### Prerequisites
- Python 3.x installed on your machine.
- TMDB API key (you can get it by creating an account on [TMDB](https://www.themoviedb.org/)).
