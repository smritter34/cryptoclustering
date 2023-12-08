CryptoClustering: Uncovering Cryptocurrency Trends

Leveraging Python and unsupervised learning techniques, I aim to forecast the impact of 24-hour and 7-day price changes on cryptocurrencies. The step-by-step approach involves:

Data Preparation:
Utilizing the StandScaler module from scikit-learn to standardize the dataset, ensuring uniformity in the features.
Determining Optimal k:
Identifying the most suitable value for k (number of clusters) using the original scaled dataframe.
K-Means Clustering (Original Scaled Data):
Employing the k-means algorithm to cluster cryptocurrencies based on the original scaled data, uncovering inherent patterns and similarities.
Optimizing Clusters with Principal Component Analysis (PCA):
Utilizing Principal Component Analysis to enhance cluster quality and reduce dimensionality.
Finding Optimal k with PCA Data:
Determining the best value for k using the PCA-transformed data, ensuring optimal clustering.
K-Means Clustering (PCA Data):
Applying k-means clustering to the PCA-transformed data to unveil deeper insights into cryptocurrency relationships and trends.
