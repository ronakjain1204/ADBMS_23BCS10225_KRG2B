# EXP 2:

Welcome to the EXP_2 folder of my Advanced Database Management Systems (ADBMS) Lab work, prepared by **Ronak Jain (UID: 23BCS10225)**.

## 📋 Overview

This experiment explores advanced SQL concepts:
- *Self-joins* to model real-world hierarchies (employee-manager relationships).
- Robust handling of missing values in *financial reporting queries* using outer joins and default substitution.

The scripts, queries, and sample outputs reflect practical problem-solving for enterprise and financial data scenarios.

## 🎯 Experiment Aim

- **Employee Manager Mapping (Medium Complexity):**
  - Build an `EMPLOYEE_TBL` capturing both employees and their managers (referencing the same table).
  - Use self-joins to map each employee to their manager, displaying employee/manager department details side by side.

- **Net Present Value Querying (Hard Level):**
  - Design datasets (`Year_tbl` and `Queries_tbl`) to manage and query financial NPV records for various instrument-years.
  - Implement SQL logic (using `LEFT OUTER JOIN` and value substitution) to ensure missing financial data is returned as zero, supporting complete and resilient reporting.

## 🛠️ What’s Implemented?

- **Schema Creation:**
  - Self-referencing `EMPLOYEE_TBL` for employee-manager hierarchy.
  - `Year_tbl` for actual NPV data.
  - `Queries_tbl` for user-queried instrument-year combinations.

- **Data Insertion:**
  - Diverse employee data modeling multi-department reporting chains.
  - Financial instrument NPVs over multiple years.

- **Querying Techniques:**
  - **Self-Join:** Generate a report showing each employee's and their manager’s names and departments.
  - **Left Outer Join & Null Handling:** Retrieve NPVs for requested instruments/years, substituting zero for missing records.

## 👨💻 Key Learnings

- Constructing *self-joins* to represent and query hierarchical relationships (e.g., organizational chart).
- Using *left outer joins* to combine datasets with potential missing data, crucial for reliable reporting.
- Applying `ISNULL()` or equivalent functions for data cleaning in SQL.
- Modelling real-world business requirements (HR hierarchies, financial reporting) with robust relational queries.

## 📜 Files Included

- `Exp2.sql` (**DBMS Script**): Complete DDL/DML and queries for both experiment sections.
- **Sample Outputs**: Expected result snippets for each SQL operation.
- This README to document objectives, design, and key learnings.

## 💡 How to Use

1. Review the provided SQL scripts for database schema, sample inserts, and required queries.
2. Understand the logic behind self-joins for organizational mapping and left joins for financial data retrieval.
3. Experiment by extending with more employee or financial instrument data, adjusting queries as needed to reinforce concepts.
