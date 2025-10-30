## 🎬 Movie Recommender System (Content-Based)

This project is a content-based movie recommender system that suggests movies similar to a user’s favorite film by analyzing metadata—such as genres, cast, and crew. It uses natural language processing (NLP) and machine learning to deliver accurate recommendations.


⸻

##🌐 Live Demo
 https://movierecommender-sys.streamlit.app/

⸻

## 🚀 Features
	•	Suggests the top 5 movies most similar to your chosen movie
	•	Considers cast, crew, genres, and storyline for accurate recommendations
	•	Uses NLP and similarity metrics to measure how closely movies are related
	•	Built with Streamlit for a fast and interactive user experience
	•	Simple interface — just type or select a movie name to get suggestions instantly

⸻

## 🧠 Tech Stack
	•	Language: Python
	•	Libraries: Pandas, NumPy, Scikit-learn, NLTK
	•	Algorithms: CountVectorizer, Cosine Similarity
	•	Framework: Streamlit
	•	Development Tools: Jupyter Notebook, VS Code

⸻

## 📊 Dataset
	•	Files Used: movies.csv (movie details) and credits.csv (cast & crew)
	•	Total Records: Over 4,800 movies analyzed

⸻

## 🛠️ How It Works
	•	Data Loading: Reads and merges movies.csv and credits.csv
	•	Feature Extraction: Focuses on key fields like cast, crew, genres, and story
	•	Vectorization: Converts textual information into numerical format using CountVectorizer
	•	Similarity Calculation: Uses Cosine Similarity to find the most similar movies
	•	App Interface: Users can type or select a movie, and the system displays the top 5 closest matches

⸻

## 📦 Files Included
	•	movies.csv — Contains basic movie details
	•	credits.csv — Includes information about cast and crew
	•	movie-recommender.ipynb — Jupyter Notebook with core model logic
	•	streamlit_app.py — Source code for the Streamlit web interface
	•	requirements.txt — List of Python dependencies
