# Cryptocurrency Clustering Using K-Means and PCA
Module 19 Challenge

This project applies K-Means clustering and Principal Component Analysis (PCA) to group cryptocurrencies based on their movement patterns. By optimizing feature selection with PCA, the clustering process imporves in clarity and efficiency.

### Overview

The goal of this project is to analyze cryptocurrency market trends using unsupervised machine learning, identify distinct crypto clusters, and compare results with and without PCA optimization.

### Technologies Used 
* Python
* Pandas & NumPy
* Scikit-learn (for K-Means clustering & PCA)
* hvplot & Matplotlib (for data visualization)

### How It Works
1. Data Preprocessing
    * Load cryptocurrency market data.
    * Scalr features to ensure equal weighting in clustering.
2. K-Means Clustering on Raw Data
    * Apply K-Maens to price movement features.
    * Visualize clusters in 2D space based on 24h & 7-day price changes.
3. PCA Optimization
    * Reduce dimensionality with PCA.
    * Select the optimal number of components for clustering.
4. K-Means clustring on PCA Data
    * Apply clustering on PCA-transformed features.
    * Compare cluster distribution before & after optimization.
5. Cluster Visualization
    * Generate scatter plots to compare raw vs. optimized clusters.
    * Analyze trends based on principal components.

### Setup & Installation
1. Clone this repository

bash

```git clone https://github.com/JenniBean-K/CryptoClustering.git```


2. Create a virtual enviorment  and install dependencies

bash

```# 1. Create a virtual environment
python3 -m venv env

# 2. Activate the environment (Mac/Linux)
source env/bin/activate

# 3. Install dependencies from requirements.txt
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook
```
3. Run the clustering notebook

Open the corresponding notebook and follow the steps to generate clusters.

### Results & Analysis
* The optimized approach (with PCA) results in more dsitinct clusters, reducing high-dimensional features.
* PCA helps preserve key infomation while minimizing redundancy.
* The final clusters allow for improved trend identification among cryptocurrencies.

### Next Steps 
* Experimnet with different cluster numbers to refine grouping.
* Exten the analysis to include trading volume & volatility features.
* Intergate time-series analysis for dynamic clustering insights.

### Contributor 
* Jenni Kim 