# Sales-Performance-Analysis-Portfolio
End-to-end sales data analysis project using Excel and SQL, Includes data cleaning, KPI analysis, interactive dashboard, and business insights across products, regions and time.

# 📊 Sales Performance Analysis

## 📌 Project Overview
This project analyzes sales performance across multiple states, product categories, and time periods to uncover key insights and support data-driven decision-making.

---

## 🎯 Business Problem
A retail business wants to understand revenue performance across products, regions, and time to improve profitability and strategic planning.

---

## 🧰 Tools Used
- Excel (Data Cleaning, Pivot Tables, Dashboard)
- SQL (Data Querying & Analysis)
- SQLite (Database Management)

---

## 📂 Dataset
- 12,000+ sales records
- 5 states (Abuja, Lagos, Kano, Rivers, Enugu)
- Multiple product categories

---

## 🔧 Data Cleaning
- Converted raw data into structured table format
- Removed duplicates and inconsistencies
- Verified revenue calculations
- Created derived columns (Month, Year)

---

## 📊 Analysis Performed
- Total Revenue & Quantity
- Revenue by Category
- Revenue by State
- Monthly Sales Trends
- Top Performing Products

---

## 📈 Dashboard
![Dashboard](images/dashboard.png)

---

## 💻 SQL Analysis
Example query:

```sql
SELECT Category, SUM(Revenue) AS revenue
FROM clean_sales_data
GROUP BY Category
ORDER BY revenue DESC;
