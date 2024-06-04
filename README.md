**Customer Segmentation using K-Means, DBSCAN, and Agglomerative Clustering** investigates retail analytics to improve operations by understanding customer behavior. This notebook contains an in-depth Exploratory Data Analysis (EDA) and three clustering techniques: K-Means, DBSCAN, and Agglomerative Clustering, which are used to categorize mall customers based on their behavior and characteristics.

Key Points:
- **Goal:** Use EDA and visualization tools to uncover dataset complexities, then apply K-Means, DBSCAN, and Agglomerative Clustering for effective customer segmentation.
- **Hierarchical Clustering:** This unsupervised learning technique groups data points by similarity, providing a dendrogram to visualize relationships.
  - **Agglomerative Clustering:** Merges individual data points into clusters (bottom-up approach).
  - **Divisive Clustering:** Splits a single cluster into smaller ones (top-down approach).

**Conclusion:** Among the techniques, K-Means segmentation based on Annual Income and Spending Score proved most effective with significant cluster separation and quality (silhouette score: 0.5539, Davies-Bouldin Index: 0.5726). Agglomerative Clustering achieved equivalent but somewhat lower performance. DBSCAN was less appropriate due to low cluster quality. Thus, K-Means is recommended for mall consumer segmentation because of its stable and interpretable results.

The dataset used is from [Kaggle: Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).
