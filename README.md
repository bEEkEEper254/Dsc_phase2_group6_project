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
## Tools and Libraries
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
1. **Handling Missing Values**: Missing values are identified and filled using appropriate statistics (e.g., mean, mode, median), or rows with missing data are removed.
2. **Removing Duplicates**: Duplicated rows are identified and removed to ensure data integrity.
3. **Renaming Columns**: Columns are renamed to improve clarity and consistency in the dataset.
4. **Converting to Date-Time Format**: Relevant columns are converted to date-time format for time-based analysis.
5. **Adjusting Data Types**: Columns are converted to appropriate data types (e.g., integers, floats, categories).
6. **Merging Datasets**: Relevant datasets are merged based on common keys to create a unified dataset for analysis.
### Data Visualization
![image](https://github.com/user-attachments/assets/70a7cbc1-5f04-441e-9490-7c3d3d8f1463)
![image](https://github.com/user-attachments/assets/b48c1a71-3d96-47e1-9a28-f5c1b31eea96)
![image](https://github.com/user-attachments/assets/c094a79a-757d-4e98-a8fc-745073fecf47)
![image](https://github.com/user-attachments/assets/ae9d3585-43c6-4fec-ac32-bcb1208aac60)
![image](https://github.com/user-attachments/assets/0e20666f-436f-4af5-b4f2-3678a6da3314)
![image](https://github.com/user-attachments/assets/ac74f426-e5f2-40f9-a90b-503fb6df4632)

### Correlation Analysis
- **Relationship Between Rating and Revenue**:
- A Pearson correlation analysis is conducted to examine the relationship between average movie ratings and worldwide gross revenue.
## Analysis Summary
Our analysis process included:

**1.Data Cleaning and Preprocessing:** Cleaning and merging datasets to ensure consistency across data sources.

**2.Exploratory Data Analysis (EDA):** Examining various film attributes, such as genres, ratings, and box office performance.

**3.Visualization and Insights:** Creating visualizations to highlight key findings and trends in successful films, which we translated into actionable recommendations.

### Key Findings

Our analysis revealed several characteristics of films that tend to perform well at the box office:

**1.Top Earning Genres:** Drama is the highest-grossing genre, followed by Comedy and genre combinations like Comedy|Drama. These genres have proven to be both popular and lucrative in the film industry.

**2.Ratings and Revenue:** There is a positive correlation between a film’s average rating and its worldwide gross. Higher-rated movies tend to earn more globally.

**3.Seasonal Trends:** Summer emerges as the most profitable season for movie releases, followed by Spring. Fall and Winter seasons show significantly lower average gross revenue.

**4.Budget Impact:** Movies with higher production budgets tend to have higher worldwide gross revenues.
## Recommendations
Based on our findings, we suggest the following strategies for the studio:

**1.Focus on Producing Highly Profitable Genres**

Invest in producing Drama, Comedy, and Comedy|Drama. These genres have proven to be the most poplar and lucrative in the film industry worldwide
By targeting these genres, the studio can maximize profitability and achieve a higher returns.

**2.Invest in High-Quality Films:**

The scatter plot showing a positive correlation between average ratings and worldwide gross revenues suggests that higher-rated films tend to perform better financially. This means that your studio should prioritize producing high-quality content that can achieve higher average ratings. Quality scripts, talented directors, and experienced actors should be the focus.

**3.Leverage Seasonal and Monthly Release Trends:**

**Release Films During Summer** - The data shows that movies released in the summer perform the best, with an average worldwide gross of 113M dollars. This season sees a higher audience turnout, leading to better box office performance.

**Avoid Fall Releases** - Films released in the fall tend to perform the worst, with an average worldwide gross of 75M dollars. Planning releases outside of this season can help in maximizing box office returns.

**4.Invest in High Production Budgets:**

The scatter plot showing a positive correlation between production budget and worldwide gross means that movies with higher production budgets tend to generate higher box office revenues. Allocate substantial budgets to your movie projects to increase the likelihood of financial success.

## Overall Conclusion:
Based on our analysis, it's clear that to achieve box office success, your new movie studio should focus on producing high-quality films in the Drama, Comedy, and Comedy|Drama genres, which are currently the top earners. Additionally, there is a positive correlation between higher average ratings and increased worldwide gross revenues, emphasizing the importance of investing in quality scripts, talented directors, and experienced actors.

To capitalize on market trends, prioritize releasing films during the lucrative Summer season while avoiding Fall releases due to their lower average gross revenue. Furthermore, allocating substantial production budgets is crucial, as higher-budget films tend to generate higher box office revenues. By implementing these strategies, your studio can maximize profitability and achieve significant returns in the competitive film industry.



