# Task 4: Sorting and Limiting Data using SQL

## 📌 Objective
The objective of this task is to understand how to **sort query results**, **limit output rows**, and **implement pagination** using SQL.  
This task helps interns work with ordered data efficiently, which is critical for real-world applications such as dashboards, reports, and leaderboards.

---

## 🛠 Tools Used
- **Primary Tool:** MySQL Workbench  
- **Alternative:** PostgreSQL  

> Note: SQL syntax used in this task works for both MySQL and PostgreSQL with minimal or no changes.

---

## 🗂 Database Table Used
**Table Name:** `teachers`

### Assumed Schema
```sql
teachers
---------
teacher_id INT
teacher_name VARCHAR(100)
department VARCHAR(50)
salary DECIMAL(10,2)
hiring_date DATE

