# Customer-churn-project
Predicting customer churn using ML and providing business insights
# Customer Churn Prediction Project

## 📌 Project Overview
This project predicts customer churn for a telecom company using machine learning and provides actionable business insights to reduce churn.  

- **Goal:** Identify customers likely to leave and suggest retention strategies.  
- **Impact:** Helps the company save revenue by targeting high-risk customers.
---

## 💾 Dataset
- Dataset used: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- Contains customer demographics, account info, and service usage.  

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Data Visualization & Dashboard (Optional):** Tableau / Power BI  
- **Deployment (Optional):** Streamlit  

---

## 🔍 Problem Statement
A telecom company wants to predict which customers are likely to churn (leave the service) and identify key factors contributing to churn. The goal is to provide **data-driven strategies** to improve customer retention.

---

## 🧠 Approach / Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values in `TotalCharges`  
   - Converted categorical variables to numeric  
   - Dropped unnecessary columns like `customerID`  

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution  
   - Analyzed correlations between features and churn  
   - Identified patterns like short-tenure customers being at high risk  

3. **Feature Engineering**
   - Created tenure groups  
   - Categorized monthly charges  

4. **Model Building**
   - Logistic Regression (baseline)  
   - Random Forest (best model)  
   - Evaluated using Accuracy, Precision, Recall, and ROC-AUC  

5. **Insights & Feature Importance**
   - Contract type is the most important predictor  
   - Short-tenure and high monthly charges → higher churn probability  

6. **Business Recommendations**
   - Encourage long-term contracts  
   - Offer discounts for high-risk customers  
   - Loyalty rewards for long-term users  
   - Improve onboarding for new customers  
