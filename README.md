### Crypto Clustering

![Crypto-Tokens-and-Crypto-Coins-What-Drives-Performance](https://github.com/gulcanasln/CryptoClustering/assets/123443605/fcc210eb-b67f-4de6-a1e0-c99be77a6bb5)


In this project I use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
I find the best Value for k Using the Original Scaled DataFrame
Use the elbow method to find the best value for k using the following steps:
* Create a list with the number of k values from 1 to 11.
* Create an empty list to store the inertia values.
* Create a for loop to compute the inertia with each possible value of k.
* Create a dictionary with the data to plot the elbow curve.
* Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.

Cluster Cryptocurrencies with K-means Using the Original Scaled Data
Use the following steps to cluster the cryptocurrencies for the best value for k on the original scaled data:
* Initialise the K-means model with the best value for k.
* Fit the K-means model using the original scaled DataFrame.
* Predict the clusters to group the cryptocurrencies using the original scaled DataFrame.

  ![bokeh_plot](https://github.com/gulcanasln/CryptoClustering/assets/123443605/e5aa2633-68b4-41c8-a721-56923468b5d4)


Cluster Cryptocurrencies with K-means Using the PCA Data

Use the following steps to cluster the cryptocurrencies for the best value for k on the PCA data:
* Initialise the K-means model with the best value for k.
* Fit the K-means model using the PCA data.
* Predict the clusters to group the cryptocurrencies using the PCA data.
* Create a copy of the DataFrame with the PCA data and add a new column to store the predicted clusters.

![bokeh_plot](https://github.com/gulcanasln/CryptoClustering/assets/123443605/0738f088-6e27-4d7b-9dbe-587c831e51ed)

