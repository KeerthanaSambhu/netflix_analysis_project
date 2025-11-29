# Netflix Data Analysis Project
**By Keerthana Sambhu**

<p align="center">
  
  <!-- Python version -->
  <img src="https://img.shields.io/badge/Python-3.10-blue" alt="Python">

  <!-- Jupyter Notebook -->
  <img src="https://img.shields.io/badge/Notebook-Jupyter-orange" alt="Jupyter">

  <!-- License -->
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">

  <!-- GitHub last commit -->
  <img src="https://img.shields.io/github/last-commit/KeerthanaSambhu/netflix_analysis_project" alt="Last Commit">

  <!-- Repo size -->
  <img src="https://img.shields.io/github/repo-size/KeerthanaSambhu/netflix_analysis_project" alt="Repo Size">

</p>

This project explores Netflix’s content library, including Movies and TV Shows, genres, ratings, actors, directors, and trends over time.

## Key Objectives

- Explore Netflix content by **type** (Movies vs TV Shows)
- Analyze **genres**, **ratings**, and **countries**
- Identify **top actors and directors**
- Observe **trends over time** (added year, release year)
- Create **interactive and static visualizations** for insights

## Dataset

- Source: netflix_titles.csv (available in /data folder or via Kaggle)
- 8807 entries
- 12+ columns including title, type, release_year, rating, listed_in (genres), cast, director, country

## Visualizations

### Movies vs TV Shows

![Movies vs TV Shows](plots/movies_vs_tv.png)

### Top Genres

![Top Genres](plots/top_genres.png)

### Rating Distribution

![Rating Distribution](plots/rating_distribution.png)

## Key Insights

- Netflix has **more Movies than TV Shows**
- Most popular genres: **International, Dramas, Comedies**
- Top countries producing content: **USA, India, UK**
- Prolific actors and directors dominate multiple titles
- Netflix content growth has been increasing year by year

## Technologies Used

- Python, Pandas, NumPy
- Jupyter Notebook
- Matplotlib, Seaborn, Plotly
- Git & GitHub

## Project Structure

```
netflix_analysis_project/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_analysis.ipynb
├── plots/
│   ├── movies_vs_tv.png
│   ├── top_genres.png
│   └── rating_distribution.png
└── README.md
```


## How to Run

1. Clone the repository:

```bash
git clone https://github.com/KeerthanaSambhu/netflix_analysis_project.git
Open notebooks/netflix_analysis.ipynb in Jupyter Notebook

Run the cells sequentially to explore the analysis

Keerthana Sambhu — Project Complete!