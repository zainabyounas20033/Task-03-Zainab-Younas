# Task_3_ZainabYounas
# DecodeLabs Internship — Project 3: SQL Data Analysis

## 📌 Overview
This project is part of the **DecodeLabs Data Analytics Internship (Batch 2026)**. The goal was to use SQL to extract insights from an e-commerce orders dataset (1200 records, 14 columns) — covering filtering, grouping, sorting, and aggregation.

## 🛠️ Tools Used
- **DB Browser for SQLite** — for writing and executing SQL queries
- **Microsoft Excel** — for initial dataset conversion (Excel → CSV)

## 📂 Dataset
E-commerce orders dataset containing columns: OrderID, Date, CustomerID, Product, Quantity, UnitPrice, ShippingAddress, PaymentMethod, OrderStatus, TrackingNumber, ItemsInCart, CouponCode, ReferralSource, TotalPrice.

## ✅ SQL Concepts Covered
- `SELECT` — choosing specific columns
- `WHERE` — equality, comparison operators, `AND`, `LIKE` pattern matching
- `GROUP BY` — categorizing rows into buckets
- Aggregations — `COUNT()`, `SUM()`, `AVG()`
- `ORDER BY` — sorting results (ASC/DESC)
- `HAVING` — filtering grouped/aggregated data
- Subqueries — for percentage contribution calculations
## 💡 Key Insights
- **Chair, Printer, and Laptop** are the top 3 revenue-generating product categories, each contributing ~15% of total revenue
- **Credit Card** transactions have the highest average order value
- **180 orders (15%)** exceed Rs. 2000 — a significant high-value order segment
- **53 orders** were both cancelled and paid online — worth investigating further
- Customer **C38840** is the top spender (Rs. 5,723.23)

## 📄 Files in this Repository
- `Project3_SQL_Data_Analysis_Report.docx` — Full report with all SQL queries, explanations, screenshots, and insights
- `Dataset_for_Data_Analytics__3_.csv` — Dataset used for analysis
- Screenshot images — Query execution results from DB Browser for SQLite

## 🔑 Key Learning
Understanding SQL's **logical execution order** (`FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY`) and the difference between row-level filtering (`WHERE`) and group-level filtering (`HAVING`) was the biggest takeaway from this project.

---
*Part of DecodeLabs Data Analytics Internship — Batch 2026*
