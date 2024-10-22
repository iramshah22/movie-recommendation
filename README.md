This repository contains a Movie Recommendation System built using Python and based on movie and rating data from a CSV file. The system utilizes several libraries and algorithms to provide personalized movie recommendations.

# Features:
User-Based Collaborative Filtering: Recommends movies based on the preferences of users with similar tastes.
**Item-Based Collaborative Filtering: Suggests movies similar to the ones a user has rated highly.**
Content-Based Filtering: Recommends movies based on movie metadata such as genres, directors, and actors.
Top N Movies Recommendation: Provides top-rated movies based on average user ratings.

**Data Source**
The system uses a dataset that consists of:
Movies: Information such as movie titles, genres, and release year.
Ratings: User ratings for movies, ranging from 1 to 5 stars.

# Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
SciPy: Used for computing similarity measures.
scikit-learn: For implementing machine learning algorithms.
