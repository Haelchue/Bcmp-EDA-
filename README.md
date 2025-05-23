# Spotify 2023 - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an in-depth exploratory data analysis (EDA) on Spotify's 2023 dataset containing track information, audio features, and performance metrics. The analysis aims to uncover insights about music trends, artist performance, and what makes songs popular.

## 📊 Dataset Description
The dataset contains:
- 1000+ tracks from 2023 and historical hits
- Track metadata (name, artists, release date)
- Platform performance metrics (streams, playlist inclusions, chart positions)
- Audio features (BPM, key, danceability, energy, etc.)

## 🔍 Analysis Objectives

### 1. Top Songs & Artists Analysis
- Identify most streamed songs and most featured artists
- Analyze artist frequency and contributions
- Examine artist collaborations impact

### 2. Platform Popularity
- Compare presence across Spotify, Apple Music, Deezer, and Shazam
- Check correlations between platform presence and stream count

### 3. Temporal Trends
- Analyze release patterns by year, month, and day
- Identify seasonal patterns in hit songs
- Examine longevity of popular tracks

### 4. Audio Feature Analysis
- Study distributions of BPM, danceability, energy, valence, etc.
- Identify common audio traits of top-performing songs
- Compare features across different years/artists

### 5. Correlation Studies
- Examine relationships between streams and audio features
- Analyze playlist influence on song performance
- Investigate chart position impact on streams

### 6. Genre Clustering
- Cluster songs using audio features to identify natural groupings
- Compare characteristics of different clusters

## 🛠️ Technical Implementation
- Python with Pandas for data manipulation
- Matplotlib and Seaborn for visualizations
- Scikit-learn for clustering analysis
- Jupyter Notebook for interactive analysis

## 📂 File Structure
```
spotify-eda/
├── data/
│   └── spotify-2023.csv          # Raw dataset
├── notebooks/
│   └── Spotify_EDA.ipynb         # Main analysis notebook
├── README.md                     # This file
└── requirements.txt              # Python dependencies
```

## 💡 Key Insights
[Will be populated after analysis]
1. Top 5 most streamed songs are...
2. The most common BPM range is...
3. Playlist inclusion correlates with streams by...

## 🚀 How to Run
1. Clone repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook

## 📈 Future Work
- Incorporate additional years of data
- Build predictive models for song success
- Create interactive dashboards

## 📜 License
This project is licensed under the MIT License. Dataset is for educational purposes only.
