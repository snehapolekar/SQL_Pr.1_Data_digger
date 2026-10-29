# Data Digger – SQL Database Project

## 📌 Project Overview
Data Digger is a SQL database project designed to manage customer information, orders, product details, and order details. It demonstrates how a relational database can be created, populated, updated, queried, and maintained using SQL.

## 🎯 Objectives
- Create and use a MySQL database.
- Store customer details and their addresses.
- Manage customer orders and order dates.
- Maintain product prices and stock information.
- Connect related tables using primary keys and foreign keys.
- Retrieve useful information using filtering, sorting, aggregate functions, and joins.

## 🗂️ Database Structure
The project uses the following tables:

### 1. Customers
Stores customer IDs, names, email addresses, and locations.

### 2. Orders
Stores order IDs, the customer associated with each order, order dates, and total amounts.

### 3. Products
Stores product IDs, product names, prices, and available stock.

### 4. OrderDetails
Stores order-detail IDs, the products included in orders, quantities, and subtotals.

## ✨ Key Features
- Database and table creation.
- Sample data insertion.
- Displaying complete table records.
- Updating customer addresses, order amounts, and product prices.
- Deleting selected orders or products.
- Filtering records by customer, date, price range, and stock.
- Sorting products by price.
- Finding maximum, minimum, average, and total values.
- Counting product sales and summarizing quantities by product.
- Joining customer records with orders.
- Joining product records with order details.
- Identifying the most frequently ordered products.

## 🛠️ Technologies Used
- MySQL
- SQL (Structured Query Language)

## ▶️ How to Run
1. Install and open MySQL or a compatible SQL environment.
2. Open the `Data_Digger.SQL` file in your SQL editor.
3. Execute the script using an account that has permission to create databases and tables.
4. The script creates the `data_digger` database and its tables, then inserts sample records and runs example queries.
5. Review the query results in your SQL editor.

**Note:** The script begins by dropping the existing `data_digger` database if it exists. Running it again will delete that database and recreate it, so back up any important data before execution.

## 📚 SQL Concepts Demonstrated
- `CREATE DATABASE` and `USE`
- `CREATE TABLE`
- `INSERT`, `SELECT`, `UPDATE`, and `DELETE`
- Primary keys and foreign keys
- `WHERE`, `BETWEEN`, and `ORDER BY`
- Aggregate functions such as `SUM`, `AVG`, `MIN`, `MAX`, and `COUNT`
- `GROUP BY` and `LIMIT`
- `JOIN`

## 📁 Project File
- `Data_Digger.SQL` — SQL script containing the database setup, sample data, and demonstration queries.

## ✅ Conclusion
Data Digger provides a beginner-friendly example of relational database management with MySQL. It demonstrates how multiple related tables can be organized and how SQL queries can be used to manage data and extract useful information.


## 👩 Connect with me :


Linkedin id : www.linkedin.com/in/sneha-polekar-1a8022415

Gmail id : snehapolekar26@gmail.com



