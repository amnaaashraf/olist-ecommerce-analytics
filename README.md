# Olist E-Commerce Analytics

End-to-end analytics project on the Brazilian Olist 
E-Commerce dataset (2016–2018), covering data 
cleaning, exploratory analysis, SQL business queries, 
machine learning classification, SHAP explainability, 
and seller revenue impact quantification.

---

## Project Structure

| Notebook | Description |
|---|---|
| 01_data_loading_and_exploration | Data loading, shape, missing values, initial inspection |
| 02_data_cleaning | Deduplication, datetime parsing, null handling |
| 03_eda_business_insights | Business-focused EDA — sales trends, delivery patterns |
| 04_advanced_eda | Advanced visualisations, correlation analysis |
| 05_sql_analysis | SQL-style business queries using pandas |
| 06_ml_regression_classification_shap | Revenue regression, binary review risk classification, DPS feature engineering, SHAP explainability, revenue impact analysis |

---

## Key Findings

- Delivery timing relative to promise is the dominant 
  driver of low review risk (mean SHAP = 0.375)
- XGBoost classifier achieves AUC-ROC = 0.7753 on 
  low review risk prediction
- Novel Delivery Performance Score (DPS) engineered 
  as a composite operational risk index
- 26,339 high-risk orders carry estimated R$ 2.54 
  million in platform revenue exposure

---

## Tools Used
Python | pandas | XGBoost | SHAP | scikit-learn | 
matplotlib | seaborn | SQL | Power BI

---

## Dataset
Brazilian E-Commerce Public Dataset by Olist — 
available on Kaggle:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Author
Amna Ashraf
MS Business Analytics — FAST-NUCES Islamabad
github.com/amnaaashraf
