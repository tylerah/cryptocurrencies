# Analysis of Cryptocurrencies Using Unsupervised Machine Learning
## Overview
Cryptocurrencies are a popular investment option in the current market. However, with so many options it can be tricky trying to decide which ones to invest in. For this project, machine learning was used to group various trends of cryptocurrency options on the market. As there is no known output, unsupervised machine learning was used to group various cryptocurrencies using a clustering K-means algorithm. Subsequently, various visualizations were created using hvplot in a Jupyter Notebook. 

## Data Processing Procedure
In order to process the data for this project, the following steps were taken:
1. Data was preprocessed and loaded into a pandas DataFrame in preparation for machine learning process
2. PCA (Personal Component Analysis) was used to reduce data dimensions
3. K-means algorithm was used to cluster the data
4. Visualizations were created using hvplot libraries in a Jupyter Notebook

## Results
The original data file contained more than 1,200 cryptocurrencies. After cleaning the data there were only 532 usable data points. These data points were loaded into a DataFrame and further reduced. An Elbow curve was generated to identify the best value to use for clustering the data into groups. Subsequently, a table and various graphs were produced displaying each cryptocurrency grouped by their respective cluster. 

Elbow Curve:

![elbow_graph](https://user-images.githubusercontent.com/104606662/189284103-0b028ac5-b5a0-4877-a640-b86db0bfcb28.png)

DataFrame Containing the Clustered Data Points:

![clustered_df](https://user-images.githubusercontent.com/104606662/189284215-9e93c396-7f75-4b40-90b4-994585f4ec27.png)

Tradable Cryptocurrencies Table:

![tradable_crypto_df](https://user-images.githubusercontent.com/104606662/189284285-64aebd26-31d0-409e-933b-c0628d125015.png)

3D PCA Visualization:

![3d_pca](https://user-images.githubusercontent.com/104606662/189284330-af35531f-d6b4-4080-a86d-2b11124ced11.png)

Scatterplot Visualization:

![scatter_plot](https://user-images.githubusercontent.com/104606662/189284345-cf0bdd6c-1642-47b7-8263-501355fe549a.png)
