# Netflix_data_analysis
# Netflix Movies and TV Shows Data Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-red)
![NumPy](https://img.shields.io/badge/NumPy-1.21.0-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.0-orange)

## 📌 Overview
This project analyzes a **9,827-row dataset** of Netflix movies and TV shows to uncover trends, genre distributions, and popularity metrics. Key findings include identifying the most frequent genres and the highest-rated titles, providing actionable insights for content recommendations.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Data Cleaning**: Handling missing values, standardizing categories.
- **Exploratory Data Analysis (EDA)**: Statistical summaries, visualizations.

## 📂 Dataset
- **Source**: [Netflix Movies and TV Shows | Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size**: 9,827 entries (movies/TV shows).
- **Features**: Title, director, cast, country, release year, rating, duration, genre, etc.

## 🔍 Key Steps
1. **Data Cleaning**:
   - Removed redundant columns (e.g., `show_id`, `description`).
   - Standardized genre categorization (e.g., "Comedies" → "Comedy").
   - Handled missing values for `country` and `cast`.

2. **Exploratory Analysis**:
   - Genre distribution: **Drama** (23%), **Comedy** (15%), and **Action** (12%) dominate.
   - Popularity metrics: *Spider-Man: No Way Home* had the highest viewer engagement.
   - Temporal trends: Content release peaks in December (holiday season).

3. **Visualizations**:
   - Heatmaps for missing data.
   - Bar plots for genre frequency.
   - Line charts for release trends over years.

## 📊 Results
| Metric               | Insight                          |
|----------------------|----------------------------------|
| Most Frequent Genre  | Drama (23% of titles)           |
| Highest-Rated Movie  | Spider-Man: No Way Home         |
| Release Trend        | 2021 saw 40% more releases than 2020 |


