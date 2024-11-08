# CryptoClustering

This script analyzes a DataFrame containing price changes of different lengths of time of various crypto currencies using unsupervised learning and clustering.

The script begins by standardizing the data and using the Elbow method to determine the most optimal number of clusters and then uses the K-Means method to determine clusters. It then visualizes these clusters using a scatter plot.

Then, it uses PCA to accomplish the same task and compares the results.

I found that PCA resulted in 4 clusters being optimal while using the normal data resulted in 3. PCA made the clusters much more easy to visualize, but abstracted the data so it made less sense to me and any person who does not have technical knowledge about data.