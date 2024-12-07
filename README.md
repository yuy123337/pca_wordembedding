# PCA & Word Embeddings

This repository contains code for analyzing restaurant reviews using Principal Component Analysis (PCA) to explore dimensionality reduction in high-dimensional text data. This repository contains the Jupyter notebook where PCA is applied on a dataset of restaurant reviews, specifically analyzing reviews for Chinese and Japanese cuisines. The aim of this trial is to identify the most significant components that explain the variance in the dataset.
# Data
http://127.0.0.1:8888/lab/tree/metro_restaurants/balanced_reviews.parquet

PCA is used to reduce the dimensionality of the review data. The notebook demonstrates how to apply PCA to the vectorized text data (using CountVectorizer or TF-IDF), and visualize the variance explained by the principal components. The goal is to identify the underlying patterns in the reviews, such as common themes or sentiments across the dataset.
