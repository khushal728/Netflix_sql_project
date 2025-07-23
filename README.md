# Netflix_sql_project.

# 📊 Netflix Data Analysis using SQL
<p align="center">
  <img src="logo.png" alt="Netflix Logo" width="500"/>
</p>

## Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

## Objectives
1.Analyze the distribution of content types (movies vs TV shows).

2.Identify the most common ratings for movies and TV shows.

3.List and analyze content based on release years, countries, and durations.

4.Explore and categorize content based on specific criteria and keyword

## 📁 Dataset

- **Source**: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File Used**: `netflix_titles.csv`
- **Columns Included**:  
  `show_id`, `type`, `title`, `director`, `casts`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🛠️ Tools Used

- PostgreSQL
- SQL (with functions like `UNNEST`, `STRING_TO_ARRAY`, `CTEs`, `Window Functions`)
- PgAdmin / DBeaver / any SQL IDE

---

## 📌 Table Schema

```sql
CREATE TABLE netflix (
    show_id      VARCHAR(10),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
```
## 🔍 Key Business Questions & Queries

1.Count the Number of Movies vs TV Shows

2.Find the Most Common Rating for Movies and TV Shows

3.List All Movies Released in a Specific Year (e.g., 2020)

4.Top 5 Countries with the Most Content on Netflix

5.Identify the Longest Movie on the Platform

6.Find Content Added in the Last 5 Years

7.Content by Specific Director (e.g., Rajiv Chilaka)

8.TV Shows with More Than 5 Seasons

9.Content Count in Each Genre

10.Top 5 Years with Highest Average Content Released in India

11.All Documentaries on Netflix

12.Content Without a Director

13.Movies Featuring Salman Khan in the Last 10 Years

14.Top 10 Actors in Indian Netflix Content

15.Content Categorization Based on Keywords: 'Kill' & 'Violence'

## 📈 Sample Insight
📌 India ranks among the top countries producing Netflix content. The last 5 years have shown significant growth in regional content.

## 📬 Contact
Feel free to connect if you’re passionate about SQL, analytics, or data storytelling.

LinkedIn: [www.linkedin.com/in/khushal-joshi728]

GitHub: (https://github.com/khushal728)]

Email: [Khushalj2003@gmail.com]
