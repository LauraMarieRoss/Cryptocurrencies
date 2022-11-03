# Cryptocurrencies
Utilizing unsupervised machine learning techniques for analyzing cryptocurrencies.

## Project Overview
For this project unsupervised machine learning techniques were used to analyze a cryptocurrency database file. The client for the project is a prominent investment bank who would like to offer a cryptocurrency investment portfolio. Cryptocurrencies were grouped by features to create a classification system for investors. 


## Resources
<b>Data Sources:</b><br>
- CSV File Containing Cryptocurrency Data: crypto_data.csv<br>

<b>Software:</b><br>
- Python 3.9.13
- Pandas 1.4.4
- hvplot 0.8.1
- Plotly 5.10.0
- Scikit-learn 1.0.2
- Jupyter Notebook 6.4.12

## Results

The first step in the process was to determine the number of clusters. Using the Elbow Curve chart below the best K value is 4 clusters.

A 3-D Scatter Plot was used to visualize the clusters using a PCA algorithm.

A 2-D Scatter Plot was then used to visualize the currencies by two principal components. Using this plot outliers can be identified. The chart below shows Class 2 as an outlier, with only one currency in the group. 

A table was then created of the tradable currencies. 

An additional 2-D Scatter Plot comparing Total Coin Supply to Total Coins Mined was created.

## Summary
The analysis showed that 532 of the cryptocurrencies available in the data were acceptable for trade during the analysis process. This is due to similarities they showed in features. The 3-D scatter plot using a PCA algorithm was the most effective way of classifying the currencies by features.





