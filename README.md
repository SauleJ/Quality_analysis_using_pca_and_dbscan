## Wine Quality Analysis with PCA and DBSCAN

This repository contains code for analyzing wine quality data using Principal Component Analysis (PCA) and Density-Based Spatial Clustering of Applications with Noise (DBSCAN). The main goals of this analysis are:

* **Outlier Detection and Marking:** Identify and label potential outliers in the data.
* **Feature Selection:** Use PCA to reduce dimensionality and select the most important features.
* **Clustering Using PCA:** Visualize the data using PCA and explore quality groupings.
* **DBSCAN Clustering:** Apply DBSCAN to identify clusters based on density and detect noise points.

## Code Structure

The code is organized as follows:

1. **Load Libraries:** Import necessary libraries for data analysis and visualization.
2. **Load Dataset:** Load the wine quality dataset from the 'reduced_data.csv' file.
3. **Outlier Detection and Marking:**
   * Visualize potential outliers using boxplots.
   * Mark outlier data points based on IQR criteria.
   * Provide outlier statistics.
4. **Feature Selection:**
   * Apply PCA to determine the optimal number of features to keep.
   * Fit and transform the data using PCA with the selected number of components.
   * Calculate and present PCA loadings for interpretation.
5. **PCA Reduction to Two Components:**
   * Further reduce PCA to two components for visualization.
6. **Clustering Using PCA:**
   * Visualize data points in the PCA space, colored by quality and outlier status.
7. **DBSCAN:**
   * Use the k-distance graph to determine the epsilon parameter for DBSCAN.
   * Apply DBSCAN to cluster the data based on density.
   * Visualize clusters and analyze composition with respect to quality.
