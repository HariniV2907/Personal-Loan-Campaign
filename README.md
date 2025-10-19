# 💰 Personal Loan Campaign Project

## 📄 Project Overview
AllLife Bank is a leading U.S. bank with a large and growing customer base. Most customers are **liability customers (depositors)**, while only a small portion are **asset customers (borrowers)**.  
To expand its loan business, the bank aims to identify existing deposit customers who are most likely to take personal loans.  

This project builds a **predictive machine learning model** to identify such customers and provides insights for **targeted marketing campaigns**.

---

## 🎯 Objective
To analyze customer data and build a predictive model that helps the marketing team:
- Identify potential customers who are likely to accept a personal loan offer.
- Understand the most influential customer attributes driving loan purchases.
- Recommend customer segments for focused marketing efforts to increase campaign success.

---

## 📊 Dataset Description
**File:** `Loan_Modelling.csv`

| Column Name | Description |
|--------------|-------------|
| `ID` | Unique Customer ID |
| `Age` | Customer’s age in completed years |
| `Experience` | Years of professional experience |
| `Income` | Annual income (in thousand dollars) |
| `ZIP Code` | Customer’s residential ZIP code |
| `Family` | Family size of the customer |
| `CCAvg` | Average monthly credit card spending (in thousand dollars) |
| `Education` | 1: Undergrad, 2: Graduate, 3: Advanced/Professional |
| `Mortgage` | Value of house mortgage (in thousand dollars) |
| `Personal_Loan` | Target variable — accepted the personal loan (1) or not (0) |
| `Securities_Account` | Has a securities account (1 = Yes, 0 = No) |
| `CD_Account` | Has a certificate of deposit (CD) account (1 = Yes, 0 = No) |
| `Online` | Uses internet banking (1 = Yes, 0 = No) |
| `CreditCard` | Uses a credit card from another bank (1 = Yes, 0 = No) |

---

## 🧠 Key Analysis Performed
- Data cleaning, preprocessing, and feature engineering.  
- Exploratory Data Analysis (EDA) to understand relationships between customer attributes and loan acceptance.  
- Visualization of key trends (income, education, family size, online usage, etc.).  
- Feature selection and model training using **classification algorithms**.  
- Evaluation using metrics such as **accuracy, precision, recall, F1-score, and ROC-AUC**.  
- Identification of significant variables driving loan acceptance.

---

## 📈 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- **Google Colab**  
- **HTML Report Generation:** `Personal_Loan_Campaign_Week2_Project.html`

---

## 📂 Project Structure
- `Loan_Modelling.csv` — Dataset  
- `Personal_Loan_Campaign_Week2_Project.html` — Project report

---

## 🔍 Insights Summary
- Customers with **higher income** and **higher education levels** showed a greater likelihood of taking loans.  
- Customers who **use online banking** and **hold CD accounts** were more responsive to loan offers.  
- **Credit card spending (CCAvg)** and **family size** were significant behavioral indicators.  
- A well-defined segment of customers can be targeted to improve the **conversion rate beyond 9%** achieved in the previous campaign.

---

## 🏁 Conclusion
**The predictive model helps AllLife Bank:**
- Identify and prioritize high-potential customers for loan marketing.  
- Design personalized offers for specific customer groups.  
- Improve marketing efficiency and return on investment (ROI).  
- Strengthen the bank’s overall cross-selling strategy while retaining deposit customers.

