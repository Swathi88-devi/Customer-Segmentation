# Customer Segmentation using K-Means Clustering
This project demonstrates how to perform customer segmentation using the K-Means clustering algorithm. 
The goal is to group customers into distinct clusters based on their annual income and spending score. 
# Overview: 
Dataset: Mall_Customers.csv 
Features used: Annual Income (k$), Spending Score (1–100) 
Algorithm: K-Means Clustering - Visualization: Matplotlib and Seaborn
# Key Steps: 
1. Loaded the dataset and checked for missing values.
2. Selected relevant features for clustering (Annual Income and Spending Score).
3. Used the Elbow Method to determine the optimal number of clusters.
4. Trained the K-Means model with 5 clusters. 5. Visualized the resulting customer segments along with their centroids.
# How to Run:
1. Make sure the Mall_Customers.csv file is in your working directory.
2. Install dependencies if needed: pip install pandas matplotlib seaborn scikit-learn
3. Run the Python file:python project_13_customer_segmentation_using_k_means_clustering.py
# Results: 
The Elbow Method suggested 5 optimal clusters. 
The K-Means model successfully grouped the customers into 5 distinct segments based on their spending behavior and income levels. Each cluster represents a group of customers with similar characteristics, helping businesses target marketing strategies more effectively. 
# Author: 
P. Swathi Naga Devi
