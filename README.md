# Unsupervised Learning on Breast Cancer Dataset

## Overview
This project demonstrates the application of unsupervised machine learning techniques on the Breast Cancer dataset. The goals are to explore patterns in tumor features, reduce dimensionality for visualization, and compare clustering methods.

## Techniques Used
- **K-means Clustering**: Partition data into clusters based on centroids.
- **K-medoids Clustering**: A robust clustering method using actual data points (medoids) as cluster centers.
- **PCA (Principal Component Analysis)**: Reduces dimensionality and visualizes high-dimensional data.

## Dataset
The dataset contains features extracted from breast cancer cell nuclei, including radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. Two classes: **Malignant (M)** and **Benign (B)**.

## Project Structure
- `project.ipynb`: Jupyter notebook with code and analysis.
- `project.html`: HTML version of the notebook.
- `data.csv`: Dataset used in the project.

## Key Findings
- Optimal number of clusters for both K-means and K-medoids is **2**, aligning with the two tumor types.
- K-means achieved a higher silhouette score than K-medoids, indicating better clustering performance.
- PCA visualization shows clear separation of clusters corresponding to tumor malignancy.
