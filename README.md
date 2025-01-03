## Movie-Recommendation-System
Content based recommendation System project about movies

### The Project files : [Files](https://drive.google.com/drive/folders/110h3eQdOL97vfZwH_pJau3i6Zwo7e7bL?usp=sharing)

![Screenshot 2024-12-31 185854](https://github.com/user-attachments/assets/e7fe8131-83fd-481c-80d2-70d7383f26e4)




#####  ![Screenshot 2024-12-31 181253](https://github.com/user-attachments/assets/bd12da14-bbff-46e9-bb2b-e4db06ca789f)


### Overview

This project is a simple yet effective Movie Recommendation System built using cosine similarity to recommend movies based on user preferences or selected movies. The system is wrapped in an interactive and user-friendly web application built with Streamlit, allowing users to explore and receive recommendations in real-time.

### Features

1. Recommends similar movies based on a selected movie using cosine similarity.

2. Interactive web app for users to browse and search movies.

3. Lightweight and easy to deploy.


### Dataset:  [LINK](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) 

 The system uses a dataset containing movie details like titles, genres, and descriptions (e.g., from Kaggle or IMDb datasets).

### Preprocessing:  

 1. Text data is vectorized using techniques like TF-IDF.

 2. Cosine similarity is calculated between movie vectors to find the most similar movies.

 Streamlit Web App:

 A user selects a movie or searches for it using the web app. The app processes the input and displays a list of similar movies.

### Tech Stack---

Python: Core language for data processing and machine learning.

### Libraries:

Pandas: For data manipulation.

Scikit-learn: For vectorization and cosine similarity computation.

Streamlit: For creating the web interface.


##### Run the Web App: Start the Streamlit web app:
                streamlit run app.py
                
##### Access the App: Open your browser and navigate to 
                http://localhost:8501.
