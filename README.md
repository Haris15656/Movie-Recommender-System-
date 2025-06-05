🎬 Movie Recommendation System

This project demonstrates a basic Movie Recommendation System using data from the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata). It includes two types of recommenders:

- 📈 **Weighted Rating-Based Recommender** (IMDb-style)
- 🔍 **Content-Based Recommender** (based on metadata similarity)

---

📁 Dataset

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

Both files are publicly available on Kaggle.

---

 ✅ Features
 1. **Weighted Rating-Based Recommender**
- Filters top 5% movies based on vote count.
- Applies IMDb's weighted rating formula to rank them.
- Helps recommend **critically acclaimed and popular** movies.

 2. **Content-Based Recommender**
- Uses movie metadata like overview, cast, crew, and keywords.
- Vectorizes text using **TF-IDF** and **CountVectorizer**.
- Computes cosine similarity to suggest **similar movies**.

---

## 🚀 How to Run

1. Clone this repository
2. Make sure the dataset CSV files are present in the working directory.
3. Open `movie_reccomendar_system.ipynb` in Jupyter Notebook or VSCode.
4. Run the cells step-by-step to explore both recommender systems.

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 📌 Credits

Dataset: [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## 📷 Example Output

- Top 10 highest scoring movies (weighted)
- Similar movies based on a selected title

---

Feel free to fork, experiment, and contribute! 🎉


![WhatsApp Image 2025-05-29 at 23 32 06_ef620fc4](https://github.com/user-attachments/assets/ed828314-869e-45d9-8b47-83ec5eddb9db)

