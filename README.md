# Customer-Segmentation-Using-PCA-and-Clustering

An unsupervised machine learning project that analyzes customer demographics, purchasing behavior, website activity, and campaign engagement to identify distinct customer segments.

## Overview

This project performs customer segmentation using clustering techniques on a dataset containing **2,240 customer records and 22 attributes**.

The workflow includes:

* Data exploration and preprocessing
* Missing value handling
* Feature engineering
* Outlier removal
* Categorical encoding
* Feature scaling
* Dimensionality reduction using PCA
* Cluster selection using the Elbow Method and Silhouette Score
* Customer segmentation using K-Means and Agglomerative Clustering
* Cluster visualization and analysis

## Tools & Technologies

* **Python**
* **Pandas**
* **Matplotlib**
* **Seaborn**

### Machine Learning

* **Scikit-learn**

  * `OneHotEncoder`
  * `StandardScaler`
  * `PCA`
  * `KMeans`
  * `AgglomerativeClustering`
  * `silhouette_score`

### Cluster Analysis

* **Kneed** — used to identify the optimal number of clusters using the Elbow Method

## Dataset

The dataset contains **2,240 customer records and 22 attributes** covering areas such as:

* Customer demographics
* Income
* Education
* Marital status
* Customer tenure
* Product spending
* Purchase channels
* Website activity
* Campaign responses

## Methodology

```text
Raw Dataset
     ↓
Data Preprocessing
     ↓
Feature Engineering
     ↓
Outlier Removal
     ↓
Categorical Encoding
     ↓
Feature Scaling
     ↓
    PCA
     ↓
Elbow Method + Silhouette Score
     ↓
K-Means Clustering
     ↓
Agglomerative Clustering
     ↓
Cluster Analysis
```

## Results

The clustering process identifies **4 distinct customer segments**.

Cluster 0:
  * Moderate-Income 
  * Low-Spending Partner Customers
    
Cluster 1:
 * High-Income
 * High-Spending Partner Customers

Cluster 2: 
  * Low-Income
  * Low-Spending Individual Customers

Cluster 3: 
  * High-Income
  * High-Spending Individual Customers

## Future Improvements

* Compare additional clustering algorithms such as DBSCAN and Gaussian Mixture Models.
* Improve cluster validation and evaluation.
* Create an interactive dashboard for exploring customer segments.
* Develop personalized recommendations for different customer segments.

