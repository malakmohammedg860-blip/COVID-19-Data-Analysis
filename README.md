# COVID-19 Data Analysis & Machine Learning

##  Project Overview

This project analyzes global COVID-19 data using Python to identify important trends, patterns, and relationships in the pandemic data.

The project also includes a Machine Learning model that predicts daily new COVID-19 cases based on historical case patterns.

---

##  Objectives

- Understand and clean the COVID-19 dataset.
- Perform Exploratory Data Analysis (EDA).
- Analyze global and country-level COVID-19 trends.
- Create meaningful data visualizations.
- Develop a custom COVID Impact Score.
- Build a Machine Learning model to predict daily new cases.
- Evaluate and compare different regression models.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📊 Data Analysis

The analysis includes:

- Dataset structure and statistical summary
- Missing value analysis
- Duplicate detection
- Data cleaning
- Global COVID-19 overview
- Top countries by confirmed cases
- Top countries by deaths
- Recovery rate comparison
- COVID-19 cases over time
- Daily case increases
- Confirmed cases vs deaths
- Correlation analysis
- Distribution of confirmed cases

---

## 📈 Visualizations

The project contains multiple visualizations, including:

- Top 10 countries by confirmed cases
- Top 10 countries by deaths
- Top countries by recovery rate
- Global confirmed cases over time
- Daily new case increases
- Confirmed cases vs deaths scatter plot
- Correlation heatmap
- Confirmed cases distribution
- COVID Impact Level comparison

---

##  COVID Impact Score

A custom COVID Impact Score was created using:

- Confirmed cases
- Deaths
- Recovery rate

Countries were classified into:

- **Low Impact**
- **Medium Impact**
- **High Impact**

This score provides a simple way to compare the overall impact of COVID-19 across countries.

---

##  Machine Learning

### Problem

The Machine Learning part of the project predicts the number of **new COVID-19 cases** using historical case patterns.

### Features

The model uses:

- New Cases Lag 1
- New Cases Lag 7
- 7-Day Rolling Average

### Models Tested

Three regression models were compared:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

### Best Model

**Linear Regression** achieved the best performance on the time-based test set.

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 185.84 | 948.02 | 0.9715 |
| Random Forest | 317.88 | 2215.05 | 0.8445 |
| Gradient Boosting | 309.09 | 2125.87 | 0.8568 |

The Linear Regression model was selected as the final model based on its lower MAE and RMSE and higher R² score.

---

## 📁 Project Files

```text
COVID-19-Data-Analysis/
│
├── COVID_19_Analysis.ipynb
├── covid_19_clean_complete.csv
├── covid_linear_regression_model.pkl
└── README.md
