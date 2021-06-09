# This project is based on various designs for recomender systems algorithms.

The data is based on rating.csv from the movielens dataset which can be found via this link [https://www.kaggle.com/grouplens/movielens-20m-dataset](https://www.kaggle.com/grouplens/movielens-20m-dataset)

In this project the data is contained in a seperate folder called data in the previous directory.

## Preprocessing

The first step is to run preprocessing.ipynb which will preprocess the data for the models for each of the models.
the number of movies and users can be varied to get different results when running the each of the algorithms

## The algorithms

### User-User collabarative filtering

The first algorithm for user user collabarative filtering.

The hyperparameter for the model are:
- number of shared weights
- number of common movies required to be considered for a shared weight

### Item Item collabarative filtering

The second algorithm is for item-item collaberative filtering which is only different to user user collabarative filtering in that the item similaritys are used to make predictions.

The hyperparameter for the model are:
- number of shared weights
- number of common movies required to be considered for a shared weight

### Matrix Factorisation

Matrix Factorisation is a alternative type of collerative filtering algorithm which is based on alternating least squares.

The hyperparemters of the model are:
- The regulisation penalty
- the number of epochs
- The number of latent features
