# Movie Recommender System using Streamlit

This project implements a movie recommendation system using content-based filtering. The system is integrated into a Streamlit web application, allowing users to select a movie and get recommendations for similar movies.

## Cloning the Project

To get started, clone this project to your local machine using the following command:

* git clone https://github.com/Rhythm1821/Recommender-System.git

## Dependencies

* Download the dataset:
dataset link -> https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv# 

* Make sure you have the following dependencies installed:

streamlit
pandas

* You can install them using pip:

pip install streamlit pandas


## Running the Web Application

* Navigate to the project directory in the terminal.
* Run the Streamlit app using the following command:

streamlit run app.py

The web application will start, and you will see a title "Movie Recommender System" and a dropdown to select a movie.
Choose a movie from the dropdown, and click the "Recommend" button to see the top 5 recommended movies based on the selected movie's similarity.
