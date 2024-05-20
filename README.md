# Movie Recommendation System

## What It Does
The program recommends movies from the [MovieLens 25M Dataset] (https://www.kaggle.com/datasets/garymk/movielens-25m-dataset) based on a movie you liked. 
For example, if you entered the movie "Fight Club" in the search box, you would get recommended movies that were highly rated by other people who also enjoyed "Fight Club".

## How It Works
When you enter the name of a movie, the recommendation system first searches for all users who gave that same movie a rating of 5/5. We call these users "similar users".
Then, we find all the other movies that these similar users also gave a rating of 5/5. From this pool of movies, only deal with the movies liked by over 10% of these similar users.
