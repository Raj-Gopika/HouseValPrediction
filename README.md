# Predicting House Values
Predicting prices of house values by KNN Regression

We are using the KNN regression model to predict the value of houses in California.
The data set used Claifornia Housing Data set from Scikit-Learn

## What is KNN regression
K-Nearest Neighbors (KNN) regression is a simple and intuitive method to predict a continuous output (i.e., a regression task) based on the similarity to other data points. In KNN regression, the value predicted for a new data point is determined by the values of its k closest neighbours in the feature space.

### How to implement
Choose the value of 𝑘

Calculate distance: For each data point, measure the distance from the new point to each data point in the training dataset. The most common distance metric used is Euclidean distance, though others like Manhattan or Minkowski distance can also be used.

Identify the k nearest neighbours

Compute the output: The predicted value for the new data point is the average of the values of the k nearest neighbors.
