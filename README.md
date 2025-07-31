
# 🎧 Spotify Song Recommender (AI-Based)

An Artificial Intelligence project that groups and recommends similar Spotify songs based on their audio properties using unsupervised learning (AI clustering) — and presents the results via an interactive Streamlit web interface.

---

## 📌 Project Objective

To build an **AI-powered music recommendation system** that:
- Clusters similar songs based on their audio features
- Visualizes relationships between song attributes
- Recommends songs that match the user's selected vibe
- Delivers an interactive and visually appealing experience

---

## 🧠 Technologies Used

- **Python**
- **Pandas / NumPy** – for data processing  
- **Matplotlib / Seaborn** – for visual analysis  
- **Scikit-learn** – for AI clustering (KMeans), scaling, and PCA  
- **Streamlit** – to build the interactive UI  

---

## 📊 Dataset

The dataset contains **32,000+ Spotify tracks** with:
- Metadata: `track_name`, `track_artist`, `playlist_genre`, etc.
- Audio features:  
  - `danceability`, `energy`, `loudness`, `tempo`  
  - `valence`, `instrumentalness`, `acousticness`, etc.

> **Source:** Public Spotify Audio Features Dataset

---

## 🔍 Key Features

- 🎼 Audio feature clustering using **AI (KMeans)**
- 📈 Correlation matrix to show feature relationships
- 🌀 PCA visualization to project song clusters in 2D
- 🤖 Intelligent song recommendations using similarity-based clustering
- 📦 Export recommendations to CSV
- 🎨 Modern dark-theme interface using Streamlit

---

## 🚀 How to Run

### 1. Extract the project ZIP file

Unzip the downloaded folder: 

### 3. Launch the Streamlit App

```bash
streamlit run app.py
```

> This will open the app in your browser (usually at `http://localhost:8501`)


---

## 🧠 AI Concepts Used

- **Unsupervised AI Clustering**
- **Feature Scaling**
- **Dimensionality Reduction (PCA)**
- **Similarity-based Recommendation Logic**

---

## ✅ Future Improvements

- Add genre-specific filters  
- Improve similarity logic (cosine similarity or neural embeddings)  
- Deploy online with Streamlit Cloud  

---

## 👨‍💻 Author

**Akrit Kumar**  
B.Tech CSE (AI/ML) – Lovely Professional University  
[GitHub](https://github.com/Akrit099) 

---

## 📄 License

This project is for academic and learning purposes only.
