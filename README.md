# 🎬 TMDB Data Analysis Project

This project explores and analyzes a large dataset of movies collected from The Movie Database (TMDB). With over **10,000 movies**, this dataset offers rich insights into the film industry—including financial performance, viewer ratings, genre trends, and more.

![TMDB Logo](https://pbs.twimg.com/profile_images/1243623122089041920/gVZIvphd.jpg)

---

## 📘 Table of Contents

1. [Introduction](#introduction)  
2. [Dataset Overview](#dataset-overview)  
3. [Research Questions](#research-questions)  
4. [Data Wrangling](#data-wrangling)  
5. [Exploratory Data Analysis](#exploratory-data-analysis)  
6. [Conclusions](#conclusions)

---

## 🧾 Introduction

The goal of this project is to uncover meaningful insights from the **TMDB dataset** by answering targeted research questions using data wrangling and analysis techniques. We utilize **Python** and libraries such as **Pandas**, **NumPy**, and **Matplotlib/Seaborn** to perform data cleaning and visual exploration.

---

## 📊 Dataset Overview

The dataset includes the following key features:

- `id`, `imdb_id`, `original_title`
- `popularity`, `vote_average`, `vote_count`
- `budget`, `revenue`, `budget_adj`, `revenue_adj`
- `cast`, `director`, `keywords`, `genres`
- `overview`, `tagline`, `homepage`
- `production_companies`, `release_date`, `release_year`
- `runtime`

> **Note**: Adjusted budget and revenue columns (`budget_adj`, `revenue_adj`) are inflation-adjusted values to better compare performance across years.

---

## ❓ Research Questions

The following questions guide the analysis:

1. 🏆 What are the **Top 5 Movies of All Time** by **Revenue** and **Profit Earned**?
2. 🎥 What are the **Top 5 Movies as per Viewer Votes**?
3. 💰 What are the common characteristics of **High Revenue Movies** (e.g., genre, runtime)?
4. 📈 How has **Profit Changed Year-over-Year** for movies?
5. 👨‍🎤 Who are the **Most Frequently Appearing Actors/Actresses**?
6. 🎭 What are the **Genre Trends** in movies over the years?
7. 🌟 Which **Genres Have Been the Most Popular** over time?
8. ⏱️ How has the **Average Running Time** of movies evolved?

---

## 🔧 Data Wrangling

Data cleaning steps include:
- Handling missing and null values
- Removing duplicate entries
- Filtering invalid or zero-value budget/revenue rows
- Parsing lists (e.g., genres, cast) from string format
- Converting `release_date` to `datetime` format

---

## 📈 Exploratory Data Analysis

Visualizations and summary statistics were used to:
- Compare average revenue across genres and years
- Analyze actor frequency and co-appearances
- Observe vote trends and movie runtimes
- Explore correlations between budget, popularity, and profit

---

## ✅ Conclusions

- **Top-Grossing Movies** tend to have larger budgets, feature popular actors, and often belong to action or adventure genres.
- Genres like **Drama, Comedy, and Action** dominate the movie industry.
- **Viewer votes** and **popularity** are moderately correlated, but not always indicators of profitability.
- There’s an observable **increase in movie runtimes** and **budget sizes** over the decades.
- **Profitability is inconsistent year-to-year**, influenced by a few blockbuster successes.

---

## 💼 Tools Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📬 Contact

**Waqar Ahmed**  
📧 Email: waqar.nu@gmail.com  
🔗 GitHub: [waqar-ahmed91](https://github.com/waqar-ahmed91)

---

> *Note: This project is for educational and analytical purposes only. All data and visuals are used under the guidelines of fair use.*

