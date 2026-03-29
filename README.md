# 📊 SQL Learning & Practice

This repository captures my hands-on learning and practice with SQL from LeetCode, focusing on real-world problem solving and data analysis scenarios.

https://leetcode.com/studyplan/top-sql-50/

## 🚀 Key Concepts Learned

### 🔹 Data Selection & Filtering
- `DISTINCT` → Used to retrieve unique values from a column  
- `NULL` handling → Represents unknown values and cannot be compared using `=` or `<>`  
- `HAVING` → Filters grouped data after `GROUP BY`

---

### 🔹 Joins & Data Combination
- Understanding different types of joins:
  - `INNER JOIN`
  - `LEFT JOIN`
  - `RIGHT JOIN`
  - `CROSS JOIN`
- Applying appropriate join conditions for accurate results

---

### 🔹 Aggregation Functions
- `COUNT(*)` → Counts all rows (including NULLs)  
- `COUNT(1)` → Also counts all rows efficiently  
- `AVG()` → Used with `IFNULL` to handle NULL values in calculations  

---

### 🔹 Date Functions
- `DATE_ADD()` → Add interval to a date  
- `DATEDIFF()` → Find difference between dates  
- `DATE_FORMAT()` → Format date values (e.g., `'%Y-%m'`)  
- `INTERVAL` → Used with date functions for dynamic calculations  

---

### 🔹 String Functions
- `LEFT()`, `RIGHT()` → Extract characters from a string  
- `UPPER()`, `LOWER()` → Case transformation  
- `CONCAT()` → Combine multiple strings  
- `SUBSTRING()` → Extract part of a string  

---

### 🔹 Advanced Querying
- Subqueries & derived tables (must always have aliases)  
- Window functions for advanced analytics  
- Conditional logic using `CASE` statements  
- Handling odd/even values using `%` operator  

---

### 🔹 Window Functions
- Used for ranking and analytics:
  - `ROW_NUMBER()`
  - `RANK()`
  - `DENSE_RANK()`
- Partitioning data using `PARTITION BY` for group-wise calculations  

---

### 🔹 Pattern Matching & Regular Expressions
- Regex patterns for validation and filtering:
  - `^` → starts with  
  - `$` → ends with  
  - `\d` → digits  
  - `(?=.*...)` → positive lookahead  
  - `{n}` → exact length  
- `REGEXP_LIKE()` → Modern MySQL regex function  

---

💡 Key Takeaways
Learned how to write efficient and optimized SQL queries
Applied SQL concepts to solve real-world data problems
Strengthened understanding of data aggregation, transformation, and analysis
Gained experience with MySQL functions, joins, and window functions

🎯 Purpose
This repository reflects my continuous learning journey in SQL and data analytics.
It demonstrates my ability to:
Analyze data effectively
Write clean and optimized queries
Solve business problems using SQL
