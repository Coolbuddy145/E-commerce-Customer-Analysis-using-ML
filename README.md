# E-commerce Customer Analysis

A linear regression project that analyzes customer behavior and predicts yearly spending amounts for an e-commerce company.

## 📊 Project Overview

This project builds and evaluates machine learning models to predict customer yearly spending based on their behavioral patterns. The analysis includes exploratory data analysis, feature correlation studies, and comparison of multiple regression models.

## 🎯 Objectives

- Analyze relationships between customer behavior features and yearly spending
- Build predictive models using Linear Regression, Ridge, and Lasso
- Evaluate model performance and identify key drivers of customer spending
- Provide insights for business decision-making

## 📁 Dataset

The dataset contains customer information with the following key features:
- `Avg. Session Length`: Average session duration
- `Time on App`: Time spent on the mobile application
- `Time on Website`: Time spent on the website
- `Length of Membership`: Customer membership duration
- `Yearly Amount Spent`: Target variable (yearly spending amount)

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning models and evaluation

## 📈 Key Findings

### Feature Correlations
- `Length of Membership` shows the strongest correlation with yearly spending
- `Time on App` has moderate predictive power
- `Time on Website` shows weaker correlation but is retained for model completeness

### Model Performance
All models performed exceptionally well with:
- **R² Scores**: ~0.98 (indicating excellent explanatory power)
- **Low MSE and MAE values**
- Minimal overfitting as confirmed by Ridge and Lasso regularization

## 🚀 Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/Coolbuddy145/E-commerce-Customer-Analysis-using-ML/tree/main
