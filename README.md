# Online Retail Customer Segmentation using RFM Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Optional-red)

## 📌 Project Overview

This project performs an end-to-end **RFM (Recency, Frequency, Monetary)** analysis on the Online Retail dataset to segment customers based on their purchasing behavior.  

The goal is to identify high-value customers, understand revenue concentration, and provide actionable marketing recommendations that can help improve customer retention and lifetime value.

**Dataset**: UCI Online Retail Dataset (transactional data from a UK-based online gift retailer)

---

## 🗂️ Dataset Information

- **Source**: [https://www.kaggle.com/datasets/ishanshrivastava28/tata-online-retail-dataset?resource=download]
- **Time Period**: December 2010 – December 2011 (subset used)
- **Original Shape**: 247,211 rows × 8 columns
- **Key Features**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🛠️ Project Workflow

1. **Data Ingestion & Initial Inspection**
2. **Data Cleaning & Preprocessing**
   - Removed missing CustomerIDs
   - Filtered out cancelled orders and invalid transactions
   - Created TotalPrice feature
3. **RFM Feature Engineering**
   - Recency, Frequency, and Monetary calculation
4. **Customer Scoring & Segmentation**
   - Quartile-based RFM scoring
   - Business-meaningful segments (Champions, Loyal Customers, At Risk, etc.)
5. **Exploratory Data Analysis & Visualizations**
6. **Business Insights & Recommendations**

---

## 📊 Key Insights

- A small group of **Champions** and **Loyal Customers** generate a large share of total revenue (Pareto principle).
- Significant opportunity exists in **reactivating At Risk and Hibernating customers**.
- New Customers show potential but need nurturing to increase purchase frequency.
- Revenue is heavily concentrated in the United Kingdom.

---

## 🎯 Business Recommendations

| Segment               | Strategy                          |
|-----------------------|-----------------------------------|
| Champions             | Reward & Retain                   |
| Loyal Customers       | Upsell & Cross-sell               |
| Potential Loyalists   | Increase Engagement               |
| New Customers         | Convert to Repeat Buyers          |
| At Risk               | Win-back Campaigns                |
| Hibernating           | Reactivate or Reduce Spend        |

---

## 🧰 Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Optional**: Scikit-learn (for K-Means clustering)

