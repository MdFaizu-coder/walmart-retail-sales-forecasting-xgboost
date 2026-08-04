# 📈 Retail Sales Forecasting using XGBoost

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![XGBoost](https://img.shields.io/badge/XGBoost-Machine%20Learning-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

# 📌 Project Overview

Retail sales forecasting helps businesses predict future sales, optimize inventory, improve demand planning, and make data-driven decisions.

This project builds and evaluates multiple machine learning models to predict Walmart's weekly sales using historical sales and economic indicators. After comparing different algorithms, **XGBoost** achieved the highest prediction performance and was selected as the final model.

---

# 🎯 Objectives

- Predict weekly retail sales
- Analyze factors affecting sales
- Compare multiple machine learning models
- Identify the best-performing model
- Interpret feature importance

---

# 📂 Dataset

The dataset contains historical Walmart sales records with the following features:

| Feature | Description |
|----------|-------------|
| Store | Store Number |
| Date | Weekly Date |
| Weekly_Sales | Target Variable |
| Holiday_Flag | Holiday Indicator |
| Temperature | Weekly Temperature |
| Fuel_Price | Fuel Price |
| CPI | Consumer Price Index |
| Unemployment | Unemployment Rate |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Joblib
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis

Several visualizations were created to understand sales patterns and feature relationships.

## Weekly Sales Distribution

![](images/weekly_sales_distribution.png)

---

## Average Weekly Sales Over Time

![](images/average_weekly_sales_over_time.png)

---

## Correlation Heatmap

![](images/correlation_heatmap.png)

---

## Holiday vs Non-Holiday Sales

![](images/holiday_vs_non_holiday_sales.png)

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

# 📈 Model Comparison

![](images/model_comparison_r2_score.png)

After comparing all models, **XGBoost** produced the highest R² Score and was selected as the final forecasting model.

---

# ⭐ Feature Importance

![](images/xgboost_feature_importance.png)

The model indicates that **Store**, **Unemployment**, and **CPI** were among the most influential features affecting weekly sales predictions.

---

# 📁 Project Structure

```
retail-sales-forecasting-xgboost/
│
├── data/
│   └── Walmart.csv
│
├── notebook/
│   └── walmart_sales_forecasting.ipynb
│
├── model/
│   └── xgboost_sales_forecasting_model.pkl
│
├── images/
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/retail-sales-forecasting-xgboost.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 🚀 How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the notebook.
4. Run all cells.
5. View the generated predictions and visualizations.

---

# 📌 Future Improvements

- Hyperparameter Optimization
- Cross Validation
- Time-Series Forecasting Models
- Deployment using Streamlit
- Real-time Sales Prediction API

---

# 👨‍💻 Author

**Mohammed Faizuddin**

AI & Data Science Student

---

## ⭐ If you found this project helpful, consider giving it a star!