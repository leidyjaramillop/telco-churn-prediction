# 📊 Telco Customer Churn Prediction

## 📌 Project Overview

Customer churn is a critical problem for subscription-based businesses. This project aims to predict customer churn using machine learning techniques to help companies proactively retain customers.

The model identifies customers at risk of leaving and provides business insights to reduce churn.

---

## 🎯 Business Objective

Predict which customers are likely to churn and identify the key factors driving customer attrition.

---

## 📊 Dataset

Telco Customer Churn Dataset

- 7043 customers
- 21 features
- Binary classification problem (Churn: Yes/No)

---

## 🧠 Methodology

This project follows the **CRISP-DM** methodology:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment (Conceptual)

---

## ⚙️ Data Preparation

- Missing values handling
- Data type corrections
- Feature encoding
- Feature engineering

New features created:

- tenure_group
- is_new_customer

---

## 🤖 Models Used

- Logistic Regression
- Random Forest
- Random Forest + SMOTE
- Random Forest + GridSearchCV

---

## 🎯 Model Evaluation

Best Model: **Random Forest Tuned**

| Metric | Value |
|--------|-------|
| Accuracy | 0.74 |
| Recall (Churn) | 0.76 |
| F1 Score | 0.61 |

The model prioritizes **recall**, ensuring most churn cases are detected.

---

## 📈 Feature Importance

Top factors influencing churn:

- Tenure
- Contract type
- Monthly charges
- Tech support
- Online security

---

## 📊 Business Insights

Key findings:

- New customers are more likely to churn
- Long-term contracts reduce churn
- Customers with tech support churn less
- Higher monthly charges increase churn risk

---

## 🛠 Technologies Used

- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
- SMOTE

---

## 📁 Project Structure

telco-churn-prediction
│
├── notebook
├── data
├── images
├── README.md
└── requirements.txt


---

## 🚀 Business Impact

This model helps companies:

- Identify at-risk customers
- Reduce churn
- Increase revenue
- Improve customer retention

---

## 👩‍💻 Author

Leidy Jaramillo  
Data Science Project
