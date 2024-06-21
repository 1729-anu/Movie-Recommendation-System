# Movie Recommendation System

This is a movie recommendation system built using Python, Streamlit, and the TMDB API. The system uses a content-based filtering approach to recommend movies similar to the one selected by the user.

## Overview

The project consists of the following main components:

- **Data Collection**: The movie data is collected from the TMDB API, including movie titles, overviews, genres, and poster images.
- **Data Processing**: The collected data is processed to extract relevant features and create a movie-tag matrix.
- **Recommendation Algorithm**: The system uses cosine similarity to calculate the similarity between movies based on their tags.
- **User Interface**: The recommendation system is deployed using Streamlit, providing a simple user interface for users to interact with.

## Installation

To run the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git

2. Install the required packages:

    ```bash
    pip install -r requirements.txt

3. Run the Streamlit app:
   ```bash
   streamlit run app.py

Open your browser and navigate to [http://localhost:8501](http://localhost:8501) to view the app.

## Usage

1. Select a movie from the dropdown menu.
2. Click the "Show Recommendation" button to view recommended movies.
3. The recommended movies will be displayed with their titles and poster images.

## Future Improvements

- Implement user-based or collaborative filtering for more personalized recommendations.
- Enhance the UI with additional features and customization options.
- Add more data sources to improve the diversity and quality of recommendations.

