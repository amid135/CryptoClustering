# CryptoClustering
Overview
The CryptoClustering project explores unsupervised learning techniques to analyze cryptocurrency data. The goal is to identify clusters of cryptocurrencies based on their price changes over different time periods. This project utilizes K-Means clustering and Principal Component Analysis (PCA) to uncover patterns in the data.

Files
- Crypto_Clustering.ipynb: The main Jupyter Notebook containing the code for data analysis, clustering, and visualization.
- crypto_market_data.csv: The dataset used for analysis.

- Create a list of k values from 1 to 11.
- Compute inertia values for each k value.
- Plot the elbow curve to visually identify the optimal value for k.

Cluster Analysis:
- Initialize the K-Means model with the best value for k.
- Fit the model and predict clusters for the original scaled data.
- Add a column for predicted clusters in the original DataFrame.
- Create a scatter plot with hvPlot to visualize clusters.

Optimize Clusters with PCA
Perform PCA:
- Reduce features to three principal components using PCA.
- Retrieve and display the explained variance of the three components.

Elbow Method on PCA Data:
- Compute the best value for k using the PCA data.
- Plot the elbow curve for the PCA data.

Cluster Analysis with PCA:
- Initialize the K-Means model with the best k value from PCA.
- Fit the model and predict clusters using PCA data.
- Add a column for predicted clusters in the PCA DataFrame.
- Create a scatter plot with hvPlot to visualize clusters in PCA space.

Visualize and Compare Results
Composite Plots:
- Compare elbow curves from original data and PCA data.
- Compare clusters from original data and PCA data.

Impact Analysis:
- Analyze and document the impact of using fewer features for clustering.
- Coding Conventions
- Imports: Place all imports at the top of the file.
- Naming: Use lowercase with underscores for function and variable names.
- DRY Principle: Ensure code is maintainable and reusable.
- Logic: Use concise logic and creative engineering where possible.
- Deployment and Submission
