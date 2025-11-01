# Telecom Customer Churn Prediction

This project predicts whether a telecom customer is likely to **churn (leave the service)** based on demographic, account, and service-related features.  
It uses machine learning models such as **Random Forest** and **XGBoost** to achieve high accuracy and interpretable insights.

---

## Project Overview

Customer churn is a critical issue for telecom companies. Retaining existing customers is often more cost-effective than acquiring new ones.  
This notebook applies **data preprocessing, exploratory analysis, and predictive modeling** to the popular **Telco Customer Churn dataset**.

---

## Dataset

**Source:** [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

**Dataset features include:**
- Customer demographics (gender, senior citizen, partner, dependents)
- Account information (tenure, contract type, payment method)
- Service usage (internet service, streaming TV, tech support)
- Target variable: `Churn` (Yes / No)

---

## Machine Learning Models Used

1. **Random Forest Classifier**
   - Ensemble of decision trees
   - Captures nonlinear relationships and reduces overfitting
   - Evaluated using confusion matrix and classification report

2. **XGBoost Classifier**
   - Gradient boosting-based ensemble
   - Optimized for performance and interpretability
   - Tuned using train-test split for optimal accuracy

---

## Results and Evaluation

| Model | Accuracy | Key Metrics |
|--------|-----------|-------------|
| Random Forest | ~0.80–0.85 | Balanced precision and recall |
| XGBoost | ~0.85–0.88 | Improved performance and stability |

Visualizations include:
- Correlation heatmaps  
- Churn distribution plots  
- Feature importance charts (via XGBoost and Random Forest)

---
