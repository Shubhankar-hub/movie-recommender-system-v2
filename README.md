# 🎬 Movie Recommender System

This is a content-based movie recommendation system built using Python, Streamlit, and The Movie Database (TMDb) API. It uses movie overviews and metadata to suggest similar movies based on your input.

## 🚀 Live Demo

👉 [Check the live app here](https://your-render-app-url.onrender.com)  
*(Replace with your actual deployed URL)*

---

## 🧠 How it Works

- Vectorizes movie descriptions using **TF-IDF**.
- Computes **cosine similarity** between movies.
- Recommends 5 similar movies with posters.
- Posters and metadata are fetched using the **TMDb API**.

---

## 📦 Features

- Search and select any movie from the dataset.
- Instantly get 5 movie recommendations.
- View poster, title, and overview for each suggestion.
- Responsive and clean Streamlit UI.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **Scikit-Learn**
- **Streamlit**
- **TMDb API**
- **Pickle** for storing similarity matrix

---

## 📁 Files and Structure
movie-recommender-system/
├── app.py                 # Streamlit web app script
├── movie-recommender-system.ipynb  # Jupyter notebook used for model development
├── movies_dict.pkl        # Pickled dictionary of movie data (title, id, overview)
├── similarity.pkl         # Pickled cosine similarity matrix
├── requirements.txt       # List of required Python libraries
├── Procfile               # Tells Render how to run the app
├── setup.sh               # Shell script to setup environment for deployment
├── .gitignore             # Git ignored files list
├── .gitattributes         # Git file attribute settings
└── README.md              # Project documentation (this file!)
