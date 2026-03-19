# 📊 Customer Behaviour Analysis Dashboard

## 🚀 Overview
This project focuses on analyzing customer purchasing behavior using **Power BI, SQL, and Python**. The goal is to extract meaningful insights from transactional data and present them through an interactive dashboard to support data-driven decision-making.

---

## 🎯 Objectives
- Analyze customer purchase patterns and trends
- Identify high-value customers and segments
- Evaluate impact of discounts and subscriptions
- Visualize key business KPIs using Power BI

---

## 🛠️ Tech Stack
- **Power BI** – Dashboard & Visualization
- **SQL (PostgreSQL)** – Data querying and analysis
- **Python (Pandas, Jupyter Notebook)** – Data preprocessing and EDA

---

## 📊 Key Features

### 🔹 Dashboard Insights (Power BI)
- Revenue analysis by gender, region, and category
- Customer segmentation (New, Returning, Loyal)
- Sales trends and purchasing patterns
- KPI tracking (Total Revenue, Avg Purchase, Orders)

### 🔹 SQL Analysis
Performed advanced queries including:
- Revenue comparison by gender
- Discount impact analysis
- Top-rated and most purchased products
- Customer segmentation using CASE statements
- Window functions for ranking products

### 🔹 Data Analysis (Python)
- Data cleaning and preprocessing using Pandas
- Exploratory Data Analysis (EDA)
- Trend identification and statistical insights

---

## 📈 Key Insights
- Customers using discounts can still contribute significantly to revenue
- Loyal customers generate higher overall revenue
- Certain product categories dominate sales performance
- Subscription status influences purchasing behavior

---

## 📌 Sample SQL Queries

```sql
-- Revenue by gender
SELECT gender, SUM(purchase_amount) AS revenue
FROM customer
GROUP BY gender;

-- Customer segmentation
CASE 
    WHEN previous_purchases = 1 THEN 'New'
    WHEN previous_purchases BETWEEN 2 AND 10 THEN 'Returning'
    ELSE 'Loyal'
END
```

---

## 📷 Dashboard Preview
<img width="1352" height="740" alt="image" src="https://github.com/user-attachments/assets/42904566-adbb-4351-b199-5d7cc09db9ef" />

<img width="1349" height="737" alt="image" src="https://github.com/user-attachments/assets/63423084-d1a9-4c91-a9e5-831c1626f7fc" />

---

## 💡 Conclusion
This project demonstrates strong skills in data cleaning, analysis, SQL querying, and dashboard development, enabling better understanding of customer behavior and business performance.



