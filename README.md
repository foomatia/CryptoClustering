# CryptoClustering
Unsupervised Machine Learning

In this assignment, we had to use unsupervised machine learning techniques to analyse crypto currency data.

## 1. Data preparation
To start off, I imported the necessary dependencies which were pandas, hvplot.pandas and KMeans, PCA and StandardScaler from their respective sklearn libraries. 
After loading the provided csv, I used describe() and plotting to see what the data is like.

## 2. Analysis using Original Data
For this part, I created a list with k values from 1 to 11 and an empty list for inertia. After looping the data and appending the results to the intertia list, I plotted an Elbow Curve to find the optimal K-Means value which was 4. 
Using the original data, the next step was to initialze a K-Means model, fit the model using the original dataframe and predict the clusers to group the cryptocurrencies. After creating a copy of the original data, I plotted the data using hvplot. 

## 3. Optimizing with Principle Component Analysis
In this part of the analysis, I performed a PCA on the original data and reduces the features to three principle components. A new dataframe was created and the index was set to coin_id. Just as with the original data, the list for k-values and inertia was created and the PCA adjusted data was looped and appended. 
Another Elbow curve was plotted. The K-Means was also 4. 
This time the PCA adjusted data was used to prepare the scatter plot.

## 4. Final Visualization and Comparison
The last part was to create two composing plots to show both Elbow Curves and Scatter Plots in a manner which would make it easier to compare the visualizations. 

### Reference
To complete this assignment, I have used the materials provided by the bootcamp and took aid from StackOverflow and relevant documentations to solve errors. 
