🍕Pizza Sales Analysis Using SQL

📌 Project Overview

This project focuses on analyzing pizza sales data using SQL to identify sales trends, customer ordering patterns, popular pizza types, and 
revenue performance.
The analysis uses four related tables: orders, order_details, pizzas, and pizza_types. 
SQL queries are used to answer key business questions and derive insights that can support data-driven business decisions.

🎯 Objectives
- Analyze overall order volume and revenue.
- Identify the most popular and highest-revenue pizza types.
- Evaluate pizza category performance.
- Understand ordering patterns by hour and date.
- Analyze revenue contribution and cumulative revenue trends.

🗂️ Dataset Description

The dataset contains four tables:

order -- Contains order IDs, order dates, and order times.
order_details -- Contains order detail IDs, order IDs, pizza IDs, and quantities.
pizzas -- Contains pizza IDs, pizza type IDs, sizes, and prices.
pizza_types -- Contains pizza type IDs, names, categories, and ingredients.

These tables are connected using common identifiers to analyze order quantities, product categories, and sales revenue.

🔍 Business Questions Answered

1. What is the total number of orders placed?
2. What is the total revenue generated from pizza sales?
3. Which pizza has the highest price?
4. Which pizza is ordered most frequently?
5. What are the top five most-ordered pizza types by quantity?
6. What is the total quantity ordered for each pizza category?
7. How are orders distributed across different hours of the day?
8. What is the average number of pizzas ordered per day?
9. Which are the top three pizza types by revenue?
10. What percentage of total revenue does each pizza type contribute?
11. How does cumulative revenue change over time?
12. What are the top three revenue-generating pizza types within each pizza category?

🛠️ Tools & Technologies

- SQL — Data querying,aggregation ,subqueries, joins, filtering, and analysis.
- SQL Notebook — Writing and executing queries.
  

📊 Key SQL Concepts Used

- Aggregate functions: SUM(), COUNT(), AVG()
- Joins across multiple tables
- GROUP BY and ORDER BY
- Filtering and conditional logic
- Subqueries
- Window functions for cumulative revenue and ranking

💡 Business Value

This analysis can help a pizza business understand its 
best-selling products, 
revenue-generating pizza types, 
category-wise demand,
and peak ordering hours. 
These insights can support inventory planning, product decisions, and sales strategy.

📁 Project Structure
- EDA-Pizza-Sales-SQL.sql — SQL analysis notebook containing the business questions and queries.

🚀 Conclusion
This project demonstrates the use of SQL to explore relational sales data, answer business questions, and 
derive insights into product performance, revenue, and ordering trends.
