# Cryptocurrencies

### Overview
The purpose of this analysis is to take a dataset of cryptocurencies and break it down to help make reccomendations to investment banks to help them break into this emerging asset. 
We will be doing this using unsupervised machine learning. To do so, we will be, preprocessing the data for PCA, reducing and scaling the data, clustering using K-Means and visualizing results.

### Results
* The first step was to take the dataset and turn it into a DataFrame.

<img width="503" alt="First_DF" src="https://user-images.githubusercontent.com/118485409/232531881-98260535-76cb-43ab-b444-c5e6ad1ef8f5.png">


* After some manipulation to the DataFrame, we then scaled the data.

<img width="485" alt="Scaled_Data" src="https://user-images.githubusercontent.com/118485409/232531971-c3181ae1-bb6d-40b9-9704-a7a001224979.png">


* Next, we used PCA to reduce the dimension to 3 principal components.

<img width="630" alt="PCA_DF" src="https://user-images.githubusercontent.com/118485409/232532055-4cb95fd1-3283-420d-a4b4-f5eda3c2cd21.png">


* To start our clustering, we had to use the elbow curve method to find how many clusters to use. The answer was 4.

<img width="491" alt="Elbow_Curve" src="https://user-images.githubusercontent.com/118485409/232532125-527ab3f8-8851-4655-ac91-d2f2121a7bc9.png">

* From there, we got our cluster DataFrame.

<img width="733" alt="Clustered_DF" src="https://user-images.githubusercontent.com/118485409/232532178-bcc17b93-bbfa-471d-b61e-90c8b679e194.png">

* Which we were then able to create a scatter chart with our clustered DataFrame.

<img width="655" alt="Cluster_Scatter" src="https://user-images.githubusercontent.com/118485409/232532237-0595f76b-c2d7-4cf2-be1c-c0c87d0d0d9b.png">

* Finally, after doing some manipulation to find which coins were tradable. We created a cluster chart showing how many coins were mined vs total coin supply. 

<img width="1157" alt="Scaled_TotalCoins_Cluster" src="https://user-images.githubusercontent.com/118485409/232532260-0301ac54-150b-4753-b84b-6f8da22674c5.png">

