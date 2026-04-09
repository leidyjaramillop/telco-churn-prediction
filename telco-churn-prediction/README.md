# 📊 Telco Customer Churn Prediction

## 📌 Project Overview

Customer churn is a critical challenge for subscription-based companies. This project aims to predict which customers are likely to churn using machine learning techniques and generate actionable business insights to improve customer retention.

---

## 🎯 Business Objective

Identify customers at risk of churn and understand the key drivers behind customer attrition.

---

## 📊 Dataset

Telco Customer Churn Dataset

* 7043 customers
* 21 features
* Binary classification (Churn: Yes / No)

---

## 🧠 Methodology

This project follows the CRISP-DM methodology:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Business Recommendations

---

## 📊 Churn Distribution

![Churn Distribution](images/churn_distribution.png)

The dataset shows class imbalance, which motivated the use of SMOTE to improve model performance.

---

## 🔍 Correlation Matrix

![Correlation Matrix](images/correlation_matrix.png)

### Key Insights

* Customers with longer tenure churn less
* Long-term contracts reduce churn
* Higher monthly charges increase churn risk
* Customers with tech support churn less

---

## 🤖 Models Used

* Logistic Regression (Baseline)
* Random Forest
* Random Forest + SMOTE
* Random Forest + Hyperparameter Tuning (Final Model)

---

## 📈 Feature Importance

![Feature Importance](images/feature_importance.png)

Top drivers of churn:

* Tenure
* Contract Type
* Monthly Charges
* Tech Support
* Online Security

---

## 🎯 Final Model Performance

![Confusion Matrix](images/confusion_matrix.png)

### Interpretation

* The model correctly identifies many customers at risk of churn
* Some false positives exist, but this is acceptable in churn prediction
* The model prioritizes identifying at-risk customers early

This approach is useful for proactive retention strategies.

---

## 💡 Business Recommendations

Based on model insights:

* Focus retention strategies on new customers
* Promote long-term contracts
* Offer technical support packages
* Review pricing strategies for high monthly charges
* Identify high-risk customers early
* Implement proactive retention campaigns

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* SMOTE

---

## 📁 Project Structure

```
telco-churn-prediction  
│  
├── notebook  
├── data  
├── images  
├── README.md  
└── requirements.txt  
```

---

## 🚀 Business Impact

This model helps companies:

* Reduce churn
* Increase customer retention
* Improve revenue
* Identify at-risk customers

---

## 👩‍💻 Author

Leidy Jaramillo
Data Science Project

