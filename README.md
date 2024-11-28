# CryptoClustering
In this project, I analyzed cryptocurrency market data using unsupervised machine learning techniques, specifically focusing on clustering cryptocurrencies based on their 24-hour and 7-day price changes. The goal was to identify patterns and trends within the cryptocurrency market to understand how these price fluctuations impacted different cryptocurrencies.

The project involved several steps, including:

- **Data Preprocessing:** Normalizing the data using StandardScaler, followed by scaling the data for further analysis.

- **K-means Clustering:** Using the elbow method to determine the optimal number of clusters (k) and applying K-means clustering to group cryptocurrencies based on price change percentages.

- **Principal Component Analysis (PCA):** Reducing the dimensionality of the data to three principal components and optimizing the clusters using PCA.

- **Visualization:** Generating scatter plots to visualize the clustering results and comparing the impact of using the full dataset versus PCA-reduced features.

- **Optimization and Evaluation:** Evaluating the best value for k for both the original and PCA-reduced data and comparing the resulting clusters.

By the end of the project, I had developed a comprehensive clustering model that could be used to predict how cryptocurrencies were influenced by price changes over specific periods.

# Executing the Project
To run the project, ensure you have the required libraries installed. Clone this repository to your local machine and run the python notebook in this repository.