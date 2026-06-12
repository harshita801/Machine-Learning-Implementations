# Local Outlier Factor (LOF) for Anomaly Detection

## Overview

This project demonstrates the implementation of the **Local Outlier Factor (LOF)** algorithm for anomaly detection using Scikit-Learn. The objective is to identify observations that significantly deviate from their local neighborhood density and classify them as outliers.

Unlike global anomaly detection methods, LOF evaluates each data point relative to its surrounding neighbors, making it highly effective for detecting local anomalies in complex datasets.

---

## Problem Statement

In real-world datasets, anomalies often occur within localized regions rather than being globally isolated. Traditional outlier detection techniques may fail to identify such observations.

This project explores how Local Outlier Factor detects anomalies by comparing the local density of a data point with the densities of its nearest neighbors.

---

## Methodology

### 1. Data Generation

A synthetic dataset was generated to simulate normal observations along with a small number of abnormal data points.

### 2. Data Visualization

The dataset was visualized to understand the distribution of observations and potential outliers.

### 3. Model Training

The Local Outlier Factor algorithm was applied to compute anomaly scores based on local density variations.

### 4. Outlier Detection

Data points with significantly lower local density compared to their neighbors were classified as anomalies.

### 5. Result Visualization

Detected outliers were highlighted separately for interpretation and analysis.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| NumPy | Numerical Computation |
| Pandas | Data Manipulation |
| Matplotlib | Data Visualization |
| Scikit-Learn | Machine Learning Library |
| Jupyter Notebook | Development Environment |

---

## Algorithm

### Local Outlier Factor (LOF)

Local Outlier Factor is an unsupervised anomaly detection algorithm that measures the local density deviation of a data point with respect to its neighboring observations.

A point is considered anomalous if its density is substantially lower than the densities of its surrounding neighbors.

### Key Characteristics

- Density-based anomaly detection
- Effective for local outlier identification
- No labeled data required
- Captures neighborhood-level anomalies
- Suitable for complex and non-uniform datasets

### Model Configuration

```python
from sklearn.neighbors import LocalOutlierFactor

lof = LocalOutlierFactor(
    n_neighbors=20,
    contamination=0.02
)

predictions = lof.fit_predict(X)
```

---

## Dataset Description

The dataset consists of:

- Normal observations concentrated in dense regions
- A small number of intentionally introduced anomalies
- Two numerical features for visualization and analysis

The objective is to distinguish unusual observations from the majority of normal data points.

---

## Results

The Local Outlier Factor algorithm successfully:

- Identified observations with abnormal local density
- Distinguished local anomalies from normal data points
- Demonstrated the effectiveness of density-based anomaly detection
- Visualized detected outliers for better interpretability

---

## Applications

Local Outlier Factor is commonly used in:

- Fraud Detection
- Network Security Monitoring
- Financial Risk Analysis
- Healthcare Data Monitoring
- Sensor Fault Detection
- Industrial Quality Control

---

## Learning Outcomes

This project provided practical experience in:

- Unsupervised Machine Learning
- Anomaly Detection Techniques
- Density-Based Outlier Detection
- Local Outlier Factor Implementation
- Data Visualization and Analysis
- Scikit-Learn Model Development

---

## Comparison with Isolation Forest

| Feature | LOF | Isolation Forest |
|----------|------|-----------------|
| Approach | Density-Based | Tree-Based |
| Detects Local Anomalies | ✅ Yes | ❌ Limited |
| Computational Cost | Higher | Lower |
| Scalability | Moderate | High |
| Interpretability | High | Moderate |

---

## Future Enhancements

- Hyperparameter optimization
- Comparison with Isolation Forest
- Comparison with One-Class SVM
- Evaluation on real-world datasets
- Interactive anomaly visualization dashboard

---

## Author

**Karra Harshita**

B.Tech, Electronics and Telecommunication Engineering

Machine Learning | Data Science | Software Development

---

### ⭐ If you found this project useful, consider giving it a star.