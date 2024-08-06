# Movie Recommender System using Neural Collaborative Filtering

This project implements a movie recommender system using Neural Collaborative Filtering (NCF) with PyTorch, predicting user ratings for movies based on their interactions and the features of both users and movies. 

NCF utilizes deep learning to model complex user-item interactions, with data sourced from GroupLens. The model architecture includes embedding layers to map users and items to latent vectors, concatenation to combine user and item embeddings, and a Multi-Layer Perceptron (MLP) to process the concatenated vectors to predict ratings. The training process uses the Adam optimizer and Mean Squared Error (MSE) as the loss function. For evaluation, precision and recall are computed for the top-k recommendations.
