# 📈 Predictive Analytics Using Historical Data

A Machine Learning project that predicts **weekly Walmart sales** using historical sales data. This project applies predictive analytics techniques to forecast future sales trends by comparing **Linear Regression** and **Random Forest Regression** models.

---

## 📌 Project Overview

This project focuses on analyzing historical Walmart sales data to build predictive models. After preprocessing the dataset and performing exploratory data analysis (EDA), two regression algorithms were trained and evaluated.

The performance comparison shows that **Random Forest Regression** significantly outperformed **Linear Regression** in predicting weekly sales.

---

## 🚀 Features

- Load and preprocess historical sales data
- Perform Exploratory Data Analysis (EDA)
- Handle missing values and inspect dataset
- Feature selection for prediction
- Train-Test Split for model evaluation
- Linear Regression model implementation
- Random Forest Regression model implementation
- Compare model performance using R² Score
- Visualize actual vs predicted sales
- Feature Importance visualization

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

**Dataset:** Walmart Weekly Sales Dataset

Features used:

- Store
- Holiday_Flag
- Temperature
- Fuel_Price
- CPI
- Unemployment

Target:

- Weekly_Sales

---

## 📊 Exploratory Data Analysis

The project includes visualizations such as:

- Weekly Sales Distribution
- Holiday vs Weekly Sales
- Temperature vs Weekly Sales
- Fuel Price vs Weekly Sales
- Actual vs Predicted Sales
- Feature Importance

---

## 🤖 Machine Learning Models

### 1. Linear Regression

A baseline regression model used for prediction.

**R² Score:** **0.148**

---

### 2. Random Forest Regression

An ensemble learning model capable of capturing complex relationships between variables.

**R² Score:** **0.9327**

---

## 📈 Model Performance

| Model | R² Score |
|--------|---------:|
| Linear Regression | 0.148 |
| Random Forest Regression | 0.9327 |

Random Forest achieved significantly better prediction performance compared to Linear Regression.

---

## 📁 Project Structure

```
Predictive-Analytics/
│
├── Walmart.csv
├── Predictive_Analytics.ipynb
├── README.md
└── images/
```

---

## 📌 Future Improvements

- Hyperparameter tuning
- XGBoost Regression
- Time Series Forecasting
- Feature Engineering
- Model Deployment using Flask or Streamlit

---

## 🎯 Conclusion

Historical Walmart sales data was analyzed and used to build predictive machine learning models. While Linear Regression provided a baseline, Random Forest Regression achieved excellent performance with an R² score of **0.9327**, making it the preferred model for forecasting weekly sales.

---

## 👨‍💻 Author

**Jayachandiran K**

B.Tech Artificial Intelligence & Data Science

Machine Learning | Data Analytics | Python
