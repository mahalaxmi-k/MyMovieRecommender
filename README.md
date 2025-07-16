# Project: Movie Recommender System Using Machine Learning!

<img src="demo/6.jpeg" alt="workflow" width="70%">

# Movie Recommendation System Using Machine Learning

Created by: Mahalaxmi K

This project recommends movies based on a selected movie. It uses content-based filtering, cosine similarity, and TMDB API to show posters.

## Features
- Select a movie from a dropdown
- Get top 5 similar movie suggestions
- See posters fetched from TMDB

## How to Run This Project

1. Clone the repository:
   https://github.com/mahalaxmi-k/MyMovieRecommender

2. Install required packages:
   pip install -r requirements.txt

3. Run the app:
   streamlit run app.py

Make sure you have a stable internet connection to fetch movie posters.

## Credits
Built using Python, Scikit-Learn, Pandas, Streamlit
Movie data from TMDB


# About this project:

This is a streamlit web application that can recommend various kinds of similar movies based on an user interest.
here is a demo,

* [Click here to run it live on server](https://movie-recommender-mahalaxmi.streamlit.app/)


# Demo:

<img src="demo/1.png" alt="workflow" width="70%">

<img src="demo/2.png" alt="workflow" width="70%">

<img src="demo/3.png" alt="workflow" width="70%">


# Dataset has been used:

* [Dataset link](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

# Concept used to build the model.pkl file : cosine_similarity

1 . Cosine Similarity is a metric that allows you to measure the similarity of the documents.

2 . In order to demonstrate cosine similarity function we need vectors. Here vectors are numpy array.

3 . Finally, Once we have vectors, We can call cosine_similarity() by passing both vectors. It will calculate the cosine similarity between these two.

4 . It will be a value between [0,1]. If it is 0 then both vectors are complete different. But in the place of that if it is 1, It will be completely similar.

5 . For more details , check URL : https://www.learndatasci.com/glossary/cosine-similarity/
