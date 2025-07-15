#  Movie Recommendation System

A simple yet effective **content-based movie recommendation system** built using Python and Scikit-learn. This project analyzes movie metadata (like genre, cast, director, and number of screens) and recommends similar movies based on the selected title.


# Project Overview

The system takes a movie title as input and returns a list of movies similar in content. It uses **text vectorization (CountVectorizer)** and **cosine similarity** to find the most similar movies from the dataset.

The main components include:

- Dataset loading and exploration
- Feature engineering (combining metadata columns)
- Text vectorization using `CountVectorizer`
- Similarity matrix computation
- Movie recommendation function


# Features

- ✅ Content-based filtering using metadata
- ✅ Cosine similarity-based scoring
- ✅ Clean and simple recommendation function
- ✅ Easily customizable for new features or larger datasets
