# 📉 Customer Churn Prediction System
*A complete end-to-end Machine Learning project for predicting customer churn and identifying key factors behind customer attrition.*

---

## 📌 Overview
Customer churn is one of the most critical business problems faced by telecom, fintech, SaaS, and subscription-based companies.  
This project builds a **machine learning model to predict whether a customer will churn** and provides **business insights** to reduce churn.

The project covers:
- Churn prediction
- Feature engineering
- Model training & evaluation
- SHAP explainability
- Business recommendations

---

## 🚀 Key Features
- End-to-end machine learning workflow  
- Clean EDA with visual insights  
- Handling class imbalance using **SMOTE**  
- Multiple ML models tested  
- Best model selection  
- Exported trained model (`pickle`)  

---


---

## 📊 Dataset
The dataset includes customer-level attributes like:

- **Demographics:** gender, age, partner, dependents  
- **Subscription details:** contract type, tenure  
- **Services used:** phone service, internet, security, tech support  
- **Billing details:** monthly charges, total charges  
- **Churn:** *Target variable — Yes/No*  

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights discovered:

- Customers with **month-to-month contracts** churn the most  
- Customers with **high monthly charges** are more likely to churn  
- Customers without **online security / tech support** show high churn  
- Long-tenure customers have significantly lower churn  

Visualizations include:
- Distribution plots  
- Correlation heatmap  
- Bar plots  
- Tenure & charges analysis  

---

## 🛠️ Data Preprocessing
Preprocessing steps:

✔ Handling missing values  
✔ One-hot encoding of categorical features  
✔ Standard scaling of numeric features  
✔ Train-test split  
✔ Class imbalance handling with **SMOTE**  
✔ ML pipeline and ColumnTransformer for clean workflow  

---



## 📈 Evaluation Metrics
The project uses:

- Accuracy  
- Precision  
- Confusion Matrix  


---

## 🔎 Model Explainability (SHAP)
To understand *why customers churn*, SHAP analysis was performed.

Top churn indicators:

- High monthly charges  
- Month-to-month contract  
- Lack of tech support  
- Lack of online security  
- Low customer tenure  

This helps businesses target the right customers.

---

## 💡 Business Recommendations
Based on churn insights:

1. Provide **discounts/loyalty offers** to high-charge customers  
2. Convert **month-to-month** users to yearly plans  
3. Offer bundled **security + support services**  
4. Improve engagement in customers with **low tenure**  
5. Reduce unexpected billing spikes  

---


## Clone the repository
```bash
git clone https://github.com/Rohan-Sahoo/Customer-Churn-Prediction.git
cd customer-churn-prediction




