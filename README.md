## Layoff Data Cleaning & Exploratory SQL Analysis

This project focuses on cleaning, standardizing, and analyzing a layoffs dataset sourced from [Kaggle](https://www.kaggle.com/datasets/salimwid/layoffs-2022). Using MySQL, I performed data wrangling and exploration on tech industry layoffs to identify trends in job cuts, funding, and company stages over time.

Although this project was inspired by a [guided walkthrough](https://www.youtube.com/watch?v=4UltKCnnnTA) from Alex The Analyst, all SQL code and steps were recreated and executed independently as part of my learning journey.

---

### Objectives
1. Clean and prepare a raw layoffs dataset for analysis.
2. Remove duplicates, standardize values, and handle nulls and incorrect data types.
3. Analyze patterns in layoffs over time and across companies, countries, and industries.
4. Identify key companies with the highest layoff impact by year and stage.

---

### Skills Demonstrated

- **SQL for Data Cleaning**
  - Removing duplicates using CTEs and `ROW_NUMBER()`
  - Standardizing strings using `TRIM()` and `UPDATE`
  - Handling missing/null values and type conversions
- **SQL for Exploratory Analysis**
  - Aggregation (`SUM`, `AVG`, `COUNT`)
  - Rolling totals with `WINDOW FUNCTIONS`
  - Trend analysis using `SUBSTRING()` and `GROUP BY`
  - Ranking top companies by layoffs using `DENSE_RANK()`

---

### Files

- [Layoffs Data Cleaning SQL](Data%20Cleaning/Data%20Cleaning%20World%20Layoffs.sql)  
- [Layoffs Exploratory SQL](Exploratory%20Data%20Analysis/MySQL%20Exploratory%20Data%20Analysis%20Project.sql)  
- [Layoffs Dataset (CSV)](Layoffs%20Dataset/layoffs.csv)


