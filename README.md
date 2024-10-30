![Description of Image](https://github.com/bEEkEEper254/Dsc_phase2_group6_project/blob/main/Film2.webp)
 # Exploratory Data Analysis for New Movie Studio Insights
## Authors:
1. Stephen Otieno
2. Immaculate Kithei
3. Augustine Komen
4. Godwin Mutuma
5. Sharleen Liz
6. Dennis Muuo

## Project Overview
The company has decided to launch a new movie studio but currently lacks experience in the film industry. As data analysts, our task is to explore the film industry landscape and identify the characteristics of top-performing films at the box office. By analyzing these trends, we aim to provide the studio with actionable insights to guide their film production strategy.

## Business Understanding
To help the studio make informed decisions, we will address the following key business questions:

1. **What genres are most successful at the box office?**
2. **How does the average rating correlate with box office success?**
3. **Which seasons do movie releases perform best?**
4. **What is the relationship between production budget and worldwide gross?**
5. **Which are the top-rated genres?**

Our analysis will provide the studio with a clear understanding of these factors, supporting a data-driven approach to film production and strategic planning.
### Data Understanding 
The following data sources were used to gather information for the analysis:

- [Box Office Mojo](https://www.boxofficemojo.com) - Provides comprehensive box office data.
- [IMDB](https://www.imdb.com) - Source for movie ratings, reviews, and cast information.
- [Rotten Tomatoes](https://www.rottentomatoes.com) - Aggregates critic and audience ratings.
- [TheMovieDB](https://www.themoviedb.org) - Offers movie metadata, ratings, and reviews.
- [The Numbers](https://www.the-numbers.com) - Source for financial data on movies, including box office performance and budgets.
The data represents a comprehensive collection of information on films, including their financial performance, ratings, genres, and other attributes. The sample includes a diverse range of films across different genres, time periods, and budgets.

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
