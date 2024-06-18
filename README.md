# K-Means Clustering for Retail Customer Segmentation

This project implements a K-Means clustering algorithm to segment customers of a retail store based on their purchase history. The goal is to group customers into clusters that exhibit similar purchasing behavior, which can help in targeted marketing, personalized customer service, and inventory management.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Clustering](#clustering)
- [Visualization](#visualization)
- [Evaluation](#evaluation)

## Introduction

Customer segmentation is a crucial aspect of retail business strategy. By understanding the different groups of customers based on their purchasing habits, businesses can tailor their marketing efforts, improve customer satisfaction, and optimize inventory.

This project uses the K-Means clustering algorithm, a popular unsupervised machine learning technique, to identify distinct customer segments in the dataset.

## Installation

To get started with this project, clone the repository and install the required dependencies.

## Dataset
The dataset used in this project is sourced from Kaggle. You can download it from the following link:

https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Preprocessing
Before applying the K-Means algorithm, the data needs to be preprocessed. This includes:

- Handling missing values
- Normalizing numerical features
- Encoding categorical features (if any)
- The preprocessing steps are implemented in the preprocessing.py file.

## Clustering
The K-Means clustering algorithm is implemented in the file. The number of clusters can be specified in the file.

The algorithm works as follows:

- Initialize the cluster centroids
- Assign each customer to the nearest centroid
- Update the centroids based on the assigned customers
- Repeat steps 2 and 3 until convergence
 
## Visualization
To understand the clustering results, the project includes various visualization tools:

- Elbow method to determine the optimal number of clusters
- Silhouette analysis
- 2D and 3D scatter plots of the clusters
- These visualizations are generated using the visualization.py file.

## Evaluation
Evaluate the clustering results using metrics such as:

- Inertia (within-cluster sum of squares)
- Silhouette score
- The evaluation metrics are calculated and displayed in the evaluation.py file.

