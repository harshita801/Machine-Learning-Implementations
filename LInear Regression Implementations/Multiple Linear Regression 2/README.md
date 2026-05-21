# 🏠 California Housing Price Prediction using Multiple Linear Regression

A machine learning project that predicts California housing prices using Multiple Linear Regression. The project demonstrates an end-to-end regression workflow including data preprocessing, feature scaling, model training, model evaluation, visualization, and model serialization.

## 📌 Overview

The California Housing dataset contains demographic and housing-related information collected from California census blocks. The objective is to estimate median house values using multiple independent variables such as median income, house age, average rooms, population, and geographical location.

## ✨ Features

- Exploratory Data Analysis (EDA)
- Correlation analysis using heatmaps
- Feature standardization using `StandardScaler`
- Multiple Linear Regression model training
- Prediction on unseen test data
- Model evaluation using regression metrics
- Residual analysis
- Model persistence using Pickle

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## 🔄 Project Workflow

1. Load and inspect the California Housing dataset
2. Perform exploratory data analysis
3. Analyze relationships between features
4. Split data into training and testing sets
5. Standardize features using `StandardScaler`
6. Train the Multiple Linear Regression model
7. Generate predictions on test data
8. Evaluate model performance
9. Save the trained model using Pickle

## 📊 Visualizations

### Correlation Heatmap

Displays correlations between features and helps identify relationships within the dataset.

![alt text](image.png)

### Actual vs Predicted Values

Compares actual house prices with model predictions to evaluate prediction quality.

![alt text](image.png)

### Residual Distribution

Shows the distribution of prediction errors and helps assess model assumptions.

![alt text](image-1.png)

### Residual Scatter Plot

Visualizes residual patterns to check for randomness and detect potential issues in model performance.

![alt text](image-2.png)

## 📈 Model Evaluation

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics provide insights into prediction accuracy and overall model performance.

```

## 🎯 Key Learnings

- Multiple Linear Regression implementation
- Data preprocessing and feature scaling
- Exploratory Data Analysis techniques
- Regression model evaluation
- Residual analysis and interpretation
- Model serialization using Pickle

## 👨‍💻 Author

**Karra Harshita**  
B.Tech, Electronics & Telecommunication Engineering