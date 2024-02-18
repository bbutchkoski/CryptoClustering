# CryptoClustering
# Overview 
- Data Preparation: Initially, the data is imported into a Pandas DataFrame from the file located at Resources/crypto_market_data.csv. Subsequently, it undergoes normalization using StandardScaler and is then examined to grasp its structure and contents.

- Clustering with K-Means: The K-Means clustering algorithm is employed to categorize cryptocurrencies based on their market data. The optimal number of clusters (k) is determined using the Elbow Method.

- Principal Component Analysis (PCA): To diminish dimensionality and enhance clustering performance, PCA is utilized on the dataset. This process aids in visualizing the data in lower dimensions while preserving a significant portion of its variance.

- Cluster Analysis: Cryptocurrencies are clustered utilizing both the original and PCA-transformed datasets. The resulting clusters are visualized to assess the efficacy of clustering before and after PCA.

- Visualization: A variety of plots, such as line plots and scatter plots, are utilized to visually represent the data, the Elbow Curve (for determining the optimal k value), and the clustering outcomes.

# Key Findings

- The Elbow Method indicates that, according to the original data, the optimal number of clusters for the K-Means algorithm is 3, while for the PCA-transformed data, it is 4.

- The PCA transformation exposes distinct clustering structures, indicating that reducing dimensionality can modify the arrangement of data points and potentially reveal more intricate clustering patterns.

- Comparing the clustering results visually with and without PCA illustrates the influence of dimensionality reduction on the distinctness and segregation of clusters.
