# Movie Recommendation System (moviexrecom)

This project is a **content-based Movie Recommendation System** built using Python and **Streamlit** for the frontend web interface. 

## Features
- **Core Functionality:** When a user selects a movie from a dropdown list, the system recommends the top 5 most similar movies.
- **Behind the Scenes:** 
  - The recommendations are generated using precomputed machine learning data (cosine similarity scores), which is loaded via pickle files (`similarity.pkl` and `movies_dict.pkl`). 
  - There is a Jupyter Notebook (`movie.ipynb`) in the repository, which was used to clean the dataset, train the model, compute the similarities, and export the `.pkl` files.
- **API Integration:** The application connects to the **TMDB (The Movie Database) API** to fetch and display the official movie posters for the 5 recommended movies dynamically.

## Technologies Used
- **Python**
- **Streamlit** (for the UI)
- **Pandas** (for data manipulation)
- **Requests** (for API calls)
- **Pickle** (for loading the precomputed similarity matrix)
