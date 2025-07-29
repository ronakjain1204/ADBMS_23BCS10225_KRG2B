# EXP 1:

Welcome to the EXP_1 folder of my Advanced Database Management Systems (ADBMS) Lab work, part of the 5th semester coursework at CSE, prepared by **Ronak Jain (UID: 23BCS10225)**.

## 📋 Overview

This experiment demonstrates foundational and intermediate-level SQL skills: designing relational tables, establishing relationships using keys, and querying relational data using joins, aggregation, and subqueries. The scripts and outputs here reflect my solutions and practical understanding of core database concepts.

## 🎯 Experiment Aim

- **Easy Level:**  
  - Create tables for authors and books, linked with proper relational constraints.
  - Practice inserting data and retrieving combined records using INNER JOIN.

- **Medium Level:**  
  - Design department and course tables with referential integrity.
  - Use GROUP BY, HAVING, and subqueries to analyze and filter departmental offerings.

## 🛠️ What’s Implemented?

- **Schema Creation:**
  - `Authors_tbl` and `Books_tbl` with primary and foreign keys for referential integrity.
  - `Departments_tbl` and `Courses_tbl` for department-course relationships.

- **Data Insertion:**
  - Sample entries for authors (e.g., J.K. Rowling, George R.R. Martin) and books.
  - Populated department and course details (spanning CS, Mechanical, Electrical, etc.).

- **Data Retrieval:**
  - **INNER JOIN** to present combined data (e.g., book titles with author and country).
  - **GROUP BY & HAVING** to find departments offering more than two courses.
  - **Subqueries** for advanced filtering.

## 🧑💻 Key Learnings

- Proper use of **primary and foreign keys** to enforce data consistency.
- Application of **joins** for multi-table queries.
- Usage of **aggregate functions, GROUP BY, HAVING**, and **subqueries** for data analysis.
- Translating real-world scenarios to SQL and relational design.

## 📜 Files Included

- `Exp1.sql` or **DBMS Script:** Step-by-step commands and sample queries.
- **Output:** Sample results shown for each query.
- This README to guide you through the experiment objectives and structure.

## 💡 How to Use

1. Review the SQL scripts for schema design and data population.
2. Understand the queries (with comments) to see how real-world information is retrieved and analyzed.
3. Run the scripts in your SQL environment for practical experimentation.
