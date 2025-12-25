# 📊 SQL Case Study — Product & Sales Analysis Using SQL

## 📌 Project Overview
This project contains 29 structured SQL queries written for a product sales case study.  
The goal is to extract business insights such as sales performance, profitability, state-wise contribution, product-wise trends, and expense evaluation.  
The queries demonstrate SQL concepts including:
- Joins
- Aggregate functions
- Window functions
- Stored procedures
- User-defined functions
- Conditional statements
- ROLLUP for hierarchical aggregation
- Transactions with rollback
- UNION & INTERSECT operations

This project represents my ability to solve real business problems using SQL.

---

## 🛠 Tools & Technologies
- Microsoft SQL Server (SSMS)
- SQL

---

## 📁 Database Schema

| Table | Description |
|--------|-------------|
| `fact` | Contains sales, profit, marketing, expenses, inventory & productId |
| `product` | Contains product name, type & category |
| `location` | Contains area code and state information |

---

## 🔍 Key Insights Extracted
- Total and average sales per product
- State-wise profit & sales distribution
- Marketing cost and expense analysis
- Profit/loss based on business condition
- Ranking products by sales
- Category based product listing
- Increase in sales forecasting (+5% case)

---

## 📈 Highlight Queries

### 🥇 1. Display minimum sales
```sql
SELECT MIN(sales) AS min_sales FROM fact;
