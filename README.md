# CryptoClustering: Unveiling Cryptocurrency Market Dynamics

## Overview
This project explores Crypto Clustering, predicting cryptocurrency fluctuations over 24-hour and 7-day intervals, utilizing Principal Component Analysis (PCA) to enhance clustering outcomes.

### Objective
The goal of this project is to leverage PCA for improved clustering, to better understand cryptocurrency market behaviors and to test the insights with and without using Principal Component Analysis (PCA). 

## Techniques 

### Data Preparation
- Data Loading
- Data Normalization

### Clustering Analysis
* Comparing original scaled data with the optimized PCA data<br/>
![Clustering Scatter Plot with PCA](img/pca_scatter.png "Clustering Scatter Plot with PCA")
## Key Findings

- **PCA Effectiveness**: Using PCA significantly improved the clustering quality, making the clusters more distinct and easy to interpret.
- **Optimal Cluster Count**: Using the PCA-transformed data and elbow curves helped to determine that four clusters was the optimal number in this case.
- **Impact of Dimensionality Reduction**: The use of PCA not only simplifies the dataset but also enhances the clustering, facilitating a more nuanced understanding of cryptocurrency market dynamics.

## Conclusion

This project underscores the utility of PCA in enhancing data clustering, particularly in the complex and fast-evolving cryptocurrency market. Through thoughtful analysis and strategic data manipulation, we uncover patterns and insights that could inform investment strategies and market analysis. Currencies that form their own clusters, like Etherlend and Celsius-degree, exhibit volatility patterns not found in the majority of currencies. Reducing the dimensions by utilizing PCA helped identify these outliers. 
