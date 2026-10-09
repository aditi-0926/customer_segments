# Customer Segmentation with K-Means

Python script that segments customers from the iFood dataset using K-Means clustering.

## Overview

Performs exploratory analysis, feature engineering, and unsupervised clustering on customer data to identify distinct segments based on income, spending, purchases, and recency.

## Features Used

- **Income**
- **Total_Spending** (sum of wines, fruits, meat, fish, sweets, gold products)
- **Total_Purchases** (web + catalog + store purchases)
- **Recency**

## Pipeline

1. **Data Loading & Cleaning** – Load `ifood_df.csv`, remove duplicates
2. **Feature Engineering** – Create Total_Spending and Total_Purchases
3. **EDA** – Income, spending, and purchase distributions; correlation heatmap; income vs spending scatter
4. **Scaling** – StandardScaler on selected features
5. **Elbow Method** – Determine optimal number of clusters (K=4)
6. **K-Means Clustering** – Assign customers to 4 segments
7. **Visualization & Analysis** – Cluster scatter plots and mean profile summary

## Requirements

```bash
pandas
matplotlib
seaborn
scikit-learn
