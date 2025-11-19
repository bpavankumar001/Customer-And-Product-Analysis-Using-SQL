# Sales & Customer Insights – SQL Project

This project is a MySQL-based sales analytics system designed to analyze customer purchases, product performance, and overall revenue trends. It includes a fully normalized schema, sample dataset, indexing, and multiple analytical SQL queries used to extract meaningful business insights.

---

## 📁 Database Schema

The project contains four normalized tables:

1. **customers**  
2. **products**  
3. **orders**  
4. **order_items**

These tables represent a real-world retail structure where each customer places orders, and each order contains multiple items.

---

## 🧱 Features & Functionality

### ✔ Normalized Schema  
- Separate tables for customers, products, orders, and order_items.  
- Foreign keys to maintain referential integrity.  
- Avoids redundancy and follows 1–Many and Many–Many relationships properly.

### ✔ Indexing  
- Indexes on city, order_date, and customer_id for faster query performance.

### ✔ Sample Dataset  
- 30+ order records  
- 10 customers  
- 6 products  
- Realistic order quantities and dates

### ✔ Analytical Queries  
Includes SQL queries for:

- Top 3 customers by revenue  
- Best-selling products  
- Inactive customers  
- Monthly revenue trend  
- Average order value  
- Total orders per customer

---

## 📘 How to Use

1. Clone or download this repository.  
2. Import the `.sql` files (`customers`, `products`, `orders`, `order_items`) into MySQL.  
3. Run the analytical queries provided to generate insights.  
4. Modify or expand the dataset for practice.

---

## 🛠 Skills Demonstrated

- SQL Joins (INNER JOIN, subqueries)
- GROUP BY, HAVING, ORDER BY
- Aggregate functions (SUM, COUNT, AVG)
- Date-based analysis
- Normalization
- Indexing & query optimization
- Real-world relational schema design

---

## 📸 Optional (Screenshots)

You can add screenshots of:
- Your tables  
- Query outputs  
- ER diagram  

Create a folder called `screenshots/` and upload them.

---

## ⭐ Project Goal

This project was built for strengthening SQL fundamentals, data modeling skills, and analytical query writing—ideal for interviews and real-world use cases.
