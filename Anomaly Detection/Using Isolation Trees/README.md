# Anomaly Detection using Isolation Forest

## Overview

This project demonstrates anomaly detection using the **Isolation Forest** algorithm on a synthetic dataset. The objective is to identify data points that significantly differ from the majority of observations and classify them as anomalies (outliers).

Isolation Forest is an unsupervised machine learning algorithm specifically designed for anomaly detection. Unlike distance-based approaches, it isolates anomalies by recursively partitioning data, making it highly efficient for large datasets.

---

## Problem Statement

In many real-world applications such as fraud detection, network security, manufacturing quality control, and healthcare monitoring, identifying unusual observations is critical.

This project explores how Isolation Forest can effectively detect anomalies within a dataset containing a dense cluster of normal observations and a small number of artificially introduced outliers.

---

## Methodology

### 1. Data Generation

A synthetic dataset was generated using Scikit-Learn's `make_blobs()` function to create a cluster of normal observations.

### 2. Outlier Injection

A few extreme data points were manually added to simulate anomalies.

### 3. Data Visualization

The dataset was visualized to understand the distribution of normal points and outliers.

### 4. Model Training

The Isolation Forest algorithm was trained to identify anomalous observations based on isolation principles.

### 5. Outlier Detection

Predictions were generated, and detected anomalies were highlighted on a scatter plot.

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

### Isolation Forest

Isolation Forest detects anomalies by randomly selecting features and splitting values. Since anomalies are few and significantly different from normal observations, they tend to be isolated in fewer splits compared to regular data points.

### Key Characteristics

- Unsupervised anomaly detection
- Efficient on large datasets
- Requires no labeled data
- Robust to high-dimensional data
- Suitable for fraud and intrusion detection applications

### Model Configuration

```python
from sklearn.ensemble import IsolationForest

model = IsolationForest(
    contamination=0.02,
    random_state=42
)

model.fit(X)
predictions = model.predict(X)
```

---

## Dataset Description

The dataset consists of:

- 300 normally distributed observations generated using `make_blobs()`
- 3 manually introduced outliers
- 2 numerical features

The outliers were intentionally placed far from the main cluster to evaluate the model's anomaly detection capability.

---

## Results

The Isolation Forest model successfully:

- Identified anomalous observations within the dataset
- Distinguished outliers from normal data points
- Demonstrated the effectiveness of tree-based anomaly detection
- Visualized detected anomalies for interpretability

Detected anomalies were highlighted separately from the main cluster for easy analysis.

---

## Applications

Isolation Forest is widely used in:

- Credit Card Fraud Detection
- Network Intrusion Detection
- Financial Risk Monitoring
- Manufacturing Defect Detection
- Healthcare Anomaly Detection
- Predictive Maintenance

---

## Learning Outcomes

This project provided hands-on experience in:

- Unsupervised Machine Learning
- Anomaly Detection Techniques
- Isolation Forest Implementation
- Data Visualization
- Outlier Analysis
- Scikit-Learn Model Development

---

## Future Improvements

- Experiment with different contamination values
- Compare with Local Outlier Factor (LOF)
- Compare with One-Class SVM
- Apply on real-world anomaly detection datasets
- Build an interactive anomaly detection dashboard

---

## Author

**Karra Harshita**

B.Tech, Electronics and Telecommunication Engineering

Machine Learning | Data Science | Software Development

---

### ⭐ If you found this project useful, consider giving it a star.