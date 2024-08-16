

# 1990s Netflix Movies Analysis

## Overview

This project focuses on performing exploratory data analysis (EDA) on a dataset of Netflix shows and movies, specifically analyzing films released in the 1990s. The analysis aims to uncover trends and patterns in movie durations, genres, and other relevant aspects of 1990s cinema available on Netflix.

## Table of Contents

- [Project Overview](#overview)
- [Data Source](#data-source)
- [Project Structure](#project-structure)
- [Key Findings](#key-findings)
- [How to Run the Project](#how-to-run-the-project)
- [Conclusion](#conclusion)
- [Future Work](#future-work)


## Data Source

The data used in this project is from `netflix_data.csv`, which includes information such as the show's ID, type, title, director, cast, country, date added to Netflix, release year, duration, description, and genre.

## Project Structure

The project consists of the following main components:

- **netflix_data.csv**: The dataset containing Netflix shows and movies.
- **notebook.ipynb**: The Jupyter Notebook file containing all the code used for the analysis.
- **readme.md**: This README file describing the project.
- **plots/**: (Optional) A directory containing any plots or visualizations generated during the analysis.

## Key Findings

During the analysis, several key insights were uncovered:

1. **Most Frequent Movie Duration in the 1990s**:
   - The most frequent movie duration for 1990s movies on Netflix was **90 minutes**.

2. **Number of Short Action Movies Released in the 1990s**:
   - The number of action movies with a duration of less than 90 minutes released in the 1990s is **5**.

3. **Popular Genres**:
   - Action, Comedy, and Drama were the most common genres for movies in the 1990s.

4. **Duration Distribution**:
   - Movie durations in the 1990s primarily ranged from 80 to 120 minutes, with a significant concentration around 90 minutes.

## How to Run the Project

To replicate the analysis, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/data-nav/netflix_90s_analysis.git
   cd netflix_90s_analysis
   ```

2. **Install Required Libraries**:
   Make sure you have Python and the necessary libraries installed. The main libraries used are `pandas`, `matplotlib`, and `seaborn`.

   You can install the required libraries using pip:

   ```sh
   pip install pandas matplotlib seaborn
   ```

3. **Run the Jupyter Notebook**:
   Open the Jupyter Notebook (`notebook.ipynb`) to see the analysis and explore the data.

   ```sh
   jupyter notebook notebook.ipynb
   ```

4. **Explore the Data**:
   Follow along with the analysis in the notebook, or try your own EDA on the dataset.

