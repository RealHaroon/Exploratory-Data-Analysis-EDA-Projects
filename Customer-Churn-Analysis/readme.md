
# 📊 Telco Customer Churn – Exploratory Data Analysis (EDA)

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the **Telco Customer Churn dataset** to understand customer behavior and identify key factors contributing to customer churn.

The analysis focuses on **data understanding, visualization, and business insights**, without applying machine learning models.

---

## 🔍 Problem Statement
Customer churn is a major challenge for telecom companies, as acquiring new customers is significantly more expensive than retaining existing ones.

The objective of this project is to:
- Analyze customer churn patterns
- Identify high-risk customer segments
- Provide actionable business insights to reduce churn

---

## 📂 Dataset Overview
- **Rows:** 7,043 customers  
- **Columns:** 21 features  
- **Target Variable:** `Churn` (Yes / No)

### Feature Types
- **Numerical Features:**  
  - `tenure`, `MonthlyCharges`, `TotalCharges`
- **Categorical Features:**  
  - Gender, Contract, PaymentMethod, InternetService, OnlineSecurity, TechSupport, etc.
- **Identifier Column:**  
  - `customerID`

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – data visualization
- **Jupyter Notebook**

---

## 📊 EDA Workflow

### Phase 0: Problem Understanding
- Defined churn and its business impact
- Identified analysis objectives

### Phase 1: Data Overview & Cleaning
- Checked dataset structure and data types
- Handled incorrect data types (`TotalCharges`)
- Verified duplicates and missing values

### Phase 2: Target Variable Analysis
- Analyzed churn distribution
- Found **~26.5% churn rate**, indicating a significant business concern

### Phase 3: Univariate Analysis
- Analyzed individual categorical and numerical features
- Identified customer composition and service usage patterns

### Phase 4: Bivariate Analysis (Feature vs Churn)
Identified key churn drivers:
- Month-to-month contracts
- High monthly charges
- Low tenure customers
- Electronic check payment method
- Lack of online security and tech support
- Fiber optic internet users

### Phase 5: Correlation Analysis
- Examined relationships between numerical features and churn
- Confirmed:
  - Negative correlation between tenure and churn
  - Positive correlation between monthly charges and churn

### Phase 6: Business Insights & Recommendations
Translated analytical findings into actionable business strategies.

---

## ⭐ Key Insights
- **26.5% of customers churned**, highlighting a major retention issue
- Month-to-month contract customers churn significantly more
- New customers are more likely to churn than long-term customers
- Higher monthly charges increase churn likelihood
- Customers using electronic checks have higher churn
- Customers without value-added services (Online Security, Tech Support) churn more

---

## 💡 Business Recommendations
- Improve early-stage customer engagement
- Encourage long-term contracts with incentives
- Introduce personalized pricing strategies
- Promote automatic payment methods
- Bundle value-added services with internet plans
- Improve fiber optic service quality

---

## 🚀 Future Work
- Feature engineering and preprocessing
- Machine learning model for churn prediction
- Model evaluation and performance comparison

---

## 📌 Conclusion
This EDA project provides a comprehensive understanding of customer churn behavior in the telecom domain. The insights derived can help businesses design targeted retention strategies and improve customer lifetime value.

---

## 📎 Author
**Haroon**  
Aspiring Data Analyst / Data Scientist  

---

⭐ *If you find this project useful, feel free to star the repository!*

