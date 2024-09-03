# CoffeSQL

Project Overview
This project is focused on analyzing the sales performance of a coffee shop using SQL queries. The dataset includes transactional data such as sales, orders, quantities sold, product categories, store locations, and time-based information. By executing the queries provided, you can generate insights such as total sales, month-over-month growth, and comparisons of daily and hourly performance. These queries will help in understanding customer behavior and identifying trends to improve business decision-making.

Prerequisites
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
1. Date and Time Conversion
Converts the transaction_date and transaction_time columns from string formats to proper DATE and TIME data types.
