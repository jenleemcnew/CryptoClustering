# Crypto Clustering

## Overview
An unsupervised machine learning project that clusters cryptocurrencies based on 
24-hour and 7-day price change patterns. Uses K-Means clustering and Principal 
Component Analysis (PCA) to identify groupings and evaluate the impact of 
dimensionality reduction on cluster quality.

---

## Approach

### K-Means on Original Scaled Data
- Normalized market data using StandardScaler
- Applied the elbow method to determine the optimal number of clusters (k)
- Clustered cryptocurrencies and visualized results using hvPlot scatter plots

### PCA Optimization
- Reduced features to three principal components
- Re-applied elbow method on PCA data to find optimal k
- Compared clustering results before and after dimensionality reduction to assess 
  the impact of using fewer features

---

## Key Concepts Demonstrated
- Data normalization with StandardScaler
- Elbow method for optimal k selection
- K-Means clustering
- Principal Component Analysis (PCA)
- Interactive visualization with hvPlot

---

## Tech Stack
- Python (Pandas, Scikit-learn, hvPlot)
- Jupyter Notebook

---

## Repository Contents
| File | Description |
|------|-------------|
| `Crypto_Clustering.ipynb` | Full analysis notebook |
| `crypto_market_data.csv` | Source cryptocurrency market data |
