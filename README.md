## Crypto Clustering

## Overview
We are attempting to group different crypto currencies to each other based off of certain "similarities" each one has relative to each other on certain features (Total Coins Mined, Total Coin Supply, Algorithm, etc.)

The dataset is first preprocessed to keep only traded cypto currencies that have their coins mined within the dataset and then have certain labeled data encoded (such as 'Algorithm' and 'ProofType') in a numerical representation.

After preprocessing the data, we perform a cluster analysis by first performing a Principle Component Analysis on the data set to reduce the total number of dimensions necessary to group the crypto currencies. Once PCA has been used, the K-means model to cluster the data.


## Summary
The 3D-Scatter plot with PCA data and the clusters is listed below (n_clusters for the K-Means Model is 4):

![3D-Scatter Plot]()


The 2D-Scatter Plot with each crypto currency labeled with a certain K-Means Model Class:

![2D-Scatter Plot]()