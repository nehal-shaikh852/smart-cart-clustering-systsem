# smart-cart-clustering-systsem

An unsupervised machine learning project that segments customers into cluters according to their behavior.

## Project Overview
This project demonstrates the complete machine learning pipeline, including data pre-processing, EDA(Exploratory Data Analysis), Feature Engineering,dimensionality reduction and clustering.

## Steps Performed 

### 1. Data pre-processing 
- Handled missing values 
- Removed ouliers 

### 2. Feature Engineering 
- Convert date columns into meaningful features 
- Created new feature by combining related variables
- Reduced categorical values inot group categories 
- Encoded categorical columns into numercial coulmns 
- Applied feature scaling 
- Applied **PCA(Principal component Analysis)** for dimensionality reduction to avoid the curse of dimensionality  

### 3. Exploratory Data Analysis (EDA)
- Visualized data to detect patterns and outliers 
- plotted correlation heatmap to understand relationship between variables

### 4.Model Training
- Used **Elbow Method and silhouette score** to find optimal number of clusters (K)
- Trained clustering models:
   - K_Means Clustering
   - Hierarchical Clustering 
- **Hierarchical Clustering** provided better customer segmentation



