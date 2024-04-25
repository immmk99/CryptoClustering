# CryptoClustering
 
**Crypto Clustering Project: Comprehensive Summary**

### Project Overview
This project leverages Python and unsupervised learning techniques to predict the impact of short-term (24-hour) and medium-term (7-day) price changes on various cryptocurrencies. By clustering cryptocurrencies based on price change data, we aim to identify patterns and insights that could inform investment strategies.

### Completed Tasks
- **Repository Setup**
  - Created a dedicated repository, `CryptoClustering`, for clean management of all project files.
  - Cloned the repository to a local machine to work directly with the project files.
  
- **File Preparation and Initial Setup**
  - Renamed `Crypto_Clustering_starter_code.ipynb` to `Crypto_Clustering.ipynb`.
  - Loaded and examined the `crypto_market_data.csv` to understand data structure and key statistics.
  
- **Data Preparation**
  - Normalized the dataset using the `StandardScaler()` from scikit-learn to prepare for clustering.
  - Generated a scaled DataFrame, maintaining the `coin_id` as an index for consistent tracking of data.

- **Optimal Cluster Identification**
  - Implemented the elbow method to determine the optimal number of clusters (k) from 1 to 11 based on inertia.
  - Identified the best k value using the original scaled data and through PCA reduced data for comparative analysis.

- **Clustering with K-Means**
  - Clustered the cryptocurrencies using the original scaled data and the PCA-reduced dataset to compare the clustering effectiveness based on the number of features used.
  - Visualized clusters using hvPlot to observe how cryptocurrencies group based on 24-hour and 7-day price changes.

- **Principal Component Analysis (PCA)**
  - Reduced data dimensions to three principal components to optimize clustering performance.
  - Evaluated the explained variance to confirm the amount of information retained post-PCA.

- **Visualization and Comparative Analysis**
  - Created composite plots to visually compare elbow curves and clustering results from the original and PCA-reduced datasets.
  - Discussed the impact of using fewer features on the effectiveness of clustering cryptocurrencies.

### Key Insights and Impact
This analysis provided valuable insights into how different cryptocurrencies respond to market changes over varying time frames. The use of PCA highlighted the potential to reduce data complexity without significantly compromising the clustering outcomes. The findings from this project can aid investors in making informed decisions by understanding the underlying patterns in cryptocurrency price movements.

### Conclusion
The project successfully demonstrated the use of unsupervised learning techniques to analyze and predict cryptocurrency behaviors based on historical price change data. Through rigorous data processing, optimal cluster determination, and insightful visualizations, we were able to offer actionable insights into the dynamic cryptocurrency market.
