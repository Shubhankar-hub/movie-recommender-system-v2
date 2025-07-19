# 🎬 Movie Recommender System with Streamlit + TMDB API

A powerful and visually appealing Movie Recommender App built using **Python**, **Streamlit**, and **TMDb API**. It helps users discover similar movies based on their selection — with real-time poster visuals!

---

## 🚀 Demo

🌐 Deployed Link: https://movie-recommender-system-v2-dmdm5xzbvr45krbkufaysc.streamlit.app/


📸 Preview:

<div align="center"> <img src="https://github.com/user-attachments/assets/31d02b1b-cb32-4e6c-9f38-5261d5a604cb" width="47%" alt="Movie App UI" /> <img src="https://github.com/user-attachments/assets/f3d613ae-8ac6-49f6-b80f-9fab7ca09fca" width="47%" alt="Recommendation Results" /> </div>


---

## 🛠️ Tech Stack

| Tool / Library | Purpose                          |
|----------------|----------------------------------|
| Streamlit      | Web Interface                    |
| Pandas         | Data handling                    |
| NumPy          | Numerical operations             |
| Pickle         | Load model and similarity data   |
| Requests       | Fetch posters from TMDb API      |

---

## 🧠 Features

- 🔍 **Search by Movie Title**
- 🎞️ **Fetch Posters using TMDB API**
- 🤖 **Recommendation Engine with Cosine Similarity**
- ⚡ Fast & Lightweight UI using **Streamlit**
- 💾 Preprocessed `.pkl` files for instant loading
- ☁️ Deployed seamlessly on **Render**

---

## 🛠️ Getting Started

### ✅ Prerequisites

- Python 3.9+
- `pip` package manager
- TMDb API Key (Free from [TMDb](https://www.themoviedb.org/))

---

### ⚙️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. **Install Dependencies**
```
pip install -r requirements.txt
```

4. **Add Environment Variables**
```
TMDB_API_KEY=your_tmdb_api_key_here
```

6. **Run the App Locally**
```
streamlit run app.py
```

### 📁 Project Structure

```
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
└── README.md
```

### 🌐 Deployment (Render)

1. Push your code to GitHub

2. Create a new Web Service on Render

3. Set Build Command to:
```
pip install -r requirements.txt
```
4. Set Start Command to:
```
streamlit run app.py --server.port=10000 --server.enableCORS=false
```
5. Add environment variable:
```
TMDB_API_KEY=your_api_key
```

:

## 👨‍💻 Developer

**Shubhankar Banerjee**  
📧 [shubhankarbanerjee0707@gmail.com](mailto:shubhankarbanerjee0707@gmail.com)  
🔗 [GitHub](https://github.com/Shubhankar-hub) | [LinkedIn](https://www.linkedin.com/in/shubhankar-banerjee-78740b258/)

---

## 📷 API Reference: TMDB

Using TMDB’s API to fetch high-resolution movie posters and metadata.  
🔗 [TMDb API Docs](https://developer.themoviedb.org/)

---

## 🙌 Acknowledgements

- **Streamlit** – for the interactive frontend  
- **The Movie Database (TMDb)** – for providing metadata and poster images  
- **Scikit-learn** – for machine learning models  

---

## ⭐ Contribute

Contributions, issues and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/Shubhankar-hub/movie-recommender-system-v2/issues)).

---

## 📜 License

Distributed under the **MIT License**.  
See [`LICENSE`](./LICENSE) for more information.


