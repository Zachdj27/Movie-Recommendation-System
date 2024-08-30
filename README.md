# Movie Recommendation System
[!][Example](https://github.com/Zachdj27/Movie-Recommendation-System/assets/151213591/77f90079-1ec5-4709-8ff8-b06c9bb60522)

## What It Does
The program recommends movies from the [MovieLens 25M Dataset] (https://www.kaggle.com/datasets/garymk/movielens-25m-dataset) based on a movie you liked. 
For example, if you entered the movie "Fight Club" in the search box, you would get recommended movies that were highly rated by other people who also enjoyed "Fight Club".

## How It Works
1. When you enter the name of a movie, the recommendation system first searches for all users who gave that same movie a rating of 5/5. We call these users "similar users".
2. The search engine finds all the other movies that these similar users also gave a rating of 5/5.
3. From these movies, we look for those who were liked by over 10% of these similar users.
4. We give a score to movies by how uncommonly they were liked by all users on the platform so we recommend more "niche" movies and not only commonly liked ones.
5. The top 5 most "niche" movies are then recommended.

## Tech Stack
- Tools/platforms: Jupyter Notebook
- Languages: Python
- Python Modules: Numpy, Pandas, Sklearn Ipywidgets, IPython



