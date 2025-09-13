![](istockphoto.jpg)

# Movie Market Analysis: Data-Driven Insights for Strategic Movie Production

### Authors : 
##              Marylyne
##              Cindy
##              Trevor
##              Halima

## Project Overview
This project focuses on analyzing movie market data to deliver strategic insights for launching a new movie studio. By leveraging a combination of Python and SQL, we explore key factors such as box office performance, audience ratings, and industry trends to determine which types of films are currently most successful. The goal is to translate these data-driven insights into practical recommendations that real-world stakeholders in the film industry can use to make informed decisions.

In today’s rapidly evolving entertainment landscape, major companies are increasingly investing in original video content to attract and retain viewers while maximizing revenue streams. Inspired by the achievements of streaming giants like Netflix and Amazon Studios, our company plans to establish a new movie studio focused on producing and distributing original films. This analysis aims to guide the studio’s strategic direction by identifying high-potential genres, audience preferences, and market dynamics critical for competitive success.


## Business Understanding

### Real-World Problem

The film industry is known for its high financial stakes, where millions of dollars are invested in producing each movie, but only a small percentage achieve blockbuster success and generate substantial returns. This creates a high-risk environment for investors and studios alike, where unpredictable audience tastes and market dynamics can make or break a film’s profitability.

Our company aims to break into this competitive industry by launching a new movie studio. However, entering the movie production business without prior experience poses significant challenges. The industry’s inherent risks stem not only from the enormous costs associated with production, marketing, and distribution but also from rapidly shifting audience preferences, technological disruptions, and evolving content consumption habits.

To minimize these risks and improve the likelihood of success, it is essential to understand current market trends and factors that contribute to a movie’s commercial performance. This project seeks to analyze box office data, audience ratings, genre popularity, and other relevant market indicators to provide actionable insights.

By doing so, the analysis will empower the studio’s leadership to make well-informed decisions on what types of films to produce, how to position these films in the market, and when to release them. Ultimately, this approach aims to align movie production efforts with market demand, reduce financial risk, and maximize profitability in an unpredictable industry landscape.


## Stakeholders

- **Head of Movie Studio:** Data-driven insights to shape production strategy and align with market demand
- **Investment Team:** Understanding of high-performing film types to reduce financial risk and guide profitable decisions
- **Operations Team:** Trend identification for streamlined planning, budgeting, and resource allocation
- **Risk Management Team:** Insights into past failures and successes to minimize financial and reputational risks
- **Monitoring, Evaluation & Learning Team:** Performance metrics and trend analysis for continuous improvement
- **Marketing Team:** Target audience insights and market segmentation to design effective promotional campaigns and maximize reach
- **Movie Enthusiasts / Audience:** Understanding viewer preferences and trends to tailor content offerings and enhance engagement

## Business Value

This analysis delivers key strategic advantages:

- **Market Alignment:** Identifying genres, themes, and characteristics of high-performing films
- **Investment Efficiency:** Optimizing budget-to-revenue trends for maximum returns
- **Content Strategy Development:** Building a focused, high-impact film portfolio
- **Competitive Positioning:** Benchmarking against industry leaders
- **Risk Reduction:** Avoiding common pitfalls through historical success/failure analysis

### Project Goals

- Identify Box Office Success Drivers
- Understand Market Trends
- Develop Actionable Production Insights
- Support Strategic Investment Decisions
- Lay Foundation for Data-Driven Content Strategy

###  Key Business Questions

1. How does a movie’s budget affect its revenue?
2. Which genres and directors consistently yield high returns?
3. What patterns emerge from audience ratings and runtimes?

## Data Understanding and Analysis

## Source of Data


This analysis focuses on the following datasets that provide comprehensive insights for identifying box office success drivers and developing strategic movie production recommendations:

