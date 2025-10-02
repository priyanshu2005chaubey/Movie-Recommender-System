Movie Recommender System — An end-to-end content-based recommendation system that suggests similar movies based on movie metadata, leveraging natural language processing and interactive web deployment.

The project consists of two stages:

 1. Data Preprocessing & Cleaning in Google Colab — merging datasets, cleaning missing values, removing duplicates, extracting and processing movie metadata (genres,      keywords, cast, crew), applying text stemming, and creating a feature-rich tag system for each movie. This stage also includes computing a similarity matrix using     CountVectorizer and cosine similarity.

 2. Web Application Deployment in Streamlit — building an interactive UI where users can select a movie and instantly receive the top 5 similar movie recommendations      along with their posters fetched in real-time from the TMDb API.

Key Highlights:

 Comprehensive preprocessing pipeline to convert raw movie datasets into usable recommendation features.

 Intelligent feature engineering with genres, keywords, cast, crew, and overview combined into tags for better similarity computation.

 Content-based filtering using cosine similarity on vectorized tags.

 Real-time interactive recommendations through a sleek Streamlit UI.

 Poster fetching integration via TMDb API for a visually appealing interface.

This project demonstrates data preprocessing, feature engineering, NLP techniques, similarity computations, and interactive web deployment — making it a strong showcase of skills in data science, machine learning, and application development.
