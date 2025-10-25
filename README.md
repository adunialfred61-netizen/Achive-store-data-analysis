# Achive-store-data-analysis
# 🧾 Sales Performance and Shipping Mode Analysis Using SQLite

## Overview
This project analyzes the *Sample – Superstore2* dataset using **SQL (SQLite)** to explore sales, profit, and operational patterns.  

It identifies high-performing categories, top products, city-level sales trends, and examines whether faster shipping influences total sales.

---

## 🗂️ Dataset
- Source: Sample – Superstore2  
- Key Fields: Category, Sub-Category, Product Name, City, Sales, Quantity, Profit, Ship Mode  
- Tool: SQLite  

---

## 🧠 Objectives
- Summarize sales and profit by category and product  
- Identify top-performing and underperforming products  
- Analyze city-level sales  
- Compute correlation between shipping mode and sales  

---

## ⚙️ SQL Queries
See the `report.pdf` or `queries.sql` file for complete query list:
1. List all tables  
2. View dataset  
3. Aggregate sales by product  
4. Aggregate sales by category  
5. Analyze city and sub-category sales  
6. Count sub-categories  
7. Correlation between ship mode and sales  

---

## 📊 Results Summary

| Category | Total Sales | Total Profit |
|-----------|--------------|---------------|
| Technology | 831,654.03 | 145,454.95 |
| Office Supplies | 719,047.03 | 122,490.80 |
| Furniture | 741,999.80 | 18,451.27 |

- Technology leads in profitability  
- Furniture shows low profit margins despite sales volume  
- Correlation between shipping speed and sales ≈ **0.00548** (no strong link)

---

## 📈 Visuals
- `visuals/citywithsales.png` – City-wise sales distribution  
- `visuals/correlation.png` – Ship mode correlation chart  

---

## 🧩 Tools Used
- SQLite (DB Browser)
- SQL Aggregations, CASE statements, CTEs
- Excel / Python for visualizations  

---

## 💡 Key Insights
- Technology & Office Supplies are top profit contributors  
- Furniture has pricing inefficiencies  
- Shipping speed doesn’t impact sales  
- NYC dominates in total sales  

---

## 🚀 Future Work
- Move dataset to **Google Cloud SQL**
- Build predictive models in **Vertex AI**
- Create a **dashboard** for real-time sales tracking  

---

**Author:**  
**ADUNI**  
*Full Stack Developer | Geospatial & Data Analyst | Future Billionaire*

