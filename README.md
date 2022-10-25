# Anime Recommendation
This is a anime recommendation system based on content-based prediction and Collaborative Filtering model.

## Methodology
Content-based: Linear Regression, Random Forest, Decision tree, Gradient boosted tree, KNN

Personalized recommendation: Collaborative Filtering

Modules: Tensorflow, Keras, Sklearn, Pyspark

## Introduction of Project

In this project, we developed an anime recommendation system. Our data is collected from [Anime Recommendation Database 2020](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020). Our main goal is to make anime recommendation for users, and we provide three choices. The first is to make content-based prediction, predicting general score of each anime based on models such as Linear Regression, Random Forest, Decision tree, and Gradient boosted tree. The Linear Regression model results in best accuracy with 83% according to our test. The second is to find similar animes to a specific anime (provided by user), and we can achieve this with KNN model. The last choice is to make personalized recommendation based on Collaborative Filtering, by looking for users who share the same rating patterns with the target user and make prediction based on preference of similar users. In this part, we used neural network of deep learning method to train the model and calculated the dot-product between user embedding and anime embedding to get the likelihood that a user interacts with an anime.
