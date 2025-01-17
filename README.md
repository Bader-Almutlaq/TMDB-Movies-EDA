# TMDb Movies EDA
This project investigates and performs EDA and some data wrangling on a dataset containing information about 10,000 movies collected from The Movie Database (TMDb). This data set is found on [Kagle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata). The dataset was modified by [Udacity](https://www.udacity.com). The goal of this project is to explore the factors that influence the popularity of movies and identify the genres with the highest revenue.

## Table of Contents
- [TMDb Movies EDA](#tmdb-movies-eda)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Dataset](#dataset)
  - [Process](#process)
  - [Technologies Used](#technologies-used)
  - [Requirements](#requirements)
  - [Installation Instructions](#installation-instructions)
  - [Usage](#usage)
  - [Acknowledgment](#acknowledgment)

## Features
- Handle missing values and inconsistent data for analysis.
- Analyze factors influencing movie popularity.
- Identify genres with the highest revenue.
- Visualize relationships between key features.

## Dataset
- **Dataset**: [TMDb Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
  
- **Features**:
  
   | **Feature**              | **Description**                                                                                        |
   | :----------------------- | :----------------------------------------------------------------------------------------------------- |
   | **id**                   | Unique identifier for the movie in the dataset.                                                        |
   | **imdb_id**              | Unique identifier for the movie on IMDb.                                                               |
   | **popularity**           | Popularity score of the movie, possibly derived from audience ratings, views, or engagement metrics.   |
   | **budget**               | The budget of the movie in US dollars (as an integer, without adjustment for inflation).               |
   | **revenue**              | The revenue generated by the movie in US dollars (as an integer, without adjustment for inflation).    |
   | **original_title**       | The original title of the movie.                                                                       |
   | **cast**                 | The main cast of the movie, with names separated by a delimiter (e.g.,`\|`).                           |
   | **homepage**             | The URL of the official homepage of the movie (if available).                                          |
   | **director**             | The name of the director of the movie.                                                                 |
   | **tagline**              | A tagline or promotional slogan associated with the movie.                                             |
   | **keywords**             | Keywords or phrases describing the themes, events, or significant elements in the movie.               |
   | **overview**             | A brief summary or description of the movie plot.                                                      |
   | **runtime**              | The runtime of the movie in minutes.                                                                   |
   | **genres**               | The genres of the movie, with multiple genres separated by a delimiter (e.g., `\|`).                   |
   | **production_companies** | The production companies involved in creating the movie, separated by a delimiter (e.g., `\|`).        |
   | **release_date**         | The release date of the movie, formatted as a string.                                                  |
   | **vote_count**           | The number of votes the movie received on a rating platform.                                           |
   | **vote_average**         | The average rating of the movie based on user votes, typically on a scale of 1 to 10.                  |
   | **release_year**         | The year the movie was released.                                                                       |
   | **budget_adj**           | The budget of the movie adjusted for inflation to account for changes in the value of money over time. |
   | **revenue_adj**          | The revenue of the movie adjusted for inflation.                                                       |
  
## Process
  - Data wrangling to clean missing and inconsistent data.
  - Exploratory Data Analysis (EDA) to investigate relationships and trends.

## Technologies Used
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

## Requirements
- Python 3.7+
- Required Python packages:
  - pandas
  - numpy
  - matplotlib

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd tmdb-movie-analysis

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and run the `analysis.ipynb` file.

## Usage
1. Ensure the dataset file `tmdb-movies.csv` is in the project directory.
2. Follow the steps in the `analysis.ipynb` notebook to load, clean, and analyze the data.
3. Visualizations and insights will be displayed in the notebook.

## Acknowledgment
- Dataset provided by [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
- The dataset is modified and provided by [Udacity](https://www.udacity.com) as part of Udacity's Data Analyist Nanodegree
