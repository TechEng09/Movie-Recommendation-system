# Movie Recommendation System

A system that recommends movies to users based on genre and similarity using machine learning techniques.

## Project Overview
This project provides personalized movie recommendations by analyzing user preferences and movie metadata. It uses a hybrid approach combining genre similarity and metadata features.

## Features
- Recommend movies based on selected movie or preferred genres  
- Handles multiple genres and multi-label movie datasets  
- Cleaned and preprocessed movie data for accurate recommendations  

## Technologies Used
- Python  
- Pandas, NumPy for data processing  
- Scikit-learn for similarity calculations and ML models  
- Jupyter Notebook for experimentation  

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/YourUsername/movie-recommender.git

2.Install dependencies:
pip install -r requirements.txt

3.Run the notebook or script to see movie recommendations
from recommender import recommend_movies
recommend_movies("Frankenstein")  # Example output: list of recommended movies
