# 🎬 Movie Recommendation System

An AI-powered Movie Recommendation System built using **Python, TF-IDF, FastAPI, Streamlit, and TMDB API**. The application provides intelligent movie recommendations along with posters, movie details, and genre-based suggestions.

---

## 🚀 Features

- 🔍 Search movies with autocomplete
- 🎬 Movie details with posters
- 🤖 TF-IDF based movie recommendations
- 🎭 Genre-based recommendations
- ⚡ FastAPI REST API backend
- 🎨 Interactive Streamlit frontend
- 🌐 TMDB API integration
- 📱 Clean and responsive UI

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- FastAPI
- Streamlit
- TMDB API
- Pickle
- Requests

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│
├── app.py                 # Streamlit Frontend
├── main.py                # FastAPI Backend
├── df.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Virtual Environment

Windows

```bash
.venv\Scripts\activate
```

Linux / Mac

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variable

Create a `.env` file and add your TMDB API key.

```env
TMDB_API_KEY=YOUR_API_KEY
```

---

## ▶️ Run FastAPI

```bash
uvicorn main:app --reload
```

API Documentation

```
http://127.0.0.1:8000/docs
```

---

## ▶️ Run Streamlit

```bash
streamlit run app.py
```

---

## 🎯 Future Improvements

- Content-Based Recommendation using BERT
- Hybrid Recommendation System
- User Authentication
- Favorites & Watchlist
- Docker Deployment
- Cloud Deployment

---

## 👨‍💻 Developed By

**Dharmesh Sharma**

AI & Machine Learning Enthusiast

---

## ⭐ If you like this project, don't forget to star the repository!
