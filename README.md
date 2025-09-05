# SQL Capstone Project – Agents, Customers, Orders

This mini-project showcases SQL fundamentals on a small retail dataset (agents, customers, and orders).  
It includes clean, runnable queries and a report with results.

## Files
- **SQL_Assignment_Queries.sql** — All queries by task (ready to run).
- **SQL_Assignment_Answers.docx** — Portfolio/report with Query + Result per task.
- **SQL_Assignment_Answers.pdf** — Portfolio/report with Query + Result per task.

This mini-project showcases SQL fundamentals on a small retail dataset (agents, customers, and orders).  
It includes clean, runnable queries and a report with results.

## Files
- **SQL_Assignment_Queries.sql** — All queries by task (ready to run).
- **SQL_Assignment_Answers.docx** — Portfolio/report with Query + Result per task.
- **SQL_Assignment_Answers.pdf** — PDF version for easy viewing.
- **Capstone Tasks** — Original task sheet.

## Highlights
- Filtering and conditional logic (`WHERE`, `LIKE`)
- Aggregations (`SUM`, `MIN`, `MAX`, `COUNT`, `DISTINCT`)
- Subqueries (e.g., min/max comparisons)
- Grouping per customer and agent (`GROUP BY`)
- Joins across tables (customers ↔ agents ↔ orders)

## How to Run
1. Open `SQL_Assignment_Queries.sql` in your SQL client (MySQL Workbench, SSMS, pgAdmin, etc.).
2. Point to the database that contains the `agents`, `customer`, and `orders` tables.
3. Execute queries task-by-task to reproduce the results shown in the report.

## Sample Query
```sql
-- Task 8: Total order amount
SELECT SUM(order_amount) AS total_order_amount
FROM orders;

- **Capstone Tasks** — Original task sheet for context.

## Highlights
- Filtering and conditional logic (`WHERE`, `LIKE`)
- Aggregations (`SUM`, `MIN`, `MAX`, `COUNT`, `DISTINCT`)
- Subqueries (e.g., min/max comparisons)
- Grouping per customer and agent (`GROUP BY`)
- Joins across tables (customers ↔ agents ↔ orders)

## How to Run
1. Open `SQL_Assignment_Queries.sql` in your SQL client (MySQL Workbench, SSMS, pgAdmin, etc.).
2. Point to the database that contains the `agents`, `customer`, and `orders` tables.
3. Execute queries task-by-task to reproduce the results shown in the report.

## Sample Query
```sql
-- Task 8: Total order amount
SELECT SUM(order_amount) AS total_order_amount
FROM orders;
