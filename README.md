# Product-Pricing-Optimization

This project focuses on optimizing product pricing using regression-based machine learning techniques and demand analysis. Using a modified e-commerce dataset, we built predictive models to forecast optimal pricing, maximize product demand, and boost revenue for retail businesses.

---

## Overview

- Objective: To predict product prices and identify optimal pricing strategies using machine learning.
- Dataset: Modified version of the [Olist Store Brazilian E-commerce Dataset](https://www.kaggle.com/datasets/gaurichaudhari9/olist-store-modified-dataset)
- Records: 100K+ entries across 8 CSV files with 40 features.
- Tools Used: Python (Pandas, NumPy, Scikit-learn), Power BI for visualization.

---

## Project Workflow

1. **Data Consolidation**  
   - Integrated 8 CSV files (customers, sellers, products, orders, payments, etc.) using Python libraries like Pandas and NumPy.
   - Cleaned and merged data into a unified dataset for modeling.

2. **Dimensionality Reduction**  
   - Applied **Principal Component Analysis (PCA)** to reduce dimensionality from 40 to 17 features, improving model performance.

3. **Model Building & Evaluation**  
   - Implemented and compared:
     - Linear Regression
     - Ridge Regression
     - Lasso Regression  
   - Achieved RMSE:
     - Linear: **2.795**
     - Ridge: **2.793**
     - Lasso: **2.73** (best)

4. **Demand Curve & Price Optimization**  
   - Focused on **Health & Beauty** product category.
   - Used Power BI and Python to perform demand curve analysis.
   - Identified optimal price of **$39.84** predicting **341+ units** in sales.

---

## Key Features & Tools

- **Languages & Libraries:** Python (Pandas, NumPy, Matplotlib, Scikit-learn)
- **ML Techniques:** PCA, Linear, Ridge, and Lasso Regression
- **Visualization:** Power BI (Sales vs Price, Demand Curve)
- **Focus Domain:** Retail, E-commerce pricing strategy

---

## Evaluation & Outcome

- **RMSE Scores:**  
  - Linear: 2.795  
  - Ridge: 2.793  
  - Lasso: 2.73

- **Impact Analysis:**  
  - Optimal price at $39.84 led to predicted sales growth of **45%**.
  - Revenue projected to grow by approximately **78%**.

---

## Conclusion

This project demonstrates the power of machine learning in price optimization:
- Enabled revenue forecasting using data-driven pricing models.
- Used PCA to reduce feature complexity while retaining performance.
- Provided actionable business insights through demand curve visualization.
- Highlighted how fine-tuning pricing strategies can significantly influence product demand and sales.
