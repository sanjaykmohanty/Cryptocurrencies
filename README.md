# Cryptocurrencies

## Overview
The purpose of this project is to use unsupervised machine learning on Crypto dataset to analyze what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for the new investment portfolio Accountability Accounting,  a prominent investment bank, is planning to offer to its customers. The analysis steps cover how to process data, how to cluster, how to reduce dimensions, and how to reduce the principal components using PCA. 

The data was processed to fit the machine learning models. As there was no known output, unsupervised machine learning techniques were used for this analysis. To group the cryptocurrencies, a clustering algorithm was used. 

The analysis consists of four technical steps:
- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCA
- Clustering Cryptocurrencies Using K-means
- Visualizing Cryptocurrencies Results

## Resources
**Data Source:** crypto_data.csv, CryptoCompare
**Software:** Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results
After preprocessing and cleaning the data for PCA, we ended up with a total of 532 tradable cryptocurrencies.

![image](https://user-images.githubusercontent.com/31812730/212247924-a2b80a15-e588-4e2d-947f-5deca378bf55.png)

Elbow curve was produced as shown below using the K-Means method iterating on k values from 1 to 10. The best K value was concluded on an output of 4 clusters to categorize the crytocurrencies.

![image](https://user-images.githubusercontent.com/31812730/212248365-136b042c-54eb-4380-a9ea-b51d6c88f185.png)

3D-Scatter with the PCA data and the clusters is shown below.

![image](https://user-images.githubusercontent.com/31812730/212249116-fe2cfdea-ca04-41b5-85b2-209cd63e0ebb.png)

Tradable Cryptocurrencies Table is shown below.

![image](https://user-images.githubusercontent.com/31812730/212249298-51f1d6ca-297f-4cf4-9ec3-d9e96ce60f3f.png)

Scatter plot with TotalCoinMined vs TotalCoinSupply

![image](https://user-images.githubusercontent.com/31812730/212250255-c37496f1-a3d8-478f-9297-ec87bb876021.png)

## Summary
The classification of 532 cryptocurrencies based on the similarities of their features are identified. Based on the results, cryptocurrencies in the Crypto dataset can be clustered into 4 distinct groups. Cluster results can be analyzed further for the new investment portfolio.
