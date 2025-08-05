# 🎧 Spotify Track Dataset – Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis on a dataset of over 114,000 Spotify tracks, using Python and visualization libraries such as seaborn and matplotlib.

The goal is to explore musical attributes like popularity, danceability, energy, valence, and more — and understand patterns or trends in the data.

---

## 📂 Dataset Info

* 📦 Source: [Spotify Tracks Dataset by Maharshi Pandya (Kaggle)](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)
* 🔢 Size: 114,000 tracks | 21 features
* 🎵 Features include:

  * `popularity`, `duration_ms`, `danceability`, `energy`, `loudness`, `valence`, `tempo`, `track_genre`, `artists`, etc.

---

## 🔍 What This Project Covers

### ✅ Data Cleaning

* Checked for missing values and duplicates
* Removed irrelevant columns (e.g. index column)
* Converted duration from milliseconds to minutes

### 📊 Visualizations

* Top 10 genres by track count
* Top 10 most frequent artists
* Popularity distribution
* Duration distribution
* Correlation heatmap of audio features
* Scatter plot: Danceability vs Energy

### 💡 Key Insights

* Most tracks have low popularity, with a sharp peak at 0
* Popular artists include The Beatles, George Jones, Stevie Wonder, etc.
* Danceability and valence show positive correlation — happier tracks are more danceable
* Loudness strongly correlates with energy
* Popularity is not strongly correlated with any audio feature — suggesting external factors affect popularity

---

## 📈 Tools Used

* Python 
* pandas
* matplotlib
* seaborn
* Jupyter Notebook (Google Colab)

---
## 👤 Author
* Abhidan Ghale 
* This project is part of my portfolio for learning and showcasing EDA skills.
