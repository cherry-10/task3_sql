# 🛒 Sales Data SQL Analysis Project

This project demonstrates how to analyze sales data using SQL with a variety of tools and techniques — including filtering, aggregation, joins, subqueries, views, and performance optimization using indexes.

---

## 📁 Dataset

The dataset is provided in CSV format: `Sales.csv`  
It includes columns such as:

- `Order ID`
- `Customer Name`
- `Category`
- `Sub Category`
- `City`
- `Order Date`
- `Region`
- `Sales`
- `Discount`
- `Profit`
- `State`

---

## 🛠️ Tools Used

- **SQLite** (for simplicity and offline use)
- You can also run the same queries in **MySQL** or **PostgreSQL**
- [SQLiteOnline.com](https://sqliteonline.com/) (no install needed)

---

## 📊 Features and Analysis

### ✅ Basic Queries
- `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY` operations

### ✅ JOINs
- `INNER JOIN`, `LEFT JOIN`, and simulated `RIGHT JOIN`
- Joined with a mock `regions` table

### ✅ Subqueries
- Example: customers with above-average sales

### ✅ Aggregate Functions
- `SUM()`, `AVG()`, `COUNT()`, etc.

### ✅ Views Created
- `region_sales_summary`
- `top_profitable_customers`
- `category_summary`

### ✅ Indexes for Optimization
- Indexes on `order_date`, `state`, `category` columns
---

