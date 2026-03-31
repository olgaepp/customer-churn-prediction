# customer-churn-prediction
Customer churn prediction with business-driven insights.
# Customer Churn Prediction (Telecom)

## 📌 Project Overview

This project analyzes and predicts customer churn using a telecom dataset. The goal is not only to identify customers likely to churn, but also to support business decision-making through interpretable models and value-based prioritization.

---

## 🎯 Objectives

* Understand key drivers of customer churn
* Build and compare predictive models
* Optimize the decision threshold based on business needs
* Prioritize customers using Customer Lifetime Value (CLTV)

---

## 📊 Dataset

* Source: IBM Telco Customer Churn dataset (Kaggle) https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/code?datasetId=1020460&language=Python

* Includes customer demographics, services, contract details, and billing information

---

Step 1. EDA.
Step 2. Feature selection & engineering (columns´dropping, encoding, new features).
Step 3. Train/test split (stratified).
Step 4. Scale numeric features.
Step 5. Check/Handle class imbalance.
Step 6. Model selection and Training.
Step 7. Model evaluation.
Step 8. Hyperparameter tuning (model optimization).
Step 9. Feature Importance & SHAP.
Step 10. Upscaling (risk classification, campaign suggestion)
Step 11.Business Recommendations.

---

## 📈 Key Results

* ROC-AUC ≈ 0.83–0.85 across models
* Recall ≈ 80% (strong churn detection)
* Precision ≈ 50% (trade-off for higher recall)
* Logistic Regression selected for its interpretability and competitive performance

---

## 🔍 Key Insights

* Churn is strongly linked to:

  * Low tenure (early-stage customers)
  * High monthly charges
  * Lack of long-term contracts
* Model performance suggests largely linear relationships in the data
* A significant group of “borderline” customers can be influenced through targeted actions

---

## 💼 Business Value

* Identifies high-risk customers before churn occurs
* Enables targeted retention strategies
* Incorporates CLTV to prioritize high-value customers
* Supports cost-effective decision-making through threshold optimization

---

## 🚀 Next Steps

* Profit-based optimization (cost vs retention value)
* Customer segmentation and targeted campaigns
* A/B testing of retention strategies

---

## 🛠️ Tools & Libraries

* Python (Pandas, NumPy, Scikit-learn)
* XGBoost
* SHAP (model interpretability)
* Matplotlib / Seaborn



This project emphasizes the transition from predictive modeling to business decision-making, demonstrating how machine learning can be applied in a practical, real-world context.
