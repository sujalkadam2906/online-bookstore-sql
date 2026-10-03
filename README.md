# Online Bookstore SQL Project

## Overview
A PostgreSQL-based SQL project designed to
manage and analyze an online bookstore database.
This project focuses on database design,
data retrieval, sales analysis, and customer
purchasing patterns.

## Technologies Used
- PostgreSQL
- SQL
- VS Code
- Git and GitHub

## Database Tables
- **Books:** Stores book details such as
  title, author, genre, price, and stock.
- **Customers:** Stores customer information
  such as name, email, city, and country.
- **Orders:** Stores order details, customer IDs,
  book IDs, quantities, and total amounts.

## SQL Concepts Practiced
- Database and table creation
- Primary and foreign keys
- CSV data import
- SELECT, WHERE, ORDER BY, LIMIT
- Aggregate functions (SUM, AVG, COUNT)
- INNER JOIN and LEFT JOIN
- GROUP BY and HAVING
- DISTINCT and BETWEEN
- COALESCE

## Business Questions
- Retrieve books by genre and publication year.
- Calculate total book stock and revenue.
- Identify customers with multiple orders.
- Find the most frequently ordered books.
- Analyze sales by genre and author.
- Identify high-spending customers.

## How to Run
1. Install PostgreSQL.
2. Create the OnlineBookstore database.
3. Create the required tables using the SQL script.
4. Import the CSV datasets into the respective tables.
5. Run the queries in `online_bookstore.sql`
   using pgAdmin or psql.

## Author
Sujal Sunil Kadam