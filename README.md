# Aggregate Functions and Grouping

## 📌 Objective
The goal of this project is to **summarize and analyze data** using SQL aggregate functions and grouping techniques.  
Key skills practiced:
- Using aggregate functions like `SUM`, `AVG`, `COUNT`, `MAX`, `MIN`
- Grouping records with `GROUP BY`
- Filtering groups using `HAVING`
- Counting distinct values
- Rounding numerical results using `ROUND()`

---

## 🛠 Tools Used
- **MySQL Workbench** – For writing and executing SQL queries  
- **Company Database** – Contains the `Employees` table for practice

---

## 🗂 Table Structure (Employees)
| Column Name   | Data Type      | Description               |
|---------------|----------------|---------------------------|
| emp_id        | INT            | Employee ID (Primary Key) |
| name          | VARCHAR(50)    | Employee Name             |
| department    | VARCHAR(50)    | Department Name           |
| salary        | DECIMAL(10,2)  | Employee Salary           |
| email         | VARCHAR(100)   | Unique Email Address      |
| joining_date  | DATE           | Date of Joining           |

---

## 💻 Key Queries

### 1. Count Total Employees
```sql
SELECT COUNT(*) AS total_employees FROM Employees;
