# 🎬Movie Recommendation System 📽

The Movie Recommendation System is a web application that suggests movie recommendations based on user-selected movies. It uses collaborative filtering techniques and the similarity between movies to generate personalized movie suggestions.

##  Features 
  - Movie Selection: Users can choose a movie from a dropdown menu or type its name.
  - Movie Recommendation: The system provides recommendations for similar movies based on the selected movie.
  - Movie Posters: The app displays the movie titles along with their corresponding posters.
  - Interactive Interface: The user interface is designed to be user-friendly and interactive.
  - Data Fetching: The app fetches movie data and posters from the TMDB API.
  - Machine Learning: Collaborative filtering and similarity measures are used to determine movie recommendations.
  - Caching: Movie data and similarity measures are cached using pickle to improve performance

## Workflow

1) The user selects a movie from the dropdown menu or types the movie's name.
2) Upon clicking the "Show Recommendation" button, the app retrieves the selected movie's index from the movie list.
3) The app calculates the similarity between the selected movie and all other movies in the dataset using precomputed similarity measures.
4) The movies are ranked based on their similarity to the selected movie.
5) The top five recommended movies, along with their posters, are displayed in a responsive layout.
6) Users can explore the recommended movies and find new movies to watch.

## Technologies Used
- Python: The project is implemented using Python programming language.
- Streamlit: Streamlit library is used for building the web application.
- Pickle: Pickle is used to cache and load movie data and similarity measures.
- Requests: Requests library is used to fetch movie data from the TMDB API.

## Website OverView:-
![ezgif com-video-to-gif (1)](https://github.com/dhrupad17/Movie-Recommendation-System/assets/91726340/92ff88ad-89d0-4b99-97dc-f622522ff73f)
