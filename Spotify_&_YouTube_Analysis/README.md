# 🎵 Spotify & YouTube Music Trends Analysis

This project explores **music trends across two major platforms — Spotify and YouTube**.  
The dataset provides detailed insights into song performance, including **stream counts, YouTube views, likes, comments, and audio features** such as danceability, energy, loudness, and tempo.

We analyze this data using **Python** to uncover patterns in artist popularity, platform-specific performance, and musical characteristics.

---

## 📂 Dataset Overview

- **Source:** [Kaggle - Spotify YouTube Dataset: Music Trends Across Platforms](https://www.kaggle.com/)  
- **Format:** CSV
- **Size:** Contains multiple tracks across various artists and platforms
- **Columns:**
  - **Track:** Song name  
  - **Artist:** Performer or band  
  - **Stream:** Spotify streams  
  - **Youtube Views:** Total YouTube views  
  - **Danceability:** Dance suitability score (0–1)  
  - **Energy:** Song intensity score (0–1)  
  - **Key:** Musical key (0–11)  
  - **Loudness:** Loudness in dB  
  - **Speechiness:** Spoken word measure (0–1)  
  - **Acousticness:** Acoustic sound measure (0–1)  
  - **Instrumentalness:** Probability of no vocals (0–1)  
  - **Liveness:** Live performance probability (0–1)  
  - **Valence:** Positivity score (0–1)  
  - **Tempo:** BPM (beats per minute)  
  - **Duration_ms:** Track length in milliseconds  
  - **Year:** Release year  

---

## 📝 Analysis Questions

1. **Top 10 Artists** with the highest YouTube views  
2. **Top 10 Tracks** with the highest Spotify streams  
3. Most common **Album Types** on Spotify and their track counts  
4. Comparison of **average views, likes, and comments** between album types  
5. **Top 5 YouTube Channels** based on total views  
6. **Top track** based on YouTube views  
7. **Top 7 tracks** with the highest like-to-view ratio on YouTube  
8. **Top albums** containing the tracks with maximum danceability  
9. Correlation between **views, likes, comments, and streams**  

---

## 🛠 Tools & Libraries

- **Python**
- **Pandas** — Data cleaning & analysis
- **NumPy** — Numerical computations
- **Matplotlib / Seaborn** — Visualization
- **Jupyter Notebook** — Interactive analysis

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sankajithdjinasena/DataAnalysisProjects.git
   ```
2. Navigate to the project folder:
   ```bash
   cd DataAnalysisProjects/SpotifyYouTubeAnalysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Spotify_YouTube_Analysis.ipynb
   ```

---

## 📌 Sample Insights

- Some artists dominate **YouTube views** but not necessarily **Spotify streams**.
- Danceability and energy scores can reveal trends in **popular genres**.
- Strong correlation observed between **YouTube views and likes**.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---
💡 *Music trends change fast — data helps us understand why.*
