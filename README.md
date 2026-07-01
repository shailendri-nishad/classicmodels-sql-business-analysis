# ClassicModels SQL Business Analysis

## Project Overview
This project analyzes the **ClassicModels** sample database using SQL to solve real-world business problems. It demonstrates SQL skills commonly used by Data Analysts and Business Analysts, including joins, aggregations, window functions, CTEs, views, and subqueries.

---

# Project Structure

```text
ClassicModels-SQL-Business-Analysis/
│
├── Database/
│   └── 01_mysqlsampledatabase.sql
├── SQL Queries/
│   └── 02_sql_queries.sql
├── Images/
│   └── ER_Diagram.png
├──  Outputs/
└── README.md
```

---

# Database Script

**File:** `Database/01_mysqlsampledatabase.sql`

This script:

- Creates the ClassicModels database
- Creates all required tables
- Defines primary and foreign keys
- Inserts sample business data

### Tables Included

| Table |
|-------|
| customers |
| orders |
| orderdetails |
| products |
| productlines |
| employees |
| offices |
| payments |

---

# SQL Script

**File:** `SQL Queries/02_sql_queries.sql`

The script contains **23 business-oriented SQL queries**.

### Business Problems Solved

| Q# | Business Scenario |
|----|-------------------|
| Q1 | Total Revenue |
| Q2 | Customers by Country |
| Q3 | Monthly Revenue Trend |
| Q4 | Revenue by Country |
| Q5 | Customer Segmentation |
| Q6 | Inactive Customers |
| Q7 | Revenue by Product |
| Q8 | Product Ranking |
| Q9 | Revenue by Product Line |
| Q10 | Employee Performance |
| Q11 | Sales Representative Ranking |
| Q12 | Office Performance |
| Q13 | Top Product in Each Product Line |
| Q14 | Top 3 Customers by Country |
| Q15 | Monthly Revenue Growth |
| Q16 | Average Order Value |
| Q17 | Loyal Customers |
| Q18 | Customer Revenue Contribution |
| Q19 | Employee Hierarchy |
| Q20 | Customers with Cancelled Orders |
| Q21 | Customer & Employee Contact List |
| Q22 | Customer Order Summary View |
| Q23 | Dead Stock Products |

---

# SQL Concepts Covered

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- INNER JOIN
- LEFT JOIN
- SELF JOIN
- EXISTS
- UNION
- CASE
- Aggregate Functions
- Subqueries
- Common Table Expressions (CTEs)
- Views
- Window Functions
  - ROW_NUMBER()
  - DENSE_RANK()
  - LAG()
  - SUM() OVER()
- COALESCE()
- COUNT(DISTINCT)

---

# How to Run

1. Import `mysqlsampledatabase.sql` into MySQL.
2. Open `02_sql_queries.sql`.
3. Execute the queries.
4. Review the results.

---

# Author

**Shailendri Nishad**
[LinkedIn](https://www.linkedin.com/in/shailendri-nishad-59b13027b) · [GitHub](https://github.com/shailendri-nishad)

