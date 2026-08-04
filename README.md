# 📈 Retail Sales Forecasting using XGBoost

![Project Banner](./images/model_comparison_r2_score.png)

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![XGBoost](https://img.shields.io/badge/XGBoost-Machine%20Learning-green?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

# 📌 Project Overview

Retail sales forecasting enables businesses to estimate future sales, optimize inventory management, improve demand planning, and support data-driven business decisions.

This project develops and compares multiple machine learning regression models to predict Walmart's weekly sales using historical sales records and economic indicators. Among all the evaluated models, **XGBoost** achieved the best performance and was selected as the final prediction model.

---

# 🎯 Objectives

- Predict Walmart weekly sales accurately
- Analyze factors influencing sales
- Perform Exploratory Data Analysis (EDA)
- Compare multiple machine learning models
- Identify the best-performing model
- Interpret feature importance

---

# 📂 Dataset

The dataset contains historical Walmart weekly sales records with the following features.

| Feature | Description |
|----------|-------------|
| Store | Store Number |
| Date | Weekly Sales Date |
| Weekly_Sales | Target Variable |
| Holiday_Flag | Holiday Indicator |
| Temperature | Average Temperature |
| Fuel_Price | Fuel Price |
| CPI | Consumer Price Index |
| Unemployment | Unemployment Rate |

---

# 🛠 Technologies Used

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

Several visualizations were created to understand sales patterns, trends, and relationships among different variables.

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

## Top 10 Stores by Average Weekly Sales

![](images/top_10_stores_average_weekly_sales.png)

---

## Bottom 10 Stores by Average Weekly Sales

![](images/bottom_10_stores_average_weekly_sales.png)

---

## Temperature vs Weekly Sales

![](images/temperature_vs_weekly_sales.png)

---

## Fuel Price vs Weekly Sales

![](images/fuel_price_vs_weekly_sales.png)

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

After comparing all models, **XGBoost achieved the highest R² Score and delivered the best prediction performance**, making it the final model for this project.

---

# ⭐ Feature Importance

![](images/xgboost_feature_importance.png)

The trained XGBoost model identified the following features as the most influential:

- Store
- Unemployment
- CPI
- Week

These variables contributed the most toward predicting weekly retail sales.

---

# 📁 Project Structure

```text
walmart-retail-sales-forecasting-xgboost/
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
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/MdFaizu-coder/walmart-retail-sales-forecasting-xgboost.git
```

Move into the project directory

```bash
cd walmart-retail-sales-forecasting-xgboost
```

Install the required packages

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
2. Install all required dependencies.
3. Open the notebook:

```text
notebook/walmart_sales_forecasting.ipynb
```

4. Run all notebook cells sequentially.
5. The notebook will:
   - Perform data preprocessing
   - Conduct Exploratory Data Analysis (EDA)
   - Train multiple machine learning models
   - Compare model performance
   - Display feature importance
   - Save the trained XGBoost model

---

# 📈 Model Performance

The machine learning models were evaluated using the **R² Score**.

| Model | Performance |
|--------|-------------|
| XGBoost | ⭐ Best |
| Random Forest | Excellent |
| Decision Tree | Good |
| Linear Regression | Lowest |

The comparison showed that **XGBoost significantly outperformed the other regression models**, making it the most suitable model for predicting Walmart's weekly sales.

---

# 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Time-series forecasting using Prophet or LSTM
- Streamlit web application
- FastAPI deployment
- Real-time sales prediction dashboard
- Automated model retraining pipeline

---

# 👨‍💻 Author

**Mohammed Faizuddin**

AI & Data Science Student

GitHub:
https://github.com/MdFaizu-coder

---

# 📜 License

This project is licensed under the **MIT License**.

See the **LICENSE** file for more information.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.