# 🎧 Spotify Song Clustering & Recommendation System

This project performs clustering of songs from a Spotify dataset based on their audio features like energy, danceability, BPM, popularity, etc., using **K-Means Clustering**. It enables a basic **content-based music recommendation system** where similar songs are recommended based on cluster similarity.

---

## 🧠 Project Highlights

- 📊 Exploratory Data Analysis and Visualization of Spotify Songs
- ⚙️ Feature Engineering with PowerTransformer & StandardScaler
- 📉 Dimensionality Reduction using PCA
- 🎯 Clustering using K-Means (Elbow method used for `k`)
- 🎨 Visualization of clusters using 2D PCA scatter plots
- 🧭 Custom Recommendation Function to suggest similar songs
- 🎵 Analysis of Top Genres and Song Popularity per Cluster

---

## 📂 Dataset

- 📁 `Spotify-2000.csv` (within ZIP archive)
- Contains metadata of 2,000 popular songs: Title, Artist, Genre, BPM, Danceability, etc.

---

## 🔍 Features Used for Clustering

- Energy  
- Danceability  
- Valence  
- Popularity  
- BPM  
- Speechiness  
- Liveness  
- Length (Duration)

---

## 📁 Project Structure

```bash
├── fiinal_clustering_model.py    # Main Python script (Colab-exported)
├── archive (3).zip               # ZIP file containing Spotify-2000.csv
├── README.md                     # Project documentation

'''
run in google colab
