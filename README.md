Movie Recommendation System


 Project Overview


     This project is a content-based Movie Recommendation System that recommends movies similar to a given movie based on textual features such as genres, overview, keywords, cast, and director.

     The system uses Natural Language Processing(NLP) and Cosine Similarity to find movies that are most similar to the user's  selected movie.


 Problem Statement


     With thousands of movies available, users often find it difficult to choose what to watch next.

     This project aims to solve that problem by recommending movies based on content similarity.


 Solution Approach


     The recommendation system works by:

           1. Processing  movie metadata(genres, cast, crew etc).

           2. Converting text data into numerical vectors.

           3. Measuring similarly between movies.

           4. Recommending the most similar movies.


 Dataset


     Source : Kaggle

     Dataset Name : TMDB 5000 Movie Dataset

     File Used : 
            
              movies.csv
              credits.csv


 Technologies Used


     Python

     Pandas
     
     NumPy

     Scikit-learn

     NLTK

     Jupyter Notebook


 Project Workflow


     1. Data Loading

     2. Data Cleaning & Merging

     3. Text Preprocessing

     4. Feature Engineering

     5. Vectorization using CountVectorizer

     6. Similarity Calculation using Cosine Similarity

     7. Movie Recommendation Function


 Model and Technique


     Vectorization : CountVectorizer

     Similarity Metric : Cosine Similarity

     Type : Content-Based Recommendation System


 Sample Output


     If the user searches for :

              The Godfather

     The system recommends:

              Desert Dancer
              Step Up
              Take the Lead
              Footloose
              Step Up 2: The Streets     


 Future Enhancements


     Add movie posters using TMDB API

     Build a web app using Streamlit

     Add user-based filtering


 Conclusion                            


     This project demonstrates how NLP and Machine Learning concepts can be used to build real-world recommendation systems similar to Netflix and Amazon Prime.