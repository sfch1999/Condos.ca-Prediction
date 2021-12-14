# Condos.ca-Prediction

This github was created for a STA2453 class project at the University of Toronto.

Our goal was to develop a model to predict price per sqm of a condo in Toronto, based on data scrapped from condos.ca

To run this project, use the following files in this order:
- "webscrapping.ipynb": this file uses Scrapy to scrape condos.ca
- "__________.ipynb": this file processes the scrapped data (Note it has two outputs based on the encoding for categorical variables: 1. numerical encoding and 2. one-hot-encoding)
- "LR_SVR.ipynb": This file contains the linear regression and support vector regression models
- "neural_network.ipynb": This file contains the neural network model
- "decision_tree_random_forest.ipynb": This file contains the decision tree and random forest regression models
