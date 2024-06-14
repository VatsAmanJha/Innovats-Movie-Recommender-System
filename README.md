# Movie Recommendation System

This project implements a movie recommendation system using cosine similarity and a Streamlit web application.

## Table of Contents

- [Introduction](#introduction)
- [Project Files](#project-files)
- [Project Overview](#project-overview)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Introduction

This project aims to create a movie recommendation system using cosine similarity to recommend similar movies based on user input. The recommendation system is implemented in a Streamlit web application, providing an interactive way for users to discover new movies.

## Project Files

1. `movie_recommender_system.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, model training, and recommendation functions.
2. `similarity.pkl`: Pickle file containing the cosine similarity matrix between movies.
3. `movie_dict.pkl`: Pickle file containing a dictionary of movie data.
4. `app.py`: Streamlit web application for interactive movie recommendations.

## Project Overview

The project includes the following steps:

1. **Data Preprocessing**: The data is loaded and preprocessed to create a clean dataset for building the recommendation system.
2. **Model Training**: Cosine similarity is calculated between movies based on their features.
3. **Recommendation Functions**: Functions are created to recommend similar movies based on user input.
4. **Streamlit Web Application**: The `app.py` file implements a Streamlit app where users can select a movie and get recommendations.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/VatsAmanJha/Innovats-Movie-Recommender-System.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-recommendation
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
5. Open your browser and go to `http://localhost:8501` to access the app.

## Dependencies

- Python 3
- pandas
- scikit-learn
- NLTK (Natural Language Toolkit)
- ast (Abstract Syntax Trees)
- Streamlit
- requests

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.