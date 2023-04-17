# Cryptocurrencies

### Overview
The purpose of this analysis is to take a dataset of cryptocurencies and break it down to help make reccomendations to investment banks to help them break into this emerging asset. 
We will be doing this using unsupervised machine learning. To do so, we will be, preprocessing the data for PCA, reducing and scaling the data, clustering using K-Means and visualizing results.

### Results
* The first step was to take the dataset and turn it into a DataFrame.


* After some manipulation to the DataFrame, we then scaled the data.


* Next, we used PCA to reduce the dimension to 3 principal components.


* To start our clustering, we had to use the elbow curve method to find how many clusters to use. The answer was 4.


* From there, we got our cluster DataFrame.


* Which we were then able to create a scatter chart with our clustered DataFrame.


* Finally, after doing some manipulation to find which coins were tradable. We created a cluster chart showing how many coins were mined vs total coin supply. 