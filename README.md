# 📊 Customer Churn Analysis & Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

# 📌 Project Overview

Customer retention is one of the biggest challenges for modern businesses. Losing customers directly impacts revenue and growth.

This project develops an end-to-end **Customer Churn Prediction** pipeline using Machine Learning to identify customers who are likely to leave the company. The project includes data preprocessing, exploratory data analysis, feature engineering, model building, evaluation, and business recommendations.

---

# 🎯 Business Problem

The company wants to predict which customers are most likely to churn so that proactive retention strategies can be applied before they leave.

Machine Learning helps businesses:

- Identify high-risk customers
- Improve customer retention
- Reduce revenue loss
- Support data-driven decision making

---

# 📂 Dataset

Dataset contains customer demographic, behavioral, transactional, and satisfaction-related information.

Main features include:

- CustomerID
- Tenure
- Preferred Login Device
- Preferred Payment Mode
- Satisfaction Score
- Cashback Amount
- Complaint Status
- Order Count
- Churn (Target Variable)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

---

# 📈 Project Workflow

## 1. Business Understanding

- Defined business objective
- Identified target variable

## 2. Data Understanding

- Dataset inspection
- Missing value analysis
- Duplicate analysis
- Statistical summary

## 3. Data Cleaning

- Missing value handling
- Duplicate removal
- Data preprocessing

## 4. Exploratory Data Analysis

Performed analysis on:

- Customer Churn Distribution
- Gender vs Churn
- Payment Mode vs Churn
- Login Device vs Churn
- Satisfaction Score
- Complaint Analysis
- Cashback Analysis
- Tenure Analysis
- Correlation Heatmap

## 5. Feature Engineering

- One Hot Encoding
- Feature Scaling
- Train-Test Split

## 6. Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest

## 7. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

## 8. Feature Importance

Random Forest Feature Importance was analyzed to identify the most influential factors affecting customer churn.

---

# 📊 Project Results

✔ Data Cleaning completed

✔ Exploratory Data Analysis performed

✔ Three Machine Learning models trained

✔ Random Forest achieved the highest predictive performance

✔ Feature Importance identified major churn drivers

✔ Business recommendations generated

---

# 💡 Key Business Insights

- Customer tenure significantly influences churn.
- Complaint history increases churn probability.
- Customer satisfaction impacts retention.
- Cashback and engagement improve customer loyalty.
- Random Forest achieved the best overall performance among all evaluated models.

---

# 💼 Business Recommendations

- Improve onboarding for new customers.
- Resolve customer complaints faster.
- Increase customer satisfaction.
- Offer personalized cashback and loyalty rewards.
- Deploy the Random Forest model for churn prediction.

---

# 📁 Project Structure

```
customer-churn-prediction-ml/
│
├── data/
│   ├── ecommerce_churn.csv
│   └── E Commerce Dataset.xlsx
│
├── visuals/
│   ├── churn_distribution.png
│   ├── churn_percentage.png
│   ├── gender_vs_churn.png
│   ├── tenure_distribution.png
│   ├── tenure_vs_churn.png
│   ├── login_device_vs_churn.png
│   ├── payment_mode_vs_churn.png
│   ├── satisfaction_vs_churn.png
│   ├── complaint_vs_churn.png
│   ├── cashback_vs_churn.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── model_accuracy_comparison.png
│   ├── logistic_confusion_matrix.png
│   ├── decision_tree_confusion_matrix.png
│   ├── random_forest_confusion_matrix.png
│   ├── logistic_roc_curve.png
│   ├── decision_tree_roc_curve.png
│   └── random_forest_roc_curve.png
│
├── customer_churn_prediction.ipynb
├── customer_churn_report.txt
├── feature_importance.csv
├── model_comparison.csv
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Future Improvements

- XGBoost and LightGBM implementation
- Hyperparameter tuning
- Cross-validation
- SHAP explainability
- Interactive Power BI dashboard
- Model deployment using Flask/FastAPI

---

# 👨‍💻 Author

**Divyanshu Tiwari**

AI/ML Engineer | Machine Learning | Data Analytics

---

## ⭐ If you found this project useful, don't forget to star the repository.
