# 🎬 Movie Recommendation System

A personalized movie recommendation web application that suggests the best titles based on selected movies and languages, using content-based filtering with IMDb ratings, genres, and user-preferred languages. Built with Python, Flask, and HTML/CSS, and powered by machine learning techniques.

---

## 🚀 Features

- 🎞️ Recommend similar movies based on selected titles
- 🌐 Filter recommendations by preferred languages
- ⭐ Sort by IMDb ratings and viewer popularity
- 🔍 Autocomplete feature for movie titles and languages
- 📊 Visualizations for genre and language distributions
- 🔗 Direct links to watch on Netflix
- 💡 Lightweight, fast, and beginner-friendly

---

## 📂 Project Structure

├── app.py # Main Flask backend
├── templates/
│ ├── index.html # Front page with input fields
│ ├── recommendations.html # Displays top recommended movies
│ └── movie_detail.html # Detailed view with Netflix link
├── static/
│ └── style.css # Custom styles
├── dataset/
│ └── netflix_titles.csv # Dataset with movie info
├── recommendation_model.py # Similarity calculation logic
└── README.md # Project documentation

---



## 🧠 Tech Stack

- **Frontend**: HTML5, CSS3 (Bootstrap), JavaScript (Autocomplete)
- **Backend**: Python (Flask)
- **ML Concepts**: Cosine Similarity, Content-Based Filtering
- **Data Visualization**: Matplotlib, Seaborn
- **Dataset**: Netflix Titles Dataset (includes title, genre, cast, language, rating, description, etc.)

---

## 📊 Visual Insights

- 🔢 Top-rated movies by language
- 📈 Genre and language distribution plots
- 🔎 Viewers' choice vs IMDb rating analysis

---

## 🧪 How It Works

1. **User Input**: Select up to 4 movies and 4 preferred languages.
2. **Filtering**: The system filters dataset entries by language.
3. **Similarity Matching**: Calculates cosine similarity between selected movie vectors and dataset entries.
4. **Ranking**: Results are sorted by IMDb rating and viewer preferences.
5. **Display**: Top 10 personalized recommendations are shown, with links and details.
