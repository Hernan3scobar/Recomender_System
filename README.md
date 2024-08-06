# Movie Recommender System using Neural Collaborative Filtering

This project implements a movie recommender system using Neural Collaborative Filtering (NCF) with PyTorch. The model predicts user ratings for movies based on their interactions and the features of both users and movies.

Features
Neural Collaborative Filtering (NCF): Utilizes deep learning to model complex user-item interactions.
Data: The dataset was sourced from GroupLens.
Components
Model Architecture:

Embedding Layers: Map users and items to latent vectors.
Concatenation: Combine user and item embeddings.
Neural Network: A Multi-Layer Perceptron (MLP) processes the concatenated vectors to predict ratings.
Training:

Optimizer: Adam
Loss Function: Mean Squared Error (MSE)
Evaluation Metrics:

Precision and Recall: Computed for the top-k recommendations.A&H
