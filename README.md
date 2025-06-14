# 🎬 SmartFlix: A User-Based Movie Recommendation System

This project is a beginner-friendly movie recommender system using Python. It applies **user-based collaborative filtering** and **cosine similarity** to recommend movies based on the preferences of similar users.

---

## 🧠 How It Works

- Build a **user-item matrix** from movie rating data.
- Compute **cosine similarity** between users.
- For a target user, identify the most similar user.
- Recommend movies that the similar user liked, but the target user hasn’t watched yet.

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📁 Files

- `movie_recommender.ipynb`: Main notebook
- `README.md`: Project documentation

---

## ✅ How to Run (Google Colab Recommended)

1. Open `movie_recommender.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run cells in order to:
   - Load sample user-movie rating data
   - Generate similarity matrix
   - Make personalized recommendations
3. To see recommendations, run:
   ```python
   recommend_movies(1, matrix, user_similarity_df, movie_titles)

