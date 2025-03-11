# Movie Recommendation System 🎬

A **K-Nearest Neighbors (KNN) based Movie Recommendation System** built using Python and Streamlit. This project recommends movies based on user-selected genres or movie titles using IMDb movie data.

## 📌 Features
- **Movie-Based Recommendations**: Suggests similar movies based on a selected movie.
- **Genre-Based Recommendations**: Suggests movies based on selected genres and IMDb ratings.
- **Movie Posters & Details**: Fetches movie posters, director, cast, and storyline from IMDb.
- **Interactive UI**: Built using Streamlit for an easy and interactive experience.

## 🛠️ Requirements
Ensure you have Python installed along with the required dependencies:
```bash
pip install streamlit numpy beautifulsoup4 requests pillow
```
1.streamlit
2.numpy
3.Pillow
4.pandas
5.requests
6.beautifulsoup4
7.urllib3

## 🚀 Usage
1. Run the app:
   ```bash
   streamlit run App.py
   ```
2. Select either **Movie-Based** or **Genre-Based** recommendation.
3. Get recommendations along with IMDb details and posters.

## 🔍 How It Works
- Uses **K-Nearest Neighbors (KNN)** algorithm for recommendations.
- Fetches **movie details & posters** from IMDb using web scraping.
- Data is sourced from the **IMDb 5000 Movie Dataset**.



