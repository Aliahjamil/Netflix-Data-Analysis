# 🎬 Netflix Movie Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

An **Exploratory Data Analysis (EDA)** project that analyzes a dataset of **9,827 movies** to uncover insights into genres, audience ratings, popularity, and release trends using Python.

---

## 📌 Project Overview

This project demonstrates the complete EDA workflow, including:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation

The objective is to understand movie trends and answer real-world business questions through data analysis.

---

## 🎯 Business Questions

- What is the most frequent movie genre?
- Which rating category contains the highest number of movies?
- Which movie has the highest popularity and what is its genre?
- Which movie has the lowest popularity and what is its genre?
- Which release year contains the highest number of movies?

---

## 📂 Dataset

The dataset contains **9,827 movie records** with the following columns:

| Column | Description |
|---------|-------------|
| Release_Date | Movie release date |
| Title | Movie title |
| Overview | Movie description |
| Popularity | Popularity score |
| Vote_Count | Total votes |
| Vote_Average | Average rating |
| Original_Language | Original language |
| Genre | Movie genre(s) |
| Poster_Url | Poster image URL |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔄 Data Preprocessing

- Converted `Release_Date` to datetime and extracted the release year.
- Removed unnecessary columns:
  - Overview
  - Original_Language
  - Poster_Url
- Categorized `Vote_Average` into:
  - Not Popular
  - Below Average
  - Average
  - Popular
- Removed missing values.
- Split multiple genres using `explode()` for better analysis.

---

## 📊 Exploratory Data Analysis

The project includes visualizations for:

- 🎭 Genre Distribution
- ⭐ Vote Average Distribution
- 📈 Movie Popularity Analysis
- 📅 Release Year Distribution

---

## 📈 Key Findings

- 🎭 **Drama** is the most frequent movie genre.
- ⭐ Movies in the **Popular** category are the largest group.
- 🕷 **Spider-Man: No Way Home** has the highest popularity score.
- 🎬 **The United States vs. Billie Holiday** and **Threads** have the lowest popularity values.
- 📅 **2020** recorded the highest number of movie releases.

---

## 📁 Project Structure

```text
Netflix-Movie-Data-Analysis/
│
├── Netflix_Movie_Data_Analysis.ipynb
├── mymoviedb.csv
├── README.md
├── requirements.txt
└── images/
    ├── genre_distribution.png
    ├── vote_distribution.png
    ├── popularity_analysis.png
    └── release_year_distribution.png
```

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/Netflix-Movie-Data-Analysis.git
```

Navigate to the project:

```bash
cd Netflix-Movie-Data-Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `Netflix_Movie_Data_Analysis.ipynb` and run all cells.

---
## 🚀 Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Develop a movie recommendation system.
- Perform sentiment analysis on movie descriptions.
- Deploy the project using Streamlit.

---

## 👩‍💻 Author

**Aliah Jamil**
