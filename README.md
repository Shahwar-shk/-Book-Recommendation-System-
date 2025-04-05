# -Book-Recommendation-System-
# 📚 Book Recommendation System

This project is a content-based book recommendation system built using collaborative filtering techniques. It helps users discover new books based on the preferences and ratings of other users.

---

## 📌 Features

- ✅ Cleaned and merged data from three sources: `Books.csv`, `Users.csv`, and `Ratings.csv`
- ✅ Filtered for popular books with sufficient ratings
- ✅ Created a pivot table of users vs books
- ✅ Used cosine similarity with K-Nearest Neighbors (KNN)
- ✅ Returns top 5 similar books for a given book title

---

## 🧰 Tech Stack

- **Python**
- **Pandas & NumPy**
- **Scikit-learn** (KNN)
- **Jupyter Notebook**

---

## 📁 Dataset

The dataset used is from the [Book-Crossing Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset), which contains:
- `Books.csv` – Book titles, authors, publishers, and ISBNs
- `Users.csv` – User demographics
- `Ratings.csv` – User ratings for books

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/book-recommendation-system.git
   cd book-recommendation-system
