## 🎬 Movie Recommender System (Content-Based)
This project is a content-based movie recommender system that suggests movies similar to a user's favorite film by analyzing metadata—such as genres, cast, and crew. It uses natural language processing (NLP) and machine learning to deliver accurate recommendations.

## 🌐 Live App
Try the Movie Recommender System here!

## 🚀 Features
Recommends the top 5 most similar movies to any selected title.
Uses Count Vectorizer and Cosine Similarity for text-based similarity scoring.
Processes and merges data from multiple sources (movies.csv, credits.csv).
Includes a Flask web interface for easy interaction.

## 🧠 Tech Stack
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, NLTK
Framework: Flask
Tools: Jupyter Notebook, VS Code

## 🧩 How It Works

Loads and merges movie datasets (movies.csv, credits.csv).
Extracts and cleans metadata (cast, crew, genres).
Combines all relevant tags into a single text column.
Applies Porter Stemming and Count Vectorizer to generate feature vectors.
Computes a Cosine Similarity matrix (4,800 × 4,800) for similarity scoring.
Returns the top 5 most similar movies for any given input title.
Deploys the system through a Flask web interface for interactive recommendations.
