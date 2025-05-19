# 🎥 Indian Movie Recommendation System

> A smart content-based movie recommender that helps you discover your next favorite Indian film — powered by **Python**, **Pandas**, and **Scikit-learn**!

---

## 📌 What is this?

This is a **Content-Based Movie Recommender System** built using **TF-IDF Vectorization** and **Cosine Similarity**. By analyzing movie **genres** and **descriptions**, the system recommends films similar to the one you like.

---

## 🧠 How It Works

1. ✅ **Data Cleaning** – Handles missing values in genre and description columns.
2. 🔗 **Metadata Creation** – Combines genre and description into a single text field.
3. ✍️ **TF-IDF Vectorization** – Converts metadata into numeric vectors.
4. 📐 **Cosine Similarity** – Computes similarity scores between movies.
5. 🎯 **Top-5 Recommendations** – Returns the most similar movies to the input.

---

## 🗃️ Dataset

Make sure your CSV file is named **`Indian_movies.csv`** with the following columns:
- 🎬 `Movie Names`
- 🎭 `Genere`
- 📝 `Description`

The system automatically renames and processes them internally as:
- `Title` = Movie Names
- `Genre` = Genere

---

## 🚀 Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/indian-movie-recommender.git
cd indian-movie-recommender
