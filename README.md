# Sales Data Analysis (MySQL)

## 📌 Overview
This project analyzes an e-commerce sales dataset using MySQL.  
It demonstrates:
- Basic SQL queries (`SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`)
- Subqueries
- Aggregate functions (`SUM`, `AVG`)

## 🗂 Dataset
The dataset contains:
- `InvoiceNo` — Invoice number
- `StockCode` — Product code
- `Description` — Product description
- `Quantity` — Units sold
- `InvoiceDate` — Date & time of purchase
- `UnitPrice` — Price per unit
- `CustomerID` — Customer identifier
- `Country` — Country of customer

## 🛠 SQL Examples

### 1. Select and Filter
```sql
SELECT InvoiceNo, Description, Quantity
FROM sales
WHERE Country = 'United Kingdom' AND Quantity > 5
ORDER BY Quantity DESC;
# sql-query-Task_3-
E-Commerce database
