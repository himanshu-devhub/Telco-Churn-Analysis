# 📊 Telco Customer Churn Analysis

## 📌 Project Objective
This project aims to understand the key drivers behind customer churn in a telecom company and build a logistic regression model to predict which customers are likely to churn. Based on the analysis, actionable business recommendations are provided to reduce churn.

---

## 📁 Dataset Overview

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Records**: 7,043
- **Target Variable**: `Churn` (Yes/No)

Each row represents a customer, and each column contains customer attributes like services subscribed, account information, demographic data, and whether they left the company.

---

## 🛠 Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Excel (for exploratory summaries and business presentation)
- Google Colab
- Git & GitHub

---

## 🔍 Exploratory Data Analysis (EDA)

Key observations from the dataset:

- 🔁 **Contract Type**: Month-to-month customers churn more.
- ⏱️ **Tenure**: Customers with lower tenure are more likely to leave.
- 💰 **MonthlyCharges**: Higher charges slightly increase churn probability.
- 📱 **Internet Service**: Fiber optic users churn more than DSL users.
- 💳 **Payment Method**: Customers paying via electronic check have higher churn rates.

Visualizations: Count plots, boxplots, heatmaps, and bar graphs were used to explore the relationships.

---

## 🤖 Model: Logistic Regression

We built a binary classification model using logistic regression.

### 📉 Data Preprocessing
- Handled missing values in `TotalCharges`
- One-hot encoded categorical variables
- Standardized numerical features
- Split into training and testing sets

### 📈 Model Evaluation
- **Accuracy**: ~80%
- **Precision**: Good separation of churn vs. non-churn customers
- **Metrics Used**: Accuracy, Confusion Matrix, Classification Report

---

## 📊 Business Insights

1. **Promote Long-Term Contracts**: Month-to-month users are more likely to churn.
2. **Tenure-Based Discounts**: Reward loyal users to improve retention.
3. **Switch Payment Channels**: Encourage users to use bank transfer or credit card over electronic checks.
4. **Customer Segmentation**: Target high-risk groups with proactive offers or support.
5. **Improve Onboarding**: New users (low tenure) might need better onboarding and support.

---

## 📁 Project Structure
Telco-Churn-Analysis/
├── churn_data.csv # Dataset
├── notebook.ipynb # Analysis & modeling notebook
└── README.md # Project overview and summary

