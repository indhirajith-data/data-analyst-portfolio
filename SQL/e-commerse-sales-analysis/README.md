E-commerce Sales Analysis using SQL
Project Overview
This project analyzes an e-commerce retail dataset using SQL to identify sales trends, top-performing products, valuable customers, and customer purchasing behaviour.
The goal is to generate meaningful business insights from real-world transactional data.
Dataset
Source: UCI Online Retail Dataset
Original records: 541,909
Table: online_retail_fixed
Database: SQLite
Tools Used
SQL
DB Browser for SQLite
Microsoft Excel
GitHub
Business Questions & Analysis
What is the total sales revenue?
How many cancelled transaction records exist?
Which countries generate the highest revenue?
What are the top 5 countries by sales?
Which products generate the highest revenue?
What are the top 5 products excluding postage?
Who are the top 5 customers by revenue?
Which months generate the highest sales?
Which year generated the highest revenue?
Which year and month combination generated the highest revenue?
How many unique orders were received?
What is the Average Order Value (AOV)?
How many repeat customers does the store have?
Who are the most frequent repeat customers?
Key Results
Metric	Result
Total Revenue	£10,644,560.42
Unique Orders	22,064
Average Order Value	£482.44
Repeat Customers	2,845
Cancelled Transaction Records	9,288
Key Insights
The business generated approximately £10.64 million in revenue.
A total of 22,064 unique non-cancelled orders were identified.
Average revenue per order was approximately £482.44.
2,845 customers placed more than one order.
November 2011 recorded the highest monthly revenue, approximately £1.51 million.
Customer 12748 was the most frequent buyer, placing 210 orders.
SQL Concepts Used
SELECT and WHERE
Aggregate Functions (SUM, COUNT, AVG)
GROUP BY and HAVING
ORDER BY and LIMIT
DISTINCT
Subqueries
LIKE and NULL filtering
String Functions (SUBSTR, INSTR)
Project Files
ecommerce_sales_analysis.sql – SQL queries used for the analysis.
README.md – Project documentation.
screenshots/ – Query outputs and analysis results.
Conclusion
This project demonstrates practical SQL skills in data cleaning considerations, data aggregation, sales analysis, customer segmentation, and extracting business insights from transactional data.
