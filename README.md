# answers.sql
First Sql Assignment
# 📘 SQL Assignment Submission

## 👩‍💻 Student Info
- **Name:** Ugwuaneke Mercy Eberechukwu
- **Course:** Data base design & programming with SQL
- **Assignment:** SQL Basics – Database Creation & Deletion

---

## 📝 Assignment Description

This assignment demonstrates foundational SQL skills by completing the following tasks using MySQL syntax:

1. **Create a new database** called `salesDB`.
2. **Drop (delete)** an existing database called `demo`.

---

## 📂 Files Included

- **answers.sql**  
  Contains SQL queries for each question with comments for clarity.

---

## ⚙️ How to Run the SQL Queries

1. Open **MySQL Workbench** or another MySQL-compatible environment.
2. Open the `answers.sql` file.
3. Run the statements one at a time, or all together:
   - Make sure to review any warnings before running `DROP DATABASE`.
   - `CREATE DATABASE` will not throw an error if the database already exists (thanks to `IF NOT EXISTS`).
4. You can verify database creation and deletion with:
   ```sql
   SHOW DATABASES;
