# Spotify-Song-Recommendation
A Spotify-style music recommendation system built using audio feature analysis, clustering, and cosine similarity to recommend songs based on user listening patterns.
# 🎵 Spotify Song Analysis & Recommendation System

A **Python-based project** that analyzes Spotify music data, explores song patterns using clustering and PCA, and provides **song recommendations** based on audio features using cosine similarity.  

This project is perfect for music enthusiasts, data scientists, or anyone interested in exploring music trends and building a simple recommendation engine.  

---

## 🔹 Features

- **Exploratory Data Analysis (EDA):**  
  - Visualize track popularity, playlist genres, and audio features.  
  - Understand relationships between features with correlation heatmaps.  

- **Clustering Songs:**  
  - Group songs using **K-Means clustering** based on audio features like danceability, energy, valence, and more.  
  - Visualize clusters by playlist genres and top playlists.  

- **Dimensionality Reduction:**  
  - Use **PCA** (Principal Component Analysis) to reduce audio features to 2D for cluster visualization.  

- **Song Recommendation System:**  
  - Recommend similar songs using **cosine similarity** on audio features.  
  - Interactive **IPython widgets** allow selecting a song and displaying recommendations.  

---

## 🔹 Dataset

- **Source:** `spotify dataset.csv`  
- **Contains:**  
  - Song information: `track_name`, `track_artist`, `track_album_release_date`  
  - Playlist info: `playlist_name`, `playlist_genre`  
  - Audio features: `danceability`, `energy`, `loudness`, `speechiness`, `acousticness`, `instrumentalness`, `liveness`, `valence`, `tempo`, `duration_ms`  
  - Popularity: `track_popularity`  

---

## 🔹 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/spotify-recommendation.git
cd spotify-recommendation
```
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets
   ```
Note: If using Jupyter Notebook, enable widgets with:
   ```bash
   jupyter nbextension enable --py widgetsnbextension
   ```
4. Run the notebook:
Open Spotify_Analysis_Recommendation.ipynb in Jupyter Notebook or JupyterLab and run all cells.

🔹 Usage

1. Explore the data visualizations for insights on songs, playlists, and audio features.
2. Examine clusters and identify trends in playlist genres and top playlists.
3. Use the interactive song recommendation widget to find similar songs:
4. Select a song from the dropdown.
5. Click Get Recommendations to view 5 similar songs.

🔹 Technologies Used

1. Python 3
2. Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, ipywidgets
3. Machine Learning: K-Means clustering, PCA, Cosine Similarity

🔹 Contributing

1. Contributions are welcome! You can:
2. Improve recommendation algorithm
3. Add new visualizations
4. Optimize performance for large datasets
5. Please open an issue or submit a pull request.

🔹 License

This project is licensed under the MIT License.
