# Customer-Sales-Analytics

## Project Overview
This project presents an end-to-end customer analytics pipeline built using Python.  
It transforms raw e-commerce transaction data into actionable insights through:

- Data cleaning & feature engineering  
- Exploratory Data Analysis (EDA)  
- RFM-based customer segmentation  
- K-Means clustering  
- Sales forecasting (SARIMAX)  
- Churn prediction (Logistic Regression & Random Forest)  

The objective is to understand customer behavior, forecast future revenue, and identify customers at risk of churn.

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Statsmodels (SARIMAX)  

---

## Project Workflow

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis  
3. RFM Customer Segmentation  
4. Customer Clustering (K-Means)  
5. Sales Forecasting  
6. Churn Prediction  
7. Business Insights & Recommendations  

---

## Key Findings

### Exploratory Insights
- Sales show clear seasonality and upward growth trends.
- Majority of customers are one-time buyers.
- Late deliveries negatively impact customer satisfaction.
- Revenue distribution is highly skewed — a small portion of customers drive a large share of revenue.

---

### RFM & Customer Segmentation

Customers were segmented using:
- **Recency** (days since last purchase)  
- **Frequency** (number of purchases)  
- **Monetary** (total spending)  

K-Means clustering identified 4 major customer groups:

- High-Spend One-Timers  
- Emerging Loyals  
- Standard Customers  
- Inactive Customers  

**Insight:** A small but valuable customer group contributes disproportionately to revenue, highlighting strong retention opportunities.

---

### Sales Forecasting

Monthly SARIMAX model performance:

- MAPE: ~11%  
- Historical average monthly revenue: ~$670K  
- Forecasted average monthly revenue: ~$1.0M  
- Projected growth rate: ~50%  
- Total 6-month forecast: ~$6.02M  

**Insight:** Revenue shows stable growth with predictable seasonality.

---

### Churn Prediction

- Churn defined as no purchase in last 180 days  
- Overall churn rate: 58.9%  
- Best model: Random Forest  
- ROC-AUC: 0.647  

#### Risk Segmentation:

- High Risk Customers: 31,742  
- Revenue at Risk: ~$4.55M  

High-risk customers are typically inactive, low-frequency buyers with declining engagement.

**Insight:** Targeted retention strategies could significantly reduce revenue loss.

---

## Business Impact

This project enables:

- Targeted churn prevention campaigns  
- Data-driven customer segmentation  
- Revenue forecasting for strategic planning  
- Identification of high-value customers  
- Proactive revenue risk management  

---

## 📌 Conclusion

This project demonstrates how advanced analytics and machine learning can transform transactional data into meaningful business intelligence and strategic decision-making tools.

---
