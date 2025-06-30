# 🚗 Car Price Prediction – EDA & Machine Learning Project

This project performs *Exploratory Data Analysis (EDA)* and *Regression-based Machine Learning modeling* on a car dataset to predict the sellingprice of used cars. The entire project is done using *Python* with a focus on *numpy, pandas, and sklearn*, making it perfect for beginners and intermediate learners.


## 📁 Dataset Info

- *Filename:* dataset eda.csv
- *Source:* Uploaded by user
- *Target Column:* sellingprice
- *Features:* Make, model, year, engine specs, fuel type, condition, and other car attributes


## 🔍 Project Overview

### 1. 📊 Exploratory Data Analysis (EDA)

- Shape, datatypes, null values
- Summary statistics
- Value counts of categorical features
- Correlation matrix heatmap
- Visualizations using matplotlib and seaborn:
  - Countplots
  - Pairplots
  - Boxplots by year and price

### 2. 🤖 Machine Learning Models

We trained 4 regression models using *scikit-learn*:

| Model                    | Description |
|-------------------------|-------------|
| Linear Regression        | Simple baseline model |
| Decision Tree Regressor | Tree-based model capturing non-linearities |
| Random Forest Regressor | Ensemble method with multiple decision trees |
| Support Vector Regressor| SVM for regression problems |

#### ✅ Preprocessing Steps:
- Label Encoding for categorical variables
- Feature Scaling using StandardScaler
- Train/Test split (80/20)

#### 📈 Evaluation Metrics:
- Mean Squared Error (MSE)
- R² Score
- Visualizations of Actual vs Predicted


## 📦 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn

Author:

Sachin
BCA Student – Mini Project

---
