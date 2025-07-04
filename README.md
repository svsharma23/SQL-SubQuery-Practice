# 🧠 SQL Subquery Practice — 21 Realistic Questions

This project contains 21 practice SQL queries written using PostgreSQL, focused on mastering different types of subqueries. The questions are based on a realistic `customers` and `orders` dataset and aim to strengthen core SQL querying skills through hands-on practice.

---

## 📋 Dataset Overview

Two sample tables were used:

### 📦 `customers`
| Column       | Type          |
|--------------|---------------|
| customer_id  | SERIAL (PK)   |
| name         | VARCHAR(100)  |
| city         | VARCHAR(50)   |
| age          | INT           |
| status       | VARCHAR(20)   |

### 📦 `orders`
| Column       | Type          |
|--------------|---------------|
| order_id     | SERIAL (PK)   |
| customer_id  | INT (FK)      |
| order_date   | DATE          |
| amount       | INT           |
| status       | VARCHAR(20)   |

---

## 🔍 Topics Covered

- ✅ Scalar Subqueries (single value)
- ✅ Row Subqueries (multi-column comparison)
- ✅ Subqueries in `SELECT` clause
- ✅ Subqueries in `WHERE` clause
- ✅ Table Subqueries / Inline Views
- ✅ Combining Subqueries with Joins

---

## ✨ Key Concepts Practiced

- Filtering with scalar comparisons: `=`, `<`, `>`, `IN`, `NOT IN`
- Aggregation inside subqueries: `AVG()`, `SUM()`, `COUNT()`, `MIN()`, `MAX()`
- Writing subqueries inside `SELECT` and `FROM`
- Using subqueries in real-world logic like:
  - Top spenders
  - Customers with no orders
  - Matching city/status/age
  - Order counts per customer

---

## 📁 Files Included

| File Name              | Description                             |
|------------------------|-----------------------------------------|
| `create_tables`        | Schema + insert statements              |
| `SQL subquery practice`| All 21 questions with answers + comments|
| `README.md`            | Documentation                           |

---

## 🧠 What I Learned

This project helped me:
- Understand how subqueries behave in different clauses
- Practice breaking queries into logical steps
- Build confidence working with SQL joins + subqueries
- Prepare for SQL-based data analyst interviews

---

## 🛠 Environment

- PostgreSQL
- Tested in pgAdmin and local PostgreSQL CLI

---

## 📌 Author

**Vaibhav Sharma**  
[LinkedIn] ((https://www.linkedin.com/in/svsharma23/)) 
[GitHub]   (https://github.com/svsharma23)

---
