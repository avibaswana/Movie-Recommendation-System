#🎬 Movie Recommendation System using Collaborative Filtering

This project demonstrates a **Movie Recommendation System** implemented in a **Jupyter Notebook** using **Collaborative Filtering**. The dataset used is the **MovieLens Small Dataset** from Kaggle. The system recommends movies to users based on user-user similarities derived from past ratings.

---

## 📂 Files in the Repository

- `movierecsys.ipynb` – Main Jupyter Notebook containing the full implementation.
- `movies.csv` – Contains metadata for movies (movieId, title, genres).
- `ratings.csv` – Contains user ratings for movies (userId, movieId, rating, timestamp).

---

## 🧠 Project Overview

The recommendation system follows the **User-Based Collaborative Filtering** approach:

1. **Load and explore the data** from `movies.csv` and `ratings.csv`.
2. **Merge** the datasets to connect movie titles with ratings.
3. **Create a user-item matrix** using a pivot table.
4. **Compute user similarity** using Cosine Similarity from `scikit-learn`.
5. **Generate personalized recommendations** for users by identifying top similar users and suggesting movies they liked but the current user hasn't rated yet.

---

## 📈 Key Features

- Easy-to-understand collaborative filtering implementation.
- Uses similarity-based recommendation logic.
- Lightweight and interpretable (no deep learning or external APIs required).
- Built entirely in Python with pandas, numpy, and scikit-learn.

---

## 🚀 Getting Started

### 🔧 Prerequisites

Ensure you have the following Python packages installed:

```bash
pip install pandas numpy scikit-learn


