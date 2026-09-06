# Customer Churn & Revenue Retention Analysis

## 📌 Project Overview

An end-to-end Data Analytics and Business Analysis project analyzing customer churn patterns and revenue risk using Microsoft Excel and Power BI.

The project analyzes **7,043 customer records** to identify high-risk customer segments, understand churn drivers, quantify revenue at risk, and provide actionable customer retention recommendations.

---

## 🎯 Business Problem

Customer churn directly impacts recurring revenue.

This project answers:

- What is the overall churn rate?
- Which customer segments have the highest churn?
- How does churn vary by contract type and tenure?
- Which services and payment methods are associated with higher churn?
- How much monthly revenue is at risk due to churn?
- What retention actions could reduce customer attrition?

---

## 🛠️ Tools Used

### Microsoft Excel
- Data Cleaning
- Data Quality Validation
- KPI Analysis
- Churn Segmentation
- Exploratory Data Analysis

### Power BI
- Interactive Dashboard
- DAX Measures
- KPI Visualization
- Churn Analysis
- Revenue Risk Analysis
- Interactive Slicers

---

## 📊 Dataset

- **Dataset:** Telco Customer Churn
- **Customer Records:** 7,043
- **Columns:** 21
- **Target Variable:** Churn

---

## 📈 Key KPIs

| KPI | Result |
|---|---:|
| Total Customers | 7,043 |
| Churned Customers | 1,869 |
| Active Customers | 5,174 |
| Overall Churn Rate | 26.54% |
| Monthly Revenue | 456,116.60 |
| Monthly Revenue at Risk | 139,130.85 |
| Average Monthly Charge | 64.76 |
| Average Tenure | 32.37 months |

---

## 🔍 Key Insights

- **26.54% of customers churned**, representing 1,869 out of 7,043 customers.
- **Month-to-month customers had the highest churn rate (42.71%)**, compared with one-year and two-year contract customers.
- Customers with **0–12 months of tenure had the highest churn rate (47.44%)**.
- **Fiber optic customers showed elevated churn (41.89%)**.
- **Electronic check users had the highest churn rate among payment methods (45.29%)**.
- Customers **without Tech Support had significantly higher churn (41.64%)**.
- Approximately **139,130.85 in monthly revenue is at risk** due to churned customers.

---

## 💡 Business Recommendations

1. **Improve early-tenure retention** through onboarding and proactive engagement programs.
2. **Encourage suitable customers toward longer-term contracts** using targeted incentives.
3. **Investigate the fiber optic customer experience** for service, pricing, and support issues.
4. **Review the electronic-check customer journey** and potential payment-related friction.
5. **Promote Tech Support and proactive assistance** to reduce customer attrition.

---

## 📊 Power BI Dashboard

The dashboard includes:

### KPIs
- Total Customers
- Churned Customers
- Churn Rate
- Monthly Revenue
- Revenue at Risk

### Interactive Analysis
- Churn Rate by Contract
- Churn Rate by Tenure
- Churned Customers by Contract
- Churned Customers by Internet Service
- Revenue at Risk by Contract
- Revenue at Risk by Internet Service

### Interactive Filters
- Contract
- Internet Service
- Payment Method
- Churn Status

---

## 🧹 Data Preparation

Data preparation was performed in Microsoft Excel.

Key steps included:

- Validating 7,043 customer records and 21 columns
- Checking duplicate and missing customer IDs
- Identifying and handling missing `TotalCharges` values
- Converting `TotalCharges` into a valid numeric field
- Reviewing categorical values for inconsistencies
- Creating analytical segments for churn analysis

---

## 🔄 Analysis Workflow

**Raw Data → Data Cleaning → Data Validation → KPI Analysis → Customer Segmentation → Power BI Dashboard → Business Insights → Recommendations**

---

## 📁 Project Structure

```text
customer-churn-retention-analysis/
│
├── Data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── Excel_Analysis/
│   └── churn_analysis_working.xlsx
│
├── PowerBI/
│   └── Customer_Churn_Revenue_Analysis.pbix
│
├── Dashboard/
│   ├── Customer_Churn_Dashboard.pdf
│   └── dashboard.png
│
├── Documentation/
│   └── Customer_Churn_Analysis_Project.docx
│
└── README.md
