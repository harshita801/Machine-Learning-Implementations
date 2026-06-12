# DBSCAN Clustering for Non-Linear Data Analysis

## Overview

This project demonstrates the application of the Density-Based Spatial Clustering of Applications with Noise (DBSCAN) algorithm on a non-linear dataset generated using Scikit-Learn. The objective is to explore how density-based clustering techniques can effectively identify clusters with arbitrary shapes while handling noise and outliers.

Unlike centroid-based algorithms such as K-Means, DBSCAN does not require the number of clusters to be specified beforehand and performs well on datasets containing irregular cluster structures.

---

## Problem Statement

Many clustering algorithms struggle to identify non-linear patterns in data. This project investigates the effectiveness of DBSCAN in discovering meaningful clusters within a circular dataset where traditional clustering approaches often fail.

---

## Methodology

### 1. Data Generation

A synthetic dataset was created using Scikit-Learn's `make_circles()` function to simulate a non-linear clustering problem.

### 2. Data Visualization

The generated dataset was visualized to understand its structure and distribution before model application.

### 3. Clustering

DBSCAN was applied to identify dense regions and assign cluster labels based on neighborhood density.

### 4. Result Analysis

The predicted clusters were visualized and compared with the original dataset structure.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Scikit-Learn | Machine Learning Library |
| Jupyter Notebook | Development Environment |

---

## Algorithm

### DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

DBSCAN groups data points based on density connectivity rather than distance from a centroid.

Key characteristics:

- Detects clusters of arbitrary shapes
- Automatically identifies noise points
- Does not require specifying the number of clusters
- Effective for non-linear datasets

### Parameters Used

| Parameter | Value |
|------------|---------|
| eps | 0.1 |
| Algorithm | DBSCAN |

---

## Results

The model successfully:

- Identified the underlying circular cluster structure.
- Demonstrated the capability of density-based clustering on non-linear data.
- Separated dense regions without requiring prior knowledge of cluster count.
- Highlighted the robustness of DBSCAN compared to centroid-based methods.

---

## Future Enhancements

- Hyperparameter optimization using nearest-neighbor analysis
- Comparison with K-Means and Agglomerative Clustering
- Application on real-world datasets
- Evaluation using clustering performance metrics
- Interactive visualizations

---

## Learning Outcomes

This project provided practical experience in:

- Unsupervised Machine Learning
- Density-Based Clustering Techniques
- Cluster Visualization
- Parameter Tuning in DBSCAN
- Working with Non-Linear Data Distributions

---

## Author

**Karra Harshita**

B.Tech, Electronics and Telecommunication Engineering

Machine Learning | Data Science | Software Development

---

If you found this project useful, consider giving it a star.