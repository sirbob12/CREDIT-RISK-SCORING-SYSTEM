# 💳 Credit Risk Scoring System

## 📌 Overview
This project builds an **end-to-end credit risk scoring system** that predicts the probability of default (PD) and simulates real-world lending decisions.

The system is designed to reflect how modern fintech companies make **data-driven credit decisions**, balancing **risk control and profitability**.

---

## 🎯 Objectives
- Predict **Probability of Default (PD)** using machine learning  
- Convert predictions into a **credit scoring system (300–850)**  
- Segment customers into **risk bands**  
- Simulate **loan approval decisions**  
- Optimize decision thresholds to **maximize profit**  
- Provide **model explainability using SHAP**

---

## 📊 Dataset
This project uses the **German Credit Dataset**, a widely used benchmark dataset for credit risk modeling.

- Source: UCI Machine Learning Repository / Kaggle  
- Contains customer financial and demographic attributes  
- Target variable:
  - `0` → Non-default (Good customer)  
  - `1` → Default (Bad customer)  

---

## ⚙️ Project Structure


## 🧠 Methodology

### 1. Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Standardized features  

### 2. Feature Engineering
- Created **credit burden (loan amount / duration)**  
- Derived financial stability indicators  
- Transformed categorical features  

### 3. Model Development
- Logistic Regression model (industry standard for credit scoring)  
- Trained on processed dataset  

### 4. Model Evaluation
- Metric: **ROC-AUC**
- Achieved performance:
  - **ROC-AUC ≈ 0.77**

---

## 💳 Credit Scoring System
Predicted probabilities are transformed into a **credit score range (300–850)**:

- Higher score → Lower risk  
- Lower score → Higher risk  

---

## 📉 Risk Segmentation

| Score Range | Risk Level |
|------------|-----------|
| 700+       | Low Risk  |
| 600–699    | Medium Risk |
| <600       | High Risk |

---

## ⚖️ Decision Engine
Loan decisions are simulated based on credit scores:

- **APPROVE** → Low-risk customers  
- **REJECT** → High-risk customers  

---

## 💰 Profit Simulation
The system simulates real lending outcomes:

- Profit from performing loans (interest)  
- Loss from defaulted loans  

---

## 🔍 Threshold Optimization
Instead of fixed rules, the model uses **data-driven threshold optimization** to:

- Maximize total profit  
- Balance approval rate and default risk  

---

## 🧾 Model Explainability (SHAP)
SHAP (SHapley Additive exPlanations) is used to:

- Identify **key drivers of default risk**  
- Explain individual predictions  
- Improve transparency in decision-making  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- SHAP  

---

## 🚀 Key Insights
- Credit burden and financial indicators strongly influence default risk  
- Optimizing decision thresholds significantly improves profitability  
- Model explainability is essential for trust in financial systems  

---

## 📌 Future Improvements
- Implement advanced models (XGBoost, LightGBM)  
- Add multi-class decision system (Approve / Review / Reject)  
- Deploy as a web application (Streamlit / API)  
- Incorporate real-time decisioning pipeline  

---

## 🤝 Contribution
Feel free to fork this repository and contribute improvements.

---

## 📬 Contact
**Bob Osho**  
- GitHub: https://github.com/sirbob12  
- LinkedIn: [your link]