# PRODIGY_ML_02

# 🛍️ Customer Segmentation using K-Means Clustering

## Overview
A beginner-level Machine Learning project that groups 
retail store customers into segments based on their 
purchase history using K-Means Clustering.

## Dataset
- Source: Kaggle - Customer Segmentation Tutorial
- Rows: 45,418 customer transactions
- Columns: 20 features including Quantity, 
  FinalPrice, Profit

## Features Used for Clustering
- Quantity — How much customer buys
- FinalPrice — How much customer spends
- Profit — How profitable the customer is

## Approach
1. Loaded and explored the dataset
2. Selected relevant numeric features
3. Scaled data using StandardScaler
4. Used Elbow Method to find optimal K=3
5. Trained K-Means model
6. Visualized customer segments

## Results — 3 Customer Segments Found

| Cluster | Type | Customers | Avg Price | Avg Profit |
|---|---|---|---|---|
| 0 | Budget | 17,690 | $739 | $138 |
| 1 | Regular | 21,519 | $969 | $136 |
| 2 | Premium | 6,209 | $6,560 | $1,570 |

## Visualizations
- Elbow Method graph
- Customer Segments scatter plot

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## What I Learned
- K-Means Clustering algorithm
- Elbow Method for finding optimal K
- Feature selection for clustering
- StandardScaler for data scaling
- Difference between supervised and 
  unsupervised learning
