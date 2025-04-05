# 📚 SQL Learning Notes – Manipulation Section

Welcome to my notes from the **Manipulation** section of Codecademy’s *Learn SQL* course! This section covered six essential SQL commands used to manage data stored in relational databases.

---

## 🛠️ What is SQL?

> **SQL (Structured Query Language)** is a programming language used to manage and manipulate **relational databases**.

- A **relational database** organizes information into **tables** (rows and columns).
- A **table** is a collection of data.
  - Each **row** is a record (e.g., a customer).
  - Each **column** is a field or attribute (e.g., name, birthdate).
- A **statement** is a SQL command recognized by the database (e.g., `SELECT`, `INSERT`, `UPDATE`, etc.).

---

## 📊 SQL Manipulation Commands

| Command          | Description                          | Example |
|------------------|--------------------------------------|---------|
| `CREATE TABLE`   | Creates a new table                  | `CREATE TABLE Movies (...);` |
| `INSERT INTO`    | Adds new rows to a table             | `INSERT INTO Movies VALUES (...);` |
| `SELECT`         | Queries/retrieves data from a table  | `SELECT * FROM Movies;` |
| `ALTER TABLE`    | Modifies an existing table structure | `ALTER TABLE Movies ADD COLUMN Genre;` |
| `UPDATE`         | Edits an existing row in a table     | `UPDATE Movies SET Title = 'Up' WHERE ID = 1;` |
| `DELETE FROM`    | Deletes rows from a table            | `DELETE FROM Movies WHERE ID = 1;` |

---

## 🔐 Constraints

**Constraints** are rules added to a column to ensure data integrity:

- `NOT NULL` – column must have a value  
- `UNIQUE` – all values in the column must be different  
- `CHECK` – sets a rule for acceptable values (e.g., `CHECK (Height > 10.0)`)  
- `PRIMARY KEY` – uniquely identifies each row  
- `FOREIGN KEY` – links to a primary key in another table

---

## ✅ Summary of What I Learned

- How to **create** tables and define data types
- How to **insert** new data into tables
- How to **update**, **alter**, and **delete** data
- How to apply **constraints** to enforce data integrity

---

## 🚀 What's Next?

Next up is learning how to **retrieve and filter** data using commands like:

- `WHERE`, `AND`, `OR`
- `ORDER BY`
- `LIMIT`
- `GROUP BY`
- `HAVING`

Stay tuned!

---

👩‍💻 *Built with love while studying for the DP-900 & mastering SQL basics.*