- [Box Office Mojo](https://www.boxofficemojo.com)
- [IMDB](https://www.imdb.com/)
- [Rotten Tomatoes](https://www.rottentomatoes.com/)
- [TheMovieDB](https://www.themoviedb.org/) 
- [The Numbers](https://www.the-numbers.com/)

* IMDB Database - Movie ratings and basic information via SQLite database (146,144 movies)
* Box Office Mojo - Box office performance data (3,387 movies)
* The Numbers - Financial performance and budget data (5,782 movies)

## Key Datasets for Analysis

- im.db - SQLite database with movie basics and ratings tables
- bom.movie_gross.csv.gz - Box office gross data with domestic/foreign revenue
- tn.movie_budgets.csv.gz - Production budgets and worldwide gross revenue

# Data Overview

<p align="center">
</p>



## IMDB Dataset

Movie Basics: 146,144 records with titles, genres, runtime, release year
Movie Ratings: 73,856 records with average ratings and vote counts
Missing Data: 31,739 runtime values, 5,408 genre classifications

## Box Office Mojo Dataset

Records: 3,387 movies (2010-2018)
Key Fields: Title, studio, domestic gross, foreign gross, year
Missing Data: 28 domestic gross, 1,350 foreign gross values

## Budget Dataset - The Numbers

Records: 5,782 movies with complete financial data
Key Fields: Production budget, domestic gross, worldwide gross
Data Quality: Complete dataset with no missing values

## Description of Data

The dataset includes the following key features:

- Title: Movie name
- Genre: Genre of the movie
- Director: Director’s name
- Release Year: Year of release
- Budget ($): Budget in dollars
- Revenue ($): Revenue in dollars
- Runtime (min): Duration of the movie
- Rating (0-10): Audience score

## Project Structure

## Tools Used

-  **_Python_** - Primary programming language
-  **_Pandas_** - Data manipulation and analysis
-  **_NumPy_** - Numerical computations
-  **_Matplotlib/Seaborn_** - Data visualization
-  **_SQLite_** - Database querying for IMDB data
-  **_Jupyter Notebook_** - Interactive analysis environment

## Analysis Approach

- **Data Exploration** - Understanding structure and quality of IMDB, Box Office Mojo, and budget datasets
- **Data Cleaning** - Handling missing values, duplicates, and inconsistencies in the three core datasets
- **Exploratory Analysis** - Identifying patterns in successful films across genres, budgets, and ratings
- **Statistical Analysis** - Correlations between movie characteristics, ratings, and box office performance
- **Business Insights** - Translating findings into actionable recommendations for strategic movie production

## Key Analysis Areas

* **Genre Performance Analysis** - Which genres perform best financially
* **Budget vs. Revenue Relationships** - ROI patterns across budget ranges
* **Seasonal Trends** - Optimal release timing strategies
* **Rating Impact** - How critical and audience scores affect box office
* **Market Competition** - Studio performance and market share analysis
* **Runtime Optimization** - Ideal movie lengths for different genres

## Expected Deliverables

1. *Three Concrete Business Recommendations* for the new movie studio
Comprehensive.
2. *Visualizations* supporting key findings.
3. *Performance Metrics* for measuring success factors.
4. *Risk Assessment* identifying potential pitfalls to avoid.

## Key Findings Focus
The analysis will concentrate on:

+ Identifying the most profitable movie genres and characteristics
+ Understanding budget allocation strategies for maximum profitability.
+ Determining optimal marketing strategies.
+ Benchmarking against successful studios and production companies.

## Visualizations

Here are three key visualizations for our analysis

1. Genre vs. Return on Investment (ROI) bar graph- Drama,Family,Fantasy genres tend to outperform others in terms of return on investment (ROI), highlighting genre-based opportunities.
   <img width="730" height="387" alt="image" src="https://github.com/user-attachments/assets/e2ea3879-d673-4b55-addb-b1ffc2abfe98" />
3.  Top 10 highly rated directors
   <img width="712" height="424" alt="image" src="https://github.com/user-attachments/assets/5be7cd29-732e-4e57-9a87-569295ae7032" />
4.  Revenue Analysis
   <img width="609" height="387" alt="image" src="https://github.com/user-attachments/assets/b661e3ea-f44f-4cf2-bbb3-1663f1b236f9" />


## Conclusion

### Summary of Conclusions

This analysis led to three relevant findings:
1. Higher Budget, Higher Revenue: There is a clear positive correlation, suggesting studios can confidently invest in larger budgets to maximize revenue.
2. Top-Performing Directors: Certain directors consistently deliver high-grossing movies, making them prime candidates for future investments.
3.  Profitable Genres: Action and Sci-Fi movies dominate revenue charts, indicating genre-based strategic opportunities.

These insights empower stakeholders to make data-driven decisions in the highly competitive movie industry.


## Questions?
Feel free to reach out or submit issues in this repo!
