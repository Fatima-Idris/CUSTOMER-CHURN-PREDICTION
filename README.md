# 📊 Customer Churn Analysis  


<img width="986" height="434" alt="image" src="https://github.com/user-attachments/assets/4e97b17d-dd3a-4561-8780-7c1bfc47a6fe" />



## 🚀 Executive Summary  
This project analyzes **customer churn** using telecom data (7,043 customers). It includes **KPI measurement, regression analysis, key driver identification, segmentation, dashboard design, and retention strategies**. The objective is to turn raw customer data into **actionable insights** that reduce churn and improve retention.  

---

## 📑 Table of Contents  
- [Project Structure](#-project-structure)  
- [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)  
- [Regression Analysis](#-regression-analysis)  
- [Key Drivers of Churn](#-key-drivers-of-churn)  
- [Guides (Analysis Steps)](#-guides-analysis-steps)  
- [Retention Strategy](#-retention-strategy)  
- [Dashboard Layout](#-dashboard-layout)  
- [Tools & Skills](#-tools--skills)  
- [Objective](#-objective)  

---

## 📂 Project Structure  
- **Customer Data** → Raw dataset (demographics, services, contracts, churn status).  
- **KPIs** → Summary metrics on churn and customer behavior.  
- **Pivot Tables** → Segmentation of churn by gender, contract, tenure, and payment method.  
- **Regression Analysis** → Statistical modeling of churn drivers.  
- **Key Drivers** → Factors most associated with churn.  
- **Guides** → Steps taken during the analysis workflow.  
- **Dashboard Layout** → Proposed structure for visual storytelling.  
- **Retention Strategy** → Recommendations to reduce churn.  

---

## 📈 Key Performance Indicators (KPIs)  

| Metric                   | Value      |
|---------------------------|-----------:|
| Total Customers           | 7,043      |
| Total Churned Customers   | 1,869      |
| **Churn Rate**            | **26.54%** |
| Average Monthly Charges   | ₦64.76     |
| Average Tenure (months)   | 32         |

---

## 🔎 Regression Analysis  

**Regression Statistics**

| Metric                  | Value   |
|--------------------------|--------:|
| Multiple R               | 0.5084  |
| R Square                 | 0.2585  |
| Adjusted R Square        | 0.2579  |

➡️ About **25.8% of churn variation** is explained by the regression model.  

**Coefficients**

| Variable        | Coefficient | Direction  | Interpretation |
|-----------------|------------:|------------|----------------|
| Tenure          | -0.00455    | Negative   | Longer tenure reduces churn risk |
| Monthly Charges | +0.00108    | Positive   | Higher charges increase churn likelihood |
| Senior Citizen  | +0.06728    | Positive   | Senior customers more likely to churn |
| Contract (MTM)  | +0.13421    | Positive   | Month-to-month contracts strongly increase churn |

---

## 📌 Key Drivers of Churn  

| Driver             | Impact on Churn |
|--------------------|-----------------|
| Contract Type      | MTM contracts → highest churn risk |
| Tenure             | Shorter tenure → higher churn likelihood |
| Monthly Charges    | Higher charges → higher churn |
| Payment Method     | Electronic check → strong churn association |
| Senior Citizen     | Senior customers → more likely to churn |

---

## 📖 Guides (Analysis Steps)  
1. **Data Cleaning** – Prepared dataset, handled missing values, standardized fields.  
2. **Exploratory Analysis** – Segmentation by gender, tenure, contract, and payment method.  
3. **KPI Tracking** – Created summary metrics for churn, charges, and tenure.  
4. **Regression Modeling** – Measured statistical impact of variables on churn.  
5. **Driver Identification** – Isolated strongest churn predictors.  
6. **Dashboard Layout** – Structured design for KPI and churn visualization.  
7. **Retention Strategy** – Developed recommendations to reduce churn.  

---

## 🛠 Retention Strategy  

| Strategy Area        | Recommendation |
|----------------------|----------------|
| Contract Management  | Move customers from MTM → long-term contracts |
| Loyalty Programs     | Reward tenure milestones to encourage retention |
| Pricing              | Review fiber optic pricing (higher churn risk) |
| Payment Methods      | Reduce reliance on e-checks, provide alternatives |
| Senior Support       | Offer tailored services/support for senior customers |

---

## 📊 Dashboard Layout  
Proposed dashboard components:  
- KPI Cards → Total Customers, Churn Rate, Avg Tenure, Avg Monthly Charges  
- Segmentation Charts → Churn by gender, contract type, payment method  
- Regression & Drivers → Summary of statistical insights  
- Retention Strategy Panel → Recommendations  

 <img width="1801" height="1373" alt="image" src="https://github.com/user-attachments/assets/b165aa7d-23e3-4f1e-a71d-cf31790667e9" />
 

---

## 🛠 Tools & Skills  
- **Excel** → Pivot tables, regression, dashboarding  
- **Data Analysis** → Cleaning, segmentation, statistical modeling  
- **Business Intelligence** → KPI reporting, visualization  
- **Customer Retention Strategy** → Evidence-based recommendations  

---

## 🎯 Objective  
This project demonstrates the ability to **analyze customer churn, design KPIs, build regression models, and recommend actionable strategies**, supporting **data-driven decision-making** in customer retention.
