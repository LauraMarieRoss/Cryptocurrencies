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
![Elbow Curve](https://user-images.githubusercontent.com/105830645/199651809-6db9661d-99e0-4acc-8db4-3ae2aec325d2.png)<br><br>


A 3-D Scatter Plot was used to visualize the clusters using a PCA algorithm.
![3D Scatter Plot](https://user-images.githubusercontent.com/105830645/199651716-4743a4db-4c96-40fd-9e6b-0c4bea21f03c.png)<br><br>

A 2-D Scatter Plot was then used to visualize the currencies by two principal components. Using this plot outliers can be identified. The chart below shows Class 2 as an outlier, with only one currency in the group. 
![2D Predicted Clusters](https://user-images.githubusercontent.com/105830645/199651743-095dea24-16b8-4827-9ee2-1b10ca1be08b.png)<br><br>

A table was then created of the tradable currencies. 
![Cryptocurrency Table](https://user-images.githubusercontent.com/105830645/199651950-3affaeff-a9d2-4ee8-886e-cb9b050087a7.png)<br><br>

An additional 2-D Scatter Plot comparing Total Coin Supply to Total Coins Mined was created.
![2D Total Coin Supply vs Total Coins Mined](https://user-images.githubusercontent.com/105830645/199651978-d40b63d4-f6d2-4019-9968-b1cdece1dabe.png)<br><br>


## Summary
The analysis showed that 532 of the cryptocurrencies available in the data were acceptable for trade during the analysis process. This is due to similarities they showed in features. The 3-D scatter plot using a PCA algorithm was the most effective way of classifying the currencies by features.





