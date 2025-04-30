# 🎬 TMDB Movies Data Analysis

This project is part of the **Digital Egypt Cubs Scholarship** in collaboration with **Udacity**. It involves an exploratory data analysis (EDA) of the TMDB (The Movie Database) dataset, which contains information about over 10,000 movies, including budgets, revenues, ratings, genres, and more.

## 📌 Objectives

- Understand what factors contribute to a movie's success.
- Identify top-rated and top-revenue genres and directors.
- Explore trends in movie production and popularity over time.
- Visualize key metrics and insights using graphs and charts.

## 🧰 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Dataset Description

The dataset includes columns such as:
- `original_title`
- `release_date`
- `budget` & `revenue`
- `vote_average` & `vote_count`
- `director`, `cast`, `genres`, etc.

Source: [TMDB Movie Metadata](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

## 🧹 Data Cleaning

- Removed unnecessary columns (`homepage`, `tagline`, etc.)
- Handled missing values (especially in `vote_average`)
- Converted data types and parsed dates

## 📈 Key Insights

- Most popular genres over the years
- Average revenue per genre
- Top 3 revenue-generating directors
- Comparison between high-revenue and other movies
- Highest-rated movies in the dataset

## 📎 Sample Visualizations

- Revenue vs. Budget scatter plots
- Genre distribution over time
- Top directors by rating and revenue
- Runtime vs. Ratings

## 👥 Authors

By students **Basel Hossam Alshakweer** and **Sara Hossam Alshakweer**  
As part of the Digital Egypt Cubs - Udacity program.

## 📁 Files

- `project (movies).ipynb` — Main analysis notebook
- `tmdb-movies.csv` — Dataset
- `README.md` — This file
