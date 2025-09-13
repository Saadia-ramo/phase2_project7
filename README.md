![](https://img2.chinadaily.com.cn/images/202412/07/6753a70ba310f1268d863e6e.jpeg)

# Movie Market Analysis: Data-Driven Insights for Strategic Movie Production

### Authors : 
   ##              Marylyne
   ##              Cindy
   ##              Trevor
   ##              Halima

## Project Overview
This project focuses on analyzing movie market data to deliver **strategic insights** for launching a new movie studio.  
By leveraging **Python** and **SQL**, we explore factors such as **box office performance, audience ratings, budgets, genres, and release timing** to uncover what makes movies successful.  

The aim is to translate data-driven insights into **practical recommendations** that stakeholders in the film industry can use to minimize risk and maximize profitability.  

In today’s entertainment industry, major players like **Netflix** and **Amazon Studios** are reshaping the landscape through original content. Inspired by their success, our company seeks to establish a new studio with a strong **data-informed foundation**.

## Business Understanding
### Real-World Problem
The film industry is high-stakes: millions of dollars are invested in production, yet only a fraction of films become profitable.  
Challenges include:
- Huge **production & marketing costs**
- Rapidly shifting **audience preferences**
- Technological disruption & streaming
- Fierce competition among studios

Our company’s challenge is to enter this space with **limited experience** but high ambition. To succeed, we must understand **what drives success** and **how to avoid failures**.

---

## Stakeholders
- 🎬 **Head of Movie Studio** – Strategic production guidance  
- 💰 **Investment Team** – Profitable, low-risk financial decisions  
- 🏗️ **Operations Team** – Planning & resource allocation  
- ⚖️ **Risk Management Team** – Lessons from past failures & successes  
- 📊 **Monitoring & Evaluation Team** – Metrics for ongoing improvements  
- 📢 **Marketing Team** – Target audience insights for campaigns  
- 👥 **Audience** – Better content aligned with preferences  

---

## Business Value
Our analysis provides competitive advantages:
- **Market Alignment** – Understanding audience-driven genres & trends  
- **Investment Efficiency** – Smarter budget allocation  
- **Content Strategy** – Building a focused, profitable film portfolio  
- **Competitive Positioning** – Benchmarking against leaders  
- **Risk Reduction** – Avoiding historical pitfalls  

---

## Project Goals
- Identify **box office success drivers**  
- Understand **market trends**  
- Develop **actionable insights** for production  
- Support **investment decisions**  
- Lay a foundation for a **data-driven studio strategy**  

---

## Key Business Questions
1. How does a movie’s **budget** affect revenue?  
2. Which **genres and directors** consistently perform best?  
3. What patterns emerge from **audience ratings and runtimes**?  
4. Does **release timing** significantly impact success?  

---

## Data Understanding and Analysis

### Data Sources
- [Box Office Mojo](https://www.boxofficemojo.com) – Revenues  
- [IMDb](https://www.imdb.com/) – Ratings & movie basics  
- [Rotten Tomatoes](https://www.rottentomatoes.com/) – Reviews & critic sentiment  
- [The Movie DB](https://www.themoviedb.org/) – Metadata  
- [The Numbers](https://www.the-numbers.com/) – Budgets & grosses  

### Key Datasets
- **im.db** – SQLite database with 146,144 movies  
- **bom.movie_gross.csv.gz** – Box office gross (3,387 movies)  
- **tn.movie_budgets.csv.gz** – Production budgets & worldwide grosses (5,782 movies)  

---

## Data Overview

### IMDb Dataset
- **Movie Basics**: 146k records (titles, genres, runtime, release year)  
- **Ratings**: 73k records (average rating + votes)  
- **Missing Data**: ~22% runtimes, ~4% genres  

### Box Office Mojo Dataset
- **Records**: 3,387 (2010–2018)  
- **Fields**: title, studio, domestic gross, foreign gross, year  
- **Missing**: 1,350 foreign gross values (~40%)  

### Budget Dataset (The Numbers)
- **Records**: 5,782 movies  
- **Fields**: budget, domestic gross, worldwide gross  
- **Quality**: Complete, no missing values  

---


## Tools Used
- **Python** – Core analysis  
- **Pandas / NumPy** – Data manipulation  
- **Matplotlib / Seaborn** – Visualization  
- **SQLite** – Querying IMDb data  
- **Jupyter Notebook** – Interactive environment  

---

## Analysis Approach
- **Data Cleaning** – Fixing missing values & duplicates  
- **Exploratory Analysis** – Genre, budget, and rating patterns  
- **Statistical Analysis** – Correlations with revenue  
- **Visualization** – Clear insights through graphs  
- **Business Insights** – Translating findings into recommendations  

---



## Key Analysis Areas
- 📊 **Genre Performance** – Best & worst financial performers  
- 💵 **Budget vs Revenue** – ROI across budget ranges  
- 🗓️ **Seasonal Trends** – Release timing strategies  
- ⭐ **Rating Impact** – Influence of critic & audience scores  
- 🏆 **Market Competition** – Benchmarking major studios  
- ⏳ **Runtime Optimization** – Ideal length by genre  

---

## Visualizations

### 1. Genre vs ROI
Genres like **Drama, Family, Fantasy** show strong ROI.  
![Genre ROI](https://github.com/user-attachments/assets/e2ea3879-d673-4b55-addb-b1ffc2abfe98)

### 2. Top 10 Directors (by Ratings)
Certain directors consistently deliver strong films.  
![Top Directors](https://github.com/user-attachments/assets/5be7cd29-732e-4e57-9a87-569295ae7032)

### 3. Revenue Analysis
Action and Sci-Fi dominate worldwide revenue.  
![Revenue Analysis](https://github.com/user-attachments/assets/b661e3ea-f44f-4cf2-bbb3-1663f1b236f9)

---
## 📈 Statistical Analysis & Tests
To validate our insights, we applied:  

1. **Correlation Analysis** → Checked linear relationships (e.g., budget vs. revenue, ratings vs. revenue).  
2. **Hypothesis Testing (t-tests, ANOVA)** →  
   - Tested if certain **genres** significantly outperform others in revenue.  
   - Compared **ratings groups** (IMDb > 7 vs. < 7) for differences in gross revenue.  
3. **Regression Models** →  
   - **Linear regression**: Predicted revenue based on budget, ratings, and runtime.  
   - **Multiple regression**: Combined financial and audience predictors.  

🔑 **Why regression?**  
Regression helps **quantify the effect size** of predictors like budget or ratings on box office revenue, allowing data-backed investment decisions rather than assumptions.  

---

### 🔑 Key Findings  
1. **Bigger Budgets Usually Mean Bigger Profits** – Movies that spend more on production often make more money, though smart mid-budget films can also perform well.  
2. **Directors Influence Success** – Well-known and experienced directors consistently deliver strong box office results.  
3. **Winning Genres** – Action, Sci-Fi, and Adventure movies attract the most audiences and dominate earnings.  
4. **Release Timing Matters** – Films released during **holidays and summer** seasons perform better than those released at other times.  

### 📌 Business Recommendations  
- **Prioritize Action, Adventure, Sci-Fi, and Fantasy films** → These genres have the highest audience demand and revenue potential.  
- **Balance film budgets** → Avoid spending only on mega-budget projects; invest in a mix of **mid-budget and high-budget films** to spread financial risk.  
- **Work with proven directors** → Experienced directors with past box office hits increase the chances of success.  
- **Plan release dates carefully** → Schedule major films during **summer and holiday seasons** to maximize audience turnout and revenue.  

---

## 📌 Final Note
This analysis equips the new movie studio with a **clear, data-driven strategy** for entering the film industry. By aligning with proven audience demand, carefully managing budgets, and timing releases effectively, the studio can **reduce risks, optimize profitability, and build a strong competitive presence**.  


## Questions?
Feel free to reach out or submit issues in this repo!
