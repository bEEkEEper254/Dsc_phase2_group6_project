 # Exploratory Data Analysis for New Movie Studio Insights
## Authors:
1. Stephen Otieno
2. Immaculate Kithei
3. Augustine Komen
4. Godwin Mutuma
5. Sharleen Liz
6. Dennis Muuo

## Overview
This repository contains a Jupyter Notebook (`film_industry.ipynb`) that provides an analysis of various aspects of the film industry, including trends in movie ratings, box office revenue, and other key factors. The goal of this analysis is to uncover insights into what drives success in the film industry.

## Contents of the Notebook

### Data Cleaning and Preparation
1. **Handling Missing Values**: Missing values are identified and filled using appropriate statistics (e.g., mean, mode, median), or rows with missing data are removed.
2. **Removing Duplicates**: Duplicated rows are identified and removed to ensure data integrity.
3. **Renaming Columns**: Columns are renamed to improve clarity and consistency in the dataset.
4. **Converting to Date-Time Format**: Relevant columns are converted to date-time format for time-based analysis.
5. **Adjusting Data Types**: Columns are converted to appropriate data types (e.g., integers, floats, categories).
6. **Merging Datasets**: Relevant datasets are merged based on common keys to create a unified dataset for analysis.

### Exploratory Data Analysis
- **Box Office Revenue Analysis**: Examines total revenue by year, revenue by genre, and top-grossing movies.
- **Audience Demographics**: Analyzes the age, gender, and geographic distribution of the cinema audience, as well as spending habits.
- **Genre Popularity**: Tracks genre trends over time, identifying which types of movies have gained or lost popularity.
- **Streaming vs. Box Office**: Compares traditional box office revenue with streaming revenue and assesses the impact of streaming on theater attendance.
- **Social Media Sentiment**: Analyzes social media sentiment around major releases to gauge audience reaction and interest.
- **Viewer Ratings**: Explores average movie ratings by genre and their correlation with box office performance.

### Correlation Analysis
- **Relationship Between Rating and Revenue**: A Pearson correlation analysis is conducted to examine the relationship between average movie ratings and worldwide gross revenue.

### Visualizations
The notebook includes various visualizations such as:
- **Time Series Plots**: To show trends in revenue and popularity over time.
- **Heatmaps**: For geographic distribution of audience demographics.
- **Bar and Pie Charts**: For comparisons across genres, studios, and revenue distribution channels.
- **Scatter Plots**: For examining relationships like ratings vs. box office performance.

## Key Findings
- A positive correlation was found between movie ratings and box office performance, indicating that higher-rated movies tend to perform better.
- Streaming platforms have had a notable impact on theater attendance, especially for certain genres.
- Specific genres, such as action and family movies, show seasonal trends in release and revenue.

## Requirements
To run the notebook, the following packages are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

Install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scipy
