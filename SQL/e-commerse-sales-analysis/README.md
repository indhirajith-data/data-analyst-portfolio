E-commerce Sales Analysis using SQL

1. Project Overview

This project analyzes an e-commerce retail dataset using SQL to identify sales trends, top-performing products, valuable customers, and customer purchasing behaviour.

The goal is to generate meaningful business insights from real-world transactional data.

2. Dataset

- Dataset: UCI Online Retail Dataset
- Source: https://archive.ics.uci.edu/dataset/352/online+retail
- Original Records: 541,909
- Database: SQLite
- Table: online_retail_fixed

3. Tools Used

- SQL
- DB Browser for SQLite
- Microsoft Excel
- GitHub

4. Business Questions

1. What is the total sales revenue?
2. How many cancelled transaction records exist?
3. Which countries generate the highest revenue?
4. What are the top 5 countries by sales?
5. Which products generate the highest revenue?
6. What are the top 5 products excluding postage?
7. Who are the top 5 customers by revenue?
8. Which months generate the highest sales?
9. Which year generated the highest revenue?
10. Which year and month combination generated the highest revenue?
11. How many unique orders were received?
12. What is the Average Order Value (AOV)?
13. How many repeat customers does the store have?
14. Who are the most frequent repeat customers?

5. Key Results

Metric| Result
Total Revenue| £10,644,560.42
Unique Orders| 22,064
Average Order Value| £482.44
Repeat Customers| 2,845
Cancelled Transaction Records| 9,288

6. Key Insights

- The business generated approximately £10.64 million in revenue.
- A total of 22,064 unique non-cancelled orders were identified.
- Average revenue per order was approximately £482.44.
- 2,845 customers placed more than one order.
- November 2011 recorded the highest monthly revenue, approximately £1.51 million.
- Customer 12748 was the most frequent buyer, placing 210 orders.

7. SQL Concepts Used

- SELECT and WHERE
- Aggregate Functions (SUM, COUNT, AVG)
- GROUP BY and HAVING
- ORDER BY and LIMIT
- DISTINCT
- Subqueries
- LIKE and NULL filtering
- String Functions (SUBSTR, INSTR)

8. Project Files

- "ecommerce_sales_analysis.sql" – SQL queries used for the analysis.
- "README.md" – Project documentation.
- "screenshots/" – Query outputs and analysis results.

9. Conclusion

This project demonstrates practical SQL skills in data aggregation, sales analysis, customer segmentation, and extracting meaningful business insights from transactional data.
