# Movie Recommender System

This is a movie recommender system built using Streamlit and The Movie Database (TMDB) API. The system recommends movies based on cosine similarity, analyzing user-selected movie titles to suggest similar movies.

## Data preprocessing and creating similarity array 
review the notebook on kaggle 
    ```bash 
    https://www.kaggle.com/code/abdulrhmaneldeeb/movies-5000

## Features
- **Personalized Movie Recommendations**: Suggests movies similar to the one selected by the user.
- **Interactive UI**: Built with Streamlit for an easy-to-use and engaging user experience.
- **Real-time Poster Fetching**: Retrieves movie posters from TMDB to visually enhance recommendations.

## How It Works
1. **Data Loading**: Loads movie data and similarity scores from precomputed pickle files.
2. **Cosine Similarity**: Uses cosine similarity to find and rank movies similar to the user-selected movie.
3. **API Integration**: Fetches movie posters using TMDB API to provide a visual representation of recommendations.

## Setup Instructions

### Prerequisites
- Python 3
- Streamlit
- Requests
- Pickle

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/AdbulrhmanEldeeb/movie_recommender_system
   cd movie-recommender-system

2. **Install required packages:**
   ```bash
   pip install -r requirements.txt


4. **Ensure you have the necessary data files:**
review this notebook on kaggle
    ```bash
    https://www.kaggle.com/code/abdulrhmaneldeeb/movies-5000
and download outputs 
- movie_list.pkl
- similarity.pkl

4. **Run the Streamlit application:**
   ```bash
   streamlit run app.py


## TMDB API Endpoints Used
- **Get Movie Details:**
  
- **Endpoint:**
   ```bash
   'https://api.themoviedb.org/3/movie/{movie_id}?api_key={add_your_api_key}&language=en-US'
- **Description:** Fetches detailed information about a specific movie.




