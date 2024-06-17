# CryptoClustering
Challenge 19
# Summary
- This project involves analyzing cryptocurrency market data by using clustering techniques and Principal Component Analysis (PCA). The goal is to group cryptocurrencies based on their market data and visualize the clusters.
# Data Loading and Preprocessing
- Imported necessary libraries and dependencies including pandas, hvplot, scikit-learn, matplotlib, and os.
- Loaded the cryptocurrency market data into a Pandas DataFrame.
- Displayed sample data and generated summary statistics.
- Visualized the data using hvPlot to understand the distribution and trends.
# Data Normalization
- Used StandardScaler from scikit-learn to normalize the data.
- Created a DataFrame with the scaled data and set appropriate indices.
# Elbow Method for Optimal k (Original Data):
- Created a range of k-values from 1 to 11.
- Computed the inertia for each k-value using KMeans clustering.
- Plotted the Elbow curve to visually identify the optimal number of clusters.
# K-Means Clustering (Original Data):
- Initialized and fitted the K-Means model using the optimal k-value obtained from the Elbow method.
- Predicted the clusters and added the cluster information to the original DataFrame.
- Created and displayed a scatter plot to visualize the clusters.
# Principal Component Analysis (PCA):
- Applied PCA to reduce the data to three principal components.
- Created a DataFrame with the PCA-transformed data.
- Calculated and printed the explained variance for each principal component.
# Repeated the Elbow Method process and K-Means Clustering for PCA Data
# Composite Plots for Comparison
- Created composite plots using hvPlot to compare the Elbow curves from the original and PCA data.
- Created composite scatter plots to compare the clustering results from the original and PCA data.
