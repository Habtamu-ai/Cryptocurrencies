
# Cryptocurrencies
# Overview
The objective of this project is to process all available cryptocurrencies that are available in the market. Then, process the data, organize, and visualize them. 

# Results
 - Total number of cryptos
 The below table shows the available cryptos in the market.  We could find 1256 different kinds of cryptos. The data also contain different important pieces of information, such as the coin name, the algorithm, if it is trading, the proof type, if the coin is mined, and the total supply of the coin.

![crypto_Market](https://user-images.githubusercontent.com/78656720/123482234-eb274580-d5d2-11eb-8870-5c0853b43443.png)


- Reducing Data Dimensions Using PCA

Once we discovered all the cryptos ou in the market we cleaned the data and organized it for analysis. Then the project creates the Principal Component Analysis (PCA) algorithm, and reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

![Reduced_diamension](https://user-images.githubusercontent.com/78656720/123482953-05adee80-d5d4-11eb-8317-fc959e7d7ed0.png)

- Clustering Cryptocurrencies Using K-means
 The project uses the K-means algorithm to create an elbow curve using hvPlot to find the best value for K from the above principal component data frame. Then, we run the K-means algorithm to predict the K clusters for the cryptocurrency data.
 
![Elbow_Curve](https://user-images.githubusercontent.com/78656720/123479981-af3eb100-d5cf-11eb-8071-a15a5316e94b.png)

- Visualizing Cryptocurrencies Results

![3D_scatter](https://user-images.githubusercontent.com/78656720/123484581-97b6f680-d5d6-11eb-92f6-98f9c41224f6.png)

Finally, the project is creating scatter plots with Plotly Express and hvplot, we visualize the distinct groups that correspond to the three principal components we created in the above table, then we create a table with all the current tradable cryptocurrencies using the hvplot.

![hvplot](https://user-images.githubusercontent.com/78656720/123484707-cf25a300-d5d6-11eb-8f80-2ad3002bad75.png)

# Summary
The project process the data using all available cryptos in the market. Then, reduce the data dimensions using principal component analysis. Finally, it clusters the Cryptocurrencies using K-means and visualizes the result.
