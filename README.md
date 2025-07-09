# Telecom Customer Churn Analysis 📊

This project analyzes customer churn data for a telecom company to understand what factors influence whether a customer stays or leaves. Churn is when a customer discontinues their service.

## 🔍 Goal

The main objective is to:
- Explore customer behaviors and service usage patterns
- Identify the key factors that are associated with churn
- Provide actionable insights that could help reduce churn

## 📁 Dataset

The dataset is from IBM Sample Data:
- Rows: 7,043 customers
- Columns: 21 features including demographics, services, charges, and churn label
- File: `data/telecom_churn.csv`

## 🔧 Tools Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook (for analysis)

## 📊 Key Analysis Steps

1. **Data Cleaning**
   - Converted `TotalCharges` to numeric
   - Handled missing values
   - Encoded churn labels for correlation analysis

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn rates by demographic and service usage
   - Analyzed contract types, payment methods, and tenure
   - Used a heatmap to understand correlation between features

## 🔑 Insights

- Churn rate is ~26.5%
- Customers with month-to-month contracts, high monthly charges, or no tech support/security services are more likely to churn
- Tenure has a strong negative correlation with churn — newer customers are more likely to leave
- Long-term contracts and automatic payment methods correlate with lower churn
