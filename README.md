# 🎬 Movie Recommender System

A web-based application that recommends similar movies based on the selected title. Built using **Python**, **Pandas**, **Scikit-learn**, and **Streamlit**, and deployed via **Render**.

---

## 🚀 Live Demo
🌐 [Click here to try it out](https://movie-recommender-rh.onrender.com)  
*(Make sure to wait a few seconds for the Render server to wake up!)*

---

## 📸 Screenshot

![Movie Recommender Screenshot](https://github.com/riyahq/movie_recommender/blob/main/Screenshot_25-6-2025_121150_.jpeg)
)

---

## 📂 Features

- 🔍 Search and select any movie from the dropdown
- 🤖 Get 5 similar movie recommendations instantly
- 🖼️ Display movie posters and titles in a clean layout
- 🧠 Cosine similarity used for recommendation logic
- 🌐 Fully deployed on Render

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python, Scikit-learn  
- **Data**: TMDB API + movie metadata  
- **Deployment**: Render  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `streamlit`, `requests`

---

## 🧠 How It Works

1. Movie metadata is preprocessed and transformed using a **count vectorizer**.
2. **Cosine similarity** is calculated between all movie vectors.
3. When a user selects a movie, the top 5 most similar movies are retrieved.
4. Posters are fetched using the **TMDB API** and displayed.

---

## 💻 Running Locally

```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
pip install -r requirements.txt
streamlit run app.py
