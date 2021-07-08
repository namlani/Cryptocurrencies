# Cryptocurrencies
## Overview
By using Principle Component Analysis (PCA), data was processed to fit an unsupervized machine learning model that employs a clustering algorithm, in order to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Results
Using a provided dataset, the data was prepocessed in order to perform PCA:

![image](https://user-images.githubusercontent.com/5934390/124955345-f623a200-dfe4-11eb-9927-5b463cc61a66.png)

![image](https://user-images.githubusercontent.com/5934390/124955553-223f2300-dfe5-11eb-9b37-a2079520adad.png)

Used PCA to reduce the dimensions of the above X DataFrame to three principal components:

![image](https://user-images.githubusercontent.com/5934390/124955823-60d4dd80-dfe5-11eb-867c-cb9fe036a134.png)

Ran a K-means algorithm to create an elbow curve and find the best value for K:

![image](https://user-images.githubusercontent.com/5934390/124956104-a691a600-dfe5-11eb-95a6-259d904f23b4.png)

This allowed for predicting the K clusters for the cryptocurrencies:

![image](https://user-images.githubusercontent.com/5934390/124956471-07b97980-dfe6-11eb-8d4c-21d353e45f63.png)

Used Plotly Express and hvplot to visualize the distinct groups that correspond to the three principal compnents that were created: 

![image](https://user-images.githubusercontent.com/5934390/124956705-3e8f8f80-dfe6-11eb-910d-89dd4ee4e337.png)

![image](https://user-images.githubusercontent.com/5934390/124956752-4c451500-dfe6-11eb-8909-35e26a80e313.png)

Created a final table containingg all the currently tradable cryptopcurrencies:

![image](https://user-images.githubusercontent.com/5934390/124956783-549d5000-dfe6-11eb-9e23-c7895825bc49.png)
