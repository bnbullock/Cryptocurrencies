# Cryptocurrencies

## Project Overview

A very important banking client is interested in offering a new cryptocurrency investment portfolio to its customers. The company, however, has some reservations about undertaking this challenge as they do not have a good handle on the universe of cryptocurrencies in the marketplace. So, they’ve tured to us and have requested a report outlining which cryptocurrencies are available on the trading market and how they could be grouped to create a classification system for this new investment.

The data we will be working with does not support our needs exactly, so it needs to be processed to fit the different machine learning models that will allow us to provide these answers. As this is an exploratory endevour, we are not sure of the expected results, therefore, we have decided to use unsupervised machine learning and specifically Principal Component Analysis(PCA). In order to group the cryptocurrencies, we have decided to utilize a clustering algorithm and will need to analyze the best fit for our data. Finally, we will be using data visualizations to share the findings with the board.

Deliverables:

1. Preprocessing the Data for PCA
2. Reducing Data Dimensions using PCA
3. Clustering Cryptocurriencies Using K-means
4. Visualizing Cryptocurrencies Results

------------------------------------------------------------------------------------------------------------

## Resources

- Software: Visual Studio Code 1.56.2, Python 3.7.10, Jupyter Notebook Server 6.3.0
- Browser : Google Chrome v91.0.4472.124
- Libraries: scikit-learn v0.24.2, hvplot v0.7.2, plotly v5.3.1

------------------------------------------------------------------------------------------------------------

## Results

- Below we can see the different steps undertaken to get to the final result. The data is evaluated and conditioned to arrive at the relevent attributes. We then use PCA to standardize the data and identify our principal components. Effectively, we are reducing the number of variables with the dataset, while preserving as much information as possible. We are then able to reorient the data from the original axes to the ones represented by the principal components. This allows us to cluster the data and generate the reports and visualizations that can then be presented to the client. the last 3 charts are interactive charts/reports and are intended for direct presentation to the client.

### Preprocessing Crypto Data

![Image1](images/1PreProcessed_1.png)

### Data Dimension Reduction using PCA

![Image2](images/2DataComponents_1.png)

### Elbow Curve showing Optimal Clustering

![Image3](images/3ElbowCurve_1.png)

### Final Chart with PCA Data and Clusters

![Image4](images/4ClusteredData_1.png)

### Scatter Plot showing data segmentation by Clusters

![Image5](images/5CryptoResults_1.png)

### Crypto Chart with Coin Availibility

![Image7](images/7CryptoChart_1.png)

------------------------------------------------------------------------------------------------------------

## Overall Summary

- As shown below we have been able to identify the different cryptocurrencies that are available for further investigation. The results show that we have 532 different cryptocurrencies to choose from with a general low level of supply.

### Report Showing Crypto Currencies

![Image6](images/6TradeableCrypto_1.png)
