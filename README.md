# 🎬 Movie Recommendation System

This is a simple **Content-Based Movie Recommender System** built using **Python**, **Streamlit**, and **cosine similarity**. It recommends 10 similar movies based on the one you select, and shows the movie posters using **The Movie Database (TMDB) API**.

---

## 🚀 Features

- 🔎 Select a movie from a dropdown list
- 🤝 Recommends top 10 similar movies using cosine similarity
- 🖼️ Fetches movie posters via the TMDB API
- 🎯 Minimalistic and user-friendly Streamlit interface

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas**
- **Streamlit**
- **Pickle** (for precomputed similarity matrix and movie metadata)
- **Requests** (for fetching movie poster URLs)
- **TMDB API**

---

## 💾 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/movie-recommender.git
   cd movie-recommender

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt


3. **Make sure you have the files:**  
   ```bash
   movie_data.pkl: Contains movies DataFrame and cosine_sim matrix
   Your TMDB API key added to the fetch_poster() function

4. **Run the app**  
   ```bash
   streamlit run app.py

---

## 🧑‍💻 Author

Built by Kavindu Mihiranga

---
