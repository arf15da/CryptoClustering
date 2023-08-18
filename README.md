# CryptoClustering

Purpose: use unsupervised learning to predict if cryptocurrenices are affected by 24 hours or 7 days price changes.

1. Scale the data with the original dataframe
2. Find the best k value using the scaled dataframe
3. Cluster Cryptocurrencies with K-means using scaled dataframe with K-means segment
4. Optimize the cluster with Princial Component Analysis(PCA) using original dataframe
5. Find the best k value using the PCA data
6. Cluster Cryptocurrencies with K-means using scaled dataframe with PCA segment
7. Compare K-means and PCA plots
