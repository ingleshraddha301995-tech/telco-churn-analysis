# telco-churn-analysis
# Telco Customer Churn Analysis

## Overview
End-to-end churn analysis project for a telecom company 
with 7,043 customers. Built to demonstrate SQL cohort 
analysis, Python EDA, ML prediction, and Tableau dashboarding.

## Live Dashboard
[View on Tableau Public](https://public.tableau.com/app/profile/shraddha.ingle/viz/TelcoCustomerChurnAnalysis_17805194488260/Dashboard1)

## Key Findings
- Month-to-month customers churn at **42.7%** vs just 
  **2.8%** for two-year contracts
- First 3 months are critical — **56.2%** of new customers 
  churn before month 4
- Fiber optic customers churn at **41.9%** vs DSL at **19%**
- **894 critical-risk customers** identified representing 
  **$24,649 MRR** at immediate risk
- ML model achieved **80.7% accuracy** and **0.842 AUC-ROC**

## Business Impact
Targeting the 894 critical-risk customers with retention 
offers could save approximately **$210,000 in annual revenue**

## Tools Used
| Tool | Purpose |
|---|---|
| Python / Pandas | Data cleaning & EDA |
| SQL / SQLite | Cohort analysis |
| Scikit-learn | Churn prediction ML model |
| Matplotlib / Seaborn | Visualizations |
| Tableau Public | Interactive dashboard |

## Project Structure
| File | Description |
|---|---|
| 01_data_exploration.ipynb | Data loading & cleaning |
| 02_sql_analysis.ipynb | SQL cohort queries |
| 03_visualizations.ipynb | EDA charts |
| 04_churn_prediction.ipynb | ML pipeline |
| cohort_analysis.sql | All SQL queries |

## Dataset
[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
7,043 customers, 21 features
