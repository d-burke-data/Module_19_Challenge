# Module_19_Challenge : CryptoClustering

This repository demonstrates unsupervised machine learning using K-Means clustering, with and without Principal Component Analysis (PCA). The code (in Python) and outputs are in the Jupyter Notebook *Crypto_Clustering.ipynb*. The dataset is a fictional representation of cryptocurrency price changes over various time periods. The optimal value of `k` is determined using the Elbow method for inertia. The results of clustering with and without PCA are presented as scatter plots.

# Conclusion

Visually analyzing the plots within the Jupyter Notebook, it is determined that PCA does not substantially improve clustering of the data. Yes, the data points are clustered more closely, but not necessarily with more distinction. The outlier points are more prominently displayed as such, but the larger clusters do not have any more definitive separation. As such, either method could be used for analysis with similar results.

# Repository Directory

|File|Purpose|
|---|---|
|Crypto_Clustering.ipynb|Jupyter Notebook to handle all code execution and provide outputs|
|Resources/crypto_market_data.csv|Cryptocurrency mock data file|
