🎬 IMDb Movie Data Analysis – SQL Project

**📌 Project Overview**

This project performs comprehensive data analysis on IMDb movie data using SQL.

The analysis covers movie release trends, genres, ratings, votes, production houses, directors, actors, actresses, movie duration, and other movie-related insights.

The project contains 29 SQL analysis questions (Q1–Q29) and demonstrates practical SQL techniques used in data analysis.

**🎯 Project Objectives**

Analyze IMDb movie data using SQL.

Identify movie release trends over time.

Analyze movie genres and their popularity.

Find top-rated movies.

Analyze movie ratings and vote counts.

Identify top production houses.

Analyze directors, actors, and actresses.

Perform data-quality and NULL-value analysis.

Use advanced SQL techniques such as CTEs and window functions.

Generate meaningful insights from structured movie data.

**🗂️ Database Schema**

Table

Description

MOVIE

Contains movie details such as title, year, duration, country, languages, production company, and gross

GENRE

Contains movie genre information

DIRECTOR_MAPPING

Maps directors to movies

ROLE_MAPPING

Maps actors/actresses to movies and roles

NAMES

Contains names and related person information

RATINGS

Contains movie ratings and vote information

**🛠️ Technologies & Tools**

Database: MySQL

Language: SQL

Tool: MySQL Workbench / MySQL-compatible SQL environment

Dataset: IMDb Movie Data

**🧠 SQL Concepts Used**

SELECT, WHERE, ORDER BY

GROUP BY, HAVING

Aggregate functions: COUNT(), SUM(), AVG(), MIN(), MAX()

JOIN / INNER JOIN / LEFT JOIN

Subqueries

Common Table Expressions (CTEs)

CASE statements

Window functions

RANK() and DENSE_RANK()

Running totals

Moving averages

Date functions

NULL / data-quality analysis

**📊 Analysis Questions**

The SQL file contains 29 analysis questions (Q1–Q29).

Q1 – Data Overview

Analyzes the number of records and checks the overall structure of the movie dataset.

Q2 – NULL Value Analysis

Identifies NULL values across important columns and evaluates data quality.

Q3 – Movie Release Trends

Analyzes the number of movies released over different years.

Q4 – Movies by Country

Analyzes movies released in specific countries, including the USA and India.

Q5 – Unique Genres

Identifies the unique genres available in the dataset.

Q6 – Highest-Volume Genre

Finds the genre with the highest number of movies.

Q7 – Single-Genre Movies

Identifies movies that belong to only one genre.

Q8 – Average Duration by Genre

Calculates the average movie duration for each genre.

Q9 – Thriller Movie Ranking

Ranks thriller movies based on their ratings.

Q10 – Minimum and Maximum Ratings

Finds the minimum and maximum movie ratings.

Q11 – Top 10 Movies by Rating

Identifies the top 10 movies based on average rating.

Q12 – Median Rating Analysis

Analyzes the distribution of movies around the median rating.

Q13 – Top Production Houses

Identifies production houses with the highest number of successful movies.

Q14 – March 2017 USA Movies

Finds USA movies released in March 2017 with more than 1,000 votes.

Q15 – Movies Starting with “The”

Identifies movies beginning with “The” and having a rating above 8.

Q16 – Rating and Date Range Analysis

Analyzes movie ratings and release-date ranges.

Q17 – German vs Italian Movies

Compares vote counts between German and Italian movies.

Q18 – NULL Analysis in Names

Analyzes NULL values and missing information in the NAMES table.

Q19 – Top Directors

Identifies directors with strong movie performance based on the available metrics.

Q20 – Top Actors

Analyzes actors and identifies high-performing actors.

Q21 – Top Actresses

Analyzes actresses based on movie performance and ratings.

Q22 – Production House Vote Analysis

Analyzes production houses based on movie votes.

Q23 – Actor Ranking

Ranks actors using SQL ranking/window functions.

Q24 – Thriller Classification

Uses a CASE statement to classify movies based on thriller-related conditions.

Q25 – Running Total and Moving Average

Uses window functions to calculate genre-level running totals and moving averages.

Q26 – Top-Grossing Movies

Identifies top-grossing movies for each year within the top genres.

Q27 – Multilingual Production Houses

Identifies production houses associated with movies in multiple languages.

Q28 – Top Drama Actresses

Identifies the highest-performing actresses in the drama genre.

Q29 – Top 9 Directors

Ranks the top 9 directors using multiple performance metrics.

**📁 Project Structure**

IMDb-Movie-Data-Analysis-SQL/
│
├── IMDb_Movie_Data_Analysis_GitHub_Ready.sql
│
└── README.md

**▶️ How to Run the Project**

Step 1 – Install MySQL

Install MySQL and optionally MySQL Workbench.

Step 2 – Create/Open a Database

CREATE DATABASE imdb_movie_analysis;
USE imdb_movie_analysis;

Step 3 – Open the SQL File

Open IMDb_Movie_Data_Analysis_GitHub_Ready.sql in MySQL Workbench or another compatible SQL editor.

Step 4 – Execute the SQL Script

Run the script to create/load the required tables and execute the analysis queries.

Note: The SQL file contains the dataset and analysis queries. Execution time may depend on your system and database configuration.

**🔍 Key SQL Skills Demonstrated**

1. Data Cleaning

NULL-value and data-quality checks are included to understand missing information.

2. Data Aggregation

COUNT, SUM, AVG, MIN, and MAX are used to summarize movie data.

3. Joins

Multiple tables are combined to connect movies with genres, ratings, directors, actors, and actresses.

4. Subqueries and CTEs

Subqueries and Common Table Expressions are used for complex analysis.

5. Window Functions

Ranking, running totals, and moving averages are calculated using window functions.

6. CASE Statements

Conditional logic is used to classify movies based on specific conditions.

📈 Key Areas of Analysis

🎬 Movie release trends

🎭 Genre analysis

⭐ Movie ratings

🗳️ Number of votes

🏢 Production house performance

🎥 Director performance

👨 Actor performance

👩 Actress performance

⏱️ Movie duration

💰 Gross revenue

🌍 Country and language analysis

📊 Ranking and advanced analytics

🧹 Data-quality analysis

💡 Learning Outcomes

Through this project, I gained practical experience in:

Writing complex SQL queries.

Combining data from multiple relational tables.

Performing exploratory data analysis using SQL.

Applying aggregate functions.

Using joins and subqueries.

Creating CTEs for complex analysis.

Applying window functions for ranking and analytical calculations.

Handling NULL values and checking data quality.

Converting business questions into SQL queries.

Extracting useful insights from a movie dataset.

**🚀 Future Improvements**

Create an interactive Power BI dashboard using the analyzed data.

Add more advanced statistical analysis.

Perform deeper analysis of movie profitability.

Build predictive models using Python.

Add visualizations for genre, rating, and revenue trends.

Automate the data-analysis pipeline.
