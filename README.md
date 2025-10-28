# 🎬 Movie Recommender System (Content-Based)

This project is a **content-based movie recommender system** that suggests movies similar to a user’s favorite film by analyzing metadata such as genres, cast, and crew. It uses **natural language processing (NLP)** and **machine learning** to find the most relevant recommendations.

---

##🌐 Live App
https://movierecommender-sys.streamlit.app/

---

## 🚀 Features
- Recommends the **top 5 most similar movies** to any selected title.
- Uses **Count Vectorizer** and **Cosine Similarity** for text-based similarity scoring.
- Processes and merges data from multiple sources (`movies.csv`, `credits.csv`).
- Includes a **Flask web interface** for easy interaction.

---

## 🧠 Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK
- **Framework:** Flask
- **Tools:** Jupyter Notebook, VS Code

---

## 🧩 How It Works
1. Load and merge movie datasets (`movies.csv`, `credits.csv`).
2. Extract and clean metadata (cast, crew, genres).
3. Combine all relevant tags into a single text column.
4. Apply **Porter Stemming** and **Count Vectorizer** to convert text into feature vectors.
5. Compute a **Cosine Similarity** matrix (4,800 × 4,800) to measure similarity between movies.
6. Build a function to return the top 5 most similar movies for any input title.
7. Deploy the model with Flask for interactive recommendations.

---
