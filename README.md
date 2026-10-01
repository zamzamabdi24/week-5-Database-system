# Week 5 Database Assignment – Indexing and Optimization

This repository contains my solutions for the Week 5 database assignment on indexing, user management, and access control in MySQL.

## Objective

- Drop and manage indexes on tables.
- Create database users and assign roles/privileges.
- Apply basic database security measures.
- Practice advanced SQL queries in a realistic context.

## Files

- `answers.sql` – Contains all required SQL statements for the assignment questions.
- `README.md` – This file, providing context and instructions.

## How to Run

1. Connect to your MySQL server (command line, Workbench, or another client).
2. Ensure the `salesDB` database exists, or create it:
   ```sql
   CREATE DATABASE IF NOT EXISTS salesDB;
   ```
3. Run the SQL file:
   ```bash
   mysql -u your_user -p salesDB < answers.sql
   ```
   Or, in a MySQL client, open `answers.sql` and execute its contents.

## Assignment Questions and Answers

All answers are implemented in `answers.sql`. For reference, the questions are:

1. Drop an index named `IdxPhone` from the `customers` table.  
2. Create a user named `bob` with password `S$cu3r3!`, restricted to `localhost`.  
3. Grant the `INSERT` privilege to `bob` on the `salesDB` database.  
4. Change the password for `bob` to `P$55!23`.

## Notes

- Passwords are set exactly as specified: `S$cu3r3!` and `P$55!23`.
- Privileges are granted on `salesDB.*` to match the assignment requirements.
- The script is written to be directly executable by MySQL without manual editing.
