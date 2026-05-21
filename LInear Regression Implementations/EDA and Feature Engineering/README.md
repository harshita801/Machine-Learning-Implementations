# 🔥 Algerian Forest Fires - End-to-End Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Regression-orange)
![EDA](https://img.shields.io/badge/EDA-Feature%20Engineering-red)

---

# 📌 Project Overview

This project demonstrates a complete Machine Learning workflow using the **Algerian Forest Fires Dataset**.

The project includes:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Feature Scaling
- Regression Model Training
- Model Evaluation

The goal of this project is to understand how real-world ML preprocessing and regression pipelines are implemented using Python and Scikit-learn.

---

# 📂 Dataset Information

Dataset Used:
**Algerian Forest Fires Dataset**

The dataset contains meteorological and fire weather observations collected from two regions of Algeria.

---

# 📊 Features in Dataset

| Feature | Description |
|---|---|
| Temperature | Temperature in Celsius |
| RH | Relative Humidity |
| Ws | Wind Speed |
| Rain | Rainfall |
| FFMC | Fine Fuel Moisture Code |
| DMC | Duff Moisture Code |
| DC | Drought Code |
| ISI | Initial Spread Index |
| BUI | Build Up Index |
| FWI | Fire Weather Index |
| Classes | Fire / Not Fire |
| Region | Region Identifier |

---

# 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🧹 Data Cleaning & Preprocessing

Performed several preprocessing steps including:

- Handling missing values
- Removing null rows
- Resetting indexes
- Fixing inconsistent column names
- Removing unnecessary rows
- Data type conversion
- Encoding categorical features

Example:

```python
df = df.dropna().reset_index(drop=True)
```

---

# 🔍 Exploratory Data Analysis (EDA)

Performed EDA to understand:

- Feature distributions
- Correlation between variables
- Statistical summaries
- Outliers
- Data imbalance
- Fire weather patterns

Visualizations used:

- Histograms
- Heatmaps
- Boxplots
- Distribution plots
- Correlation matrix

---

# 📊 Data Visualization

## 🔥 Correlation Heatmap

![alt text](image.png)

---

## 📦 Boxplots for Before vs After Feature Scaling

![alt text](image.png)

---


## 🎯 Prediction Scatter Plot

![alt text](image.png)

---

# ⚙️ Feature Engineering

Feature engineering steps included:

- Encoding categorical labels
- Feature selection
- Preparing independent and dependent features
- Removing irrelevant columns

Example:

```python
X = df.drop("FWI", axis=1)
y = df["FWI"]
```

---

# 🤖 Machine Learning Models Used

Implemented and compared multiple regression models:

- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- LassoCV

---

# 📉 Model Evaluation Metrics

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 🎯 Key Learning Outcomes

Through this project, I learned:

- Real-world data preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Feature Scaling
- Regression algorithms
- Model evaluation techniques
- End-to-end ML workflow implementation

---

# 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deployment using Streamlit/Flask
- Advanced dashboards and visualizations

---

# 👩‍💻 Author

## Karra Harshita

Second-Year B.Tech Student  
Electronics and Telecommunication Engineering (ETC)

---

# ⭐ If you found this project useful, feel free to star the repository.