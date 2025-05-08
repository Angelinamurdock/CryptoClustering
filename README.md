## Crypto Clustering
**Creator**: Angelina Murdock  
**Date**: May 2025

## Overview
This project uses unsupervised learning to predict whether cryptocurrencies will be affected by 24-hour or 7-day price changes. The approach includes clustering cryptocurrencies based on historical price change data using K-Means, with optional dimensionality reduction through PCA for visualization and improved grouping. Tools such as **scikit-learn, pandas,** and **hvplot** are used for preprocessing, clustering, and visualization.

## Table of contents
- [Overview](#overview)
- [Installation](#installation)
- [Methodology](#methodology)
- [Resources](#resources)

## Installation
**1. Clone the Repository:**
```bash
git clone https://github.com/Angelinamurdock/CryptoClustering.git
```

**2. Open the Project**:
- Open the `Crypto_Clustering_Final.ipynb` Jupyter Notebook File to interact with the project. 

**Requirements include:**
- pandas
- scikit-learn
- hvplot
- jupyter

### Methodology
**Data Preprocessing**
- **Standardization**: The price change features are standardized using **StandardScaler** to ensure all features have a mean of 0 and standard deviation of 1. This prevents features with larger ranges from dominating the clustering process.

**Dimensionality Reduction**
- **PCA**: Principal Component Analysis is used to reduce the feature space and highlight the most significant variance.

**Clustering with K-Means**
- **K-Means** is applied to group cryptocurrencies. The number of clusters is determined using the **Elbow Method**.

## Resources
- **DU Bootcamp Module 19:** Used challenge files and class materials from the bootcamp.
- **ChatGPT:** Assisted with code explanations and debugging.