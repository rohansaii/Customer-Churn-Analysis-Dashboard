# 📊 Customer Churn Analysis Dashboard – Power BI Project

This project presents an end-to-end **Customer Churn Analysis** using Power BI.  
It includes **data cleaning**, **feature engineering**, **custom DAX measures**, and **interactive dashboards** to uncover key insights behind customer attrition.

---

## 📝 Project Overview

Customer churn is one of the biggest challenges for subscription-based and service industries.  
Using the *Churn Modelling Dataset*, this project identifies **why customers are leaving**, **which segments are most at risk**, and **what business factors drive churn**.

The dashboard is divided into **two analytical pages**:

---

## 📍 Page 1: Churn Overview

This page highlights:
- ✔ **Total Customers**
- ✔ **Total Churned**
- ✔ **Overall Churn Rate**
- ✔ Churn rate comparison across **Geography**, **Age Groups**, and **Gender**
- ✔ **Key Influencers Analysis** explaining top churn drivers

### 🔍 Key Insights
- Customers in **Germany** have the highest churn rate (32%+)
- Age groups **45–64** show significantly higher churn
- Female customers churn slightly more than male customers
- Lower credit score and high product count strongly influence churn

---

## 📍 Page 2: Product & Financial Deep Dive

This page explores:
- ✔ Churn rate by **Number of Products**
- ✔ Churn distribution across **Balance Categories**
- ✔ Relationship between **Estimated Salary** and **Balance** (Scatter Plot)
- ✔ High-churn customer segments using a detailed performance table

### 🔍 Key Insights
- Customers with **3 and 4 products** churn at extremely high rates  
  (82.71% and 100% respectively)
- Zero balance and high balance customers are more likely to churn
- Inactive members and low-tenure customers are also high-risk segments

---

## ⚙️ Data Preparation & Feature Engineering

Performed using **Power Query**:
- Removed unnecessary columns: RowNumber, CustomerId, Surname  
- Created calculated columns:
  - `AgeGroup`
  - `BalanceCategory`
  - `Churn Status`
- Ensured proper data types and cleaned inconsistencies

---

## 🧮 DAX Measures

Key DAX measures used:
- `Total Customers`
- `Total Churned`
- `Churn Rate (%)`
- `Avg Credit Score`
- `Avg Balance`

These measures enable dynamic filtering across slicers and visuals.

---

## 📈 Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- Data Modelling & Visualization  
- Business Insights & Analytical Storytelling

---

## 🗂️ Repository Structure

├── 📄 README.md
├── 📊 PowerBI_Dashboard.pbix # Main Power BI file
├── 📁 Screenshots/ # Dashboard images
└── 📄 Churn_Modelling.csv 

---


---

## 📌 Conclusion

This project demonstrates how Power BI can be used to:
- Understand customer churn behavior
- Identify high-risk customer segments
- Provide actionable business insights
- Support data-driven retention strategies

---

## 📧 Contact

If you’d like to collaborate, discuss analytics projects, or review the dashboard, feel free to reach out!

**Rohan Velagala**  
🔗 [*LinkedIn: linkedin.com/in/rohansaii/]*

