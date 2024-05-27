# CryptoClustering

Module 11 Challenge 

This project uses Python and machine learning techniques to cluster cryptocurrencies based on their price change data. The code performs the following tasks:

## Data Preprocessing

1. Loads cryptocurrency market data from a CSV file into a Pandas DataFrame.
2. Scales the data using the `StandardScaler` from scikit-learn.

## Finding the Best Number of Clusters

1. Computes the inertia for different values of `k` (number of clusters) using the K-Means algorithm.
2. Plots the Elbow curve to determine the optimal value of `k` based on the original scaled data.
3. Repeats the process using Principal Component Analysis (PCA) data to find the best `k` value.

## Clustering Cryptocurrencies

1. Clusters the cryptocurrencies using the K-Means algorithm with the optimal `k` value found in the previous step.
2. Creates scatter plots to visualize the clusters using both the original scaled data and the PCA data.

## Principal Component Analysis

1. Performs PCA to reduce the dimensionality of the data to three principal components.
2. Calculates the explained variance ratio for each principal component.
3. Analyzes the weights of each feature on the principal components to determine their influence.

## Usage

1. Ensure you have the required Python libraries installed: `pandas`, `scikit-learn`, and `matplotlib`.
2. Place the `crypto_market_data.csv` file in the `Resources` directory.
3. Run the Python script to execute the code.

