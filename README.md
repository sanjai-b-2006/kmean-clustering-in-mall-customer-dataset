# Kmean-clustering-in-mall-customer-dataset
K-means clustering algorithm to group customers of a retail store based on their purchase history.
Certainly! Here's a sample README file for your project to find the elbow value in `mall_customer.csv` and to create a K-means clustering algorithm to group customers based on their purchase history:

---

# Customer Segmentation using K-Means Clustering

This project aims to group customers of a retail store based on their purchase history using K-Means Clustering. The project involves finding the optimal number of clusters (`k`) using the Elbow Method and then creating a K-means clustering algorithm.


## Dataset Description

The dataset contains the following fields:
- `CustomerID`: Unique ID for each customer.
- `Gender`: Gender of the customer.
- `Age`: Age of the customer.
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars.
- `Spending Score (1-100)`: Spending score assigned by the store, based on customer behavior and purchase data.


1. **Load the Data**: Load the `mall_customer.csv` data file.
2. **Preprocess the Data**: Select relevant features and standardize them.
3. **Find the Elbow Value**: Use the Elbow Method to find the optimal number of clusters.
4. **Create K-Means Clustering Algorithm**: Apply K-means clustering to group customers based on their purchase history.
5. **Visualize the Clusters**: Plot the clusters to visualize the results.
