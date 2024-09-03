# CoffeSQL

# Project Overview
This project is focused on analyzing the sales performance of a coffee shop using SQL queries. The dataset includes transactional data such as sales, orders, quantities sold, product categories, store locations, and time-based information. By executing the queries provided, you can generate insights such as total sales, month-over-month growth, and comparisons of daily and hourly performance. These queries will help in understanding customer behavior and identifying trends to improve business decision-making.

# Prerequisites
Database: The queries are written for an SQL-based relational database management system (RDBMS). You can use MySQL or any other system that supports standard SQL syntax.
Dataset: The table used in these queries is coffee_shop_sales. The dataset must contain the following columns:
transaction_id: Unique identifier for each transaction.
transaction_date: Date of the transaction (in the format DD-MM-YYYY).
transaction_time: Time of the transaction (in the format HH:MM:SS).
unit_price: Price per unit for the product sold.
transaction_qty: Quantity of the product sold in each transaction.
store_location: Location of the store where the transaction took place.
product_category: The category of the product sold.
SQL Queries
# 1. Date and Time Conversion
Converts the transaction_date and transaction_time columns from string formats to proper DATE and TIME data types.
# 2. Total Sales Calculation
Calculates total sales for May by summing the product of unit_price and transaction_qty.
# 3. Month-over-Month Growth Calculation
Calculates month-over-month (MoM) growth for sales between April and May.
# 4. Total Orders Calculation
Counts the total number of transactions (orders) for May.
# 5. Daily Sales Comparison
Compares daily sales in May to the average sales for the month. Classifies days as "Above Average", "Below Average", or "Average".
# . Sales by Location
Displays total sales grouped by store location for May, ordered by highest sales.
# 7. Sales by Product Category
Calculates total sales grouped by product_category for May.
# 8. Sales by Day and Hour
Calculates sales, quantity, and total orders for a specific day and hour (Tuesday at 8 AM) in May.
# How to Use
Prepare the Database: Ensure your database contains the coffee_shop_sales table with the specified columns.
Run the Queries: Use any SQL client or interface that connects to your database (e.g., MySQL Workbench, phpMyAdmin) to run the provided queries.
Analyze the Results: After running the queries, you can analyze the sales, trends, and business insights provided by the output.
# Notes
These queries are specific to the coffee shop dataset and assume that the data follows the given structure.
The MONTH(transaction_date) = 5 filter can be adjusted to analyze different months.
Ensure that date and time formats in the dataset match the formats used in the queries (e.g., %d-%m-%Y for dates).
Author
