
# Employee–Department SQL Task

## 📌 Description
This repository contains SQL practice queries based on a simple **Employee–Department** schema.  
The task demonstrates database creation, table management, data insertion, and various SQL queries such as selection, filtering, aggregation, and joins.

---

## 📂 Repository Structure
- **queries.sql** → Script file with database, tables, insert statements, and queries  
- **README.md** → Documentation of the task  
- **screenshots/** → Screenshots of tables and sample query outputs (added later)  

---

## 🛠️ Setup Instructions
1. Open your SQL client (e.g., MySQL Workbench or any RDBMS supporting SQL).
2. Run the SQL script:
   ```bash
   mysql < queries.sql
   ```
   or copy–paste the queries into your SQL console.
3. The script will:
   - Create the `practice1` database
   - Create two tables: `employee` and `department`
   - Insert sample data
   - Execute a set of SQL queries for practice

---

## 🔍 Queries Overview
This script includes the following queries:

1. Display all records from the `employee` table  
2. Display only `empname` and `salary` of all employees  
3. Find all employees who belong to the IT department  
4. List employees whose salary is greater than 50,000  
5. Find employees hired before `2020-01-01`  
6. Display employees in descending order of salary  
7. Count total number of employees  
8. Find the average salary of all employees  
9. Find the maximum salary in each department  
10. Find departments having more than one employee  
11. Display employees whose names start with 'A'  
12. Find employees with salary between 45,000 and 60,000  
13. Show department name of each employee (JOIN query)  
14. Find the number of employees in each department  
15. Display all employees, including those without a department (LEFT JOIN)  

---

## 🖼️ Screenshots
*(Screenshots of schema and query outputs will be added here)*

### 1. Employee Table
![Employee Table](screenshots/Employee%20Table.png)

### 2. Department Table
![Department Table](screenshots/Department%20Table.png)


---

## 👨‍💻 Author
- **Name**: Aswani Veerepalli  
- **Task**: SQL Basic Queries Practice  
- **Date**: August 2025
