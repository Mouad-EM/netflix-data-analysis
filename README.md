# 🎬 Netflix Titles Data Analysis

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project explores the **Netflix Titles dataset**, which contains detailed information about thousands of movies and TV shows available on the platform.  
The goal is to apply **Exploratory Data Analysis (EDA)** and **Machine Learning techniques** to uncover insights, build predictive models, and design a recommendation system.

---
## 📌 Notebook - [Netflix Data Analysis](notebooks/netflix_data_analysis.ipynb)

## 📂 Dataset

This project uses the [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) available on Kaggle.  
Please download the dataset from Kaggle and place it in the `data/` folder before running the notebook.

## 📌 Objectives
- Analyze the distribution of content across **years, countries, and genres**.
- Identify **patterns and clusters** in Netflix's catalog.
- Build **classification models** to predict attributes (e.g., Movie vs TV Show).
- Develop a **recommendation system** to suggest similar titles.
- Apply **regression models** to estimate numeric attributes (e.g., duration).

---

## 🛠️ Tech Stack
- **Languages**: Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning**: Scikit-learn (RandomForest, KMeans, Regression)
- **NLP & Recommendation**: TF-IDF, Cosine Similarity
- **Visualization**: Matplotlib, Seaborn

---

## 📊 Key Insights
- Netflix has a strong dominance of **movies vs TV shows**.
- The **United States, India, and UK** are the top producers of Netflix content.
- Popular genres include **International Movies, Dramas, Comedies, Documentaries**.
- Classification model achieved **~99.6% accuracy** in distinguishing Movies vs TV Shows.
- Recommendation system suggests titles based on **content similarity**.

---

## 🚀 Project Structure
netflix-data-analysis/

│── notebooks/

│ └── netflix_data_analysis.ipynb

│── data/

│ └── netflix_titles.csv (or link to dataset)

│── src/

│ └── helper_functions.py

│── README.md

│── requirements.txt

---

## 📈 Results
- **Classification**: RandomForestClassifier with 99.6% accuracy.
- **Clustering**: KMeans grouped titles into meaningful clusters (e.g., family movies, crime dramas).
- **Recommendation**: Content-based filtering using TF-IDF + cosine similarity.
- **Regression**: Linear Regression to estimate duration trends.

---

## 📫 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Mouad-EM/netflix-data-analysis.git
