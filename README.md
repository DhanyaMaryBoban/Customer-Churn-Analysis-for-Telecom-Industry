# 📊 Customer Churn Analysis – Telecom Industry

## 🔰 Introduction
This project analyzes customer churn in the telecom industry using **Python (data cleaning and EDA)** and **Power BI (dashboard)**. The objective is to identify churn drivers, highlight high-risk customer segments, and recommend retention strategies.

## 📂 Dataset
Columns include:
- Demographics: gender, senior citizen, partner, dependents
- Services: phone service, multiple lines, internet service, online security, online backup, device protection, tech support, streaming TV, streaming movies
- Financials: monthly charges, total charges, contract type, payment method
- Target: Churn (Yes/No)

  ## 🛠 Tools Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** → Data cleaning & EDA  
- **Power BI** → Interactive dashboard & KPIs

## 🔑 Analyst Questions
1. What is the overall churn rate?  
2. Which customer segments churn more?  
3. Does tenure affect churn?  
4. Which services impact churn?  
5. What financial factors drive churn?  
6. Which payment methods are riskier?  

## 📊 Findings

### 🔢 Numerical Insights
- **Average tenure**: ~2.5 years (≈32.3 months), ranging from brand new to 6 years.  
- **Monthly charges**: The monthly charges vary between 18 to 119 (in dollars).  
- **Total charges**: $19 – $8685, directly dependent on tenure × monthly charges.  

### 👥 Demographics
- 16% of customers are senior citizens.  
- Majority are male.  
- Most customers do not have dependents.  

### 🌐 Services
- Most common internet type: Fiber optic.  
- Majority have phone service.  
- Majority do not subscribe to extra services (security, backup, streaming, tech support).  

### 📑 Contracts & Billing
- Most customers are on **month-to-month contracts**.  
- Majority prefer **paperless billing**.  
- Most common payment method: **Electronic check**.  

## 🔎 Answers to Analyst Questions

1. **Overall churn rate**  
   → 26.5% (≈27% customers left, 73% retained).  

2. **Demographic analysis**  
   - Senior citizens churn more (~42%).  
   - Customers without partners churn ~33% vs ~19.7% with partners.  
   - Customers without dependents churn ~31% vs ~15% with dependents.  
   - Gender is not a significant driver (~26.2% for both).  

3. **Tenure effect**  
   → Long-tenure customers are more loyal than new customers.  

4. **Services impact**  
   → Lack of internet, streaming and tech support correlates with higher churn.  

5. **Financial drivers**  
   - High monthly charges increase churn risk.  
   - Month-to-month contracts carry the highest churn risk.  
   - Two-year contracts show the lowest churn, while one-year contracts fall in between.  

6. **Payment methods**  
   - Electronic check is riskiest.  
   - Auto-pay methods (bank transfer, credit card) are safer.  


## 🎯 Suggestions
- Promote long-term contracts.  
- Offer discounts for high-charge customers.  
- Encourage auto-pay methods.  
- Bundle extra services.  
- Target senior citizens and single customers.  

## 🏁 Conclusion
Churn is influenced by **contracts, payment methods, monthly charges, and service bundles**. Retention strategies focusing on **long-term contracts, auto-pay, and bundled services** can reduce churn and improve loyalty.
  
