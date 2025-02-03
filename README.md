# Car Data Analysis

## Overview
This project analyzes a dataset of cars to extract insights using data preprocessing, clustering, and dimensionality reduction techniques.

## Data Cleaning & Preprocessing
- **Handling Missing Values:**
  - The "Market Category" column has ~30% missing values. Instead of dropping them, they are replaced with `'unknown category'`.
  - The missing values in **Engine Fuel Type, Engine HP, and Engine Cylinders** are minimal and are either dropped or analyzed further.

## Techniques Used
- **Feature Scaling:** `StandardScaler` is applied to normalize numerical data.
- **Clustering:** `KMeans` clustering is performed to group similar cars based on features.
- **Dimensionality Reduction:** `PCA` (Principal Component Analysis) is used to visualize and simplify the dataset.

## Key Findings
- **Clustering Results:**
  - Cars are grouped into meaningful clusters based on attributes like engine power, fuel type, and market category.
  - This helps identify trends in different car types.
- **PCA Outcomes:**
  - PCA reduces data complexity, making it easier to visualize clusters.
  - It confirms well-defined separations between different car groups.


