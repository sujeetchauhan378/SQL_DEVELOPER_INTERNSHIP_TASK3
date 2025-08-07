# SQL_DEVELOPER_INTERNSHIP_TASK3

# 💻 SQL Developer Internship – Task 3

## ✅ Task: Writing Basic SELECT Queries

This task focuses on writing SQL queries to extract and filter data from one or more tables using basic SQL clauses.

---

## 🎯 Objective

- Extract data from tables using `SELECT`, `WHERE`, `ORDER BY`, and `LIMIT`.
- Understand filtering and projection techniques.

---

## 🧰 Tools Used

- DB Browser for SQLite / MySQL Workbench

---

## 📌 SQL Query Examples

```sql
-- 1. Select all columns
SELECT * FROM Employees;

-- 2. Select specific columns
SELECT name, department FROM Employees;

-- 3. Apply WHERE clause
SELECT * FROM Employees WHERE department = 'IT';

-- 4. Use AND / OR
SELECT * FROM Employees WHERE department = 'HR' AND salary > 50000;
SELECT * FROM Employees WHERE department = 'HR' OR department = 'Finance';

-- 5. LIKE operator
SELECT * FROM Employees WHERE name LIKE 'A%';

-- 6. BETWEEN operator
SELECT * FROM Employees WHERE salary BETWEEN 40000 AND 70000;

-- 7. ORDER BY ascending
SELECT * FROM Employees ORDER BY name;

-- 8. ORDER BY descending
SELECT * FROM Employees ORDER BY salary DESC;

-- 9. LIMIT results
SELECT * FROM Employees LIMIT 5;

-- 10. DISTINCT values
SELECT DISTINCT department FROM Employees;

-- 11. Aliasing
SELECT name AS Employee_Name, salary AS Salary_INR FROM Employees;
