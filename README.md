# Sql-4th-task

# 📄 README: SQL Aggregation and Grouping

This document explains how aggregate functions, grouping, and filtering grouped data are applied in SQL using the `students` table.


# ✅ 1. Apply Aggregate Functions on Numeric Columns

Aggregate functions perform calculations on a set of numeric values and return a single result.
Common aggregate functions include:

`COUNT()` – returns the number of rows. `SUM()` – calculates the total sum of a column.
`AVG()` – computes the average value.
`MIN()` and `MAX()` – find the smallest and largest values.

These functions help summarize data such as the average age of students or the total number of entries.



# ✅ 2. Use GROUP BY to Categorize

The `GROUP BY` clause is used to arrange identical data into groups.
It is often used with aggregate functions to perform calculations for each group separately.
For example, grouping books by assigned student ID and counting how many books each student has.



# ✅ 3. Filter Groups Using HAVING

While `WHERE` filters rows before grouping, the `HAVING` clause filters groups after aggregation.
It is used to specify conditions on aggregate values.
For example, displaying only those students who have more than one book assigned.
