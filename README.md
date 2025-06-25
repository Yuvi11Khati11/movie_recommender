# 🎬 Movie Recommender System

A content-based movie recommendation system built with Python, Flask, and TMDB API.

## 🔍 Features

- 🔎 Search any movie by name
- 🎯 Recommends 5 similar movies based on content
- 🧠 Uses NLP techniques (`CountVectorizer` + `Cosine Similarity`)
- 🎥 Fetches live poster, rating, genres, and **YouTube trailer**
- 💾 Add and save favorite movies (stored in SQLite)
- 📦 Organized with Flask backend and HTML/CSS frontend

## 🚀 Tech Stack

- Python (Pandas, Scikit-learn, Requests)
- Flask
- HTML, CSS, JavaScript
- TMDB API
- SQLite for storing favorites

## 📂 Project Structure

movie_recommender/
├── app.py
├── recommender.py
├── favorites.db
├── .env
├── requirements.txt
├── templates/
│ ├── index.html
│ └── favorites.html
├── static/
│ ├── css/style.css
│ └── js/script.js
├── data/
│ ├── movies_metadata.csv
│ ├── credits.csv
│ └── keywords.csv

## 📦 Setup Instructions

1. **Clone this repo**  
   ```bash
   git clone https://github.com/Yuvi11Khati11/movie_recommender.git
   cd movie_recommender
   
Create a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate  

Install dependencies
pip install -r requirements.txt

Add your TMDB API key to .env
TMDB_API_KEY=your_api_key_here

Open in browser
Visit http://127.0.0.1:5000 in your browser.
