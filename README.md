# AutoRec

This repository consist of MovieLens 100K dataset and Jupyter notebook with the implementation of AutoRec neural network.

This AutoRec implementation is an item-based collaborative filtering model using an autoencoder architecture. It learns a compressed representation for each item based on ratings provided by all users, allowing it to predict missing ratings for items based on similar patterns. The model processes each item vector (user ratings for that item) and reconstructs it, enabling the recommendation system to fill in unobserved ratings by leveraging learned relationships among items.