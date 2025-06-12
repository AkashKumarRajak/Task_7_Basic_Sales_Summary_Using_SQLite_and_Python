# Task_7_Basic_Sales_Summary_Using_SQLite_and_Python

---

**Internship**: Data Analyst Intern  
**Company**: Elevate Labs  
**Submitted By**: Akash Kumar Rajak  
**Date**: June 2025

---

## Objective

The objective of this task is to demonstrate how to query a local SQLite database using Python and extract simple sales metrics — total quantity sold and total revenue — and visualize them using a bar chart.

---

## 📁 Dataset & Database

- **Database Name**: `sales_data.db`
- **Table Used**: `sales`
- **Fields**:
  - `product`: Name of the product
  - `quantity`: Quantity sold
  - `price`: Unit price of the product

---

## Tools & Libraries

- Python (3.x)
- SQLite (via `sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook / `.py` script

---

## SQL Query Used

```sql
SELECT 
    product, 
    SUM(quantity) AS total_qty, 
    ROUND(SUM(quantity * price), 2) AS revenue 
FROM sales 
GROUP BY product;
```
---

## Visualization
A simple bar chart was created using matplotlib to show revenue by product.
Sales_chart.png (included in repo)

---

## 📂 Files Included

File Name	Description:

`Task-7_Basic_Sales_Summary_Using_SQLite_&_Python.ipynb`:	Jupyter Notebook version (optional)
`sales_data.db`:	SQLite database 
`sales_chart.png`:	Bar chart showing revenue by product

---

## Outcome

This task demonstrates how to:

- Create and query a local SQLite database
- Execute SQL queries from Python
- Load SQL results into Pandas
- Print and visualize simple business metrics using bar charts

---

## Contact

- Akash Kumar Rajak
- Email Id: akashkumarrajak200@gmail.com
- LinkedIn: https://www.linkedin.com/in/akash-kumar-rajak-22a98623b/com

