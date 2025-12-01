This assignment demonstrates the creation of two relational tables and the application of various SQL time functions and analytical window functions. The goal is to understand how SQL processes data using ranking, partitioning, and date/time manipulation functions commonly used in real-world data analysis.

1. Tables Used

Employees Table

Contains employee details such as Employee ID, Name, Department, Salary, and Joining Date.
It is used to perform ranking, partitioning, and date-based calculations.

Orders Table

Contains order-related information including Order ID, Employee ID, Order Amount, and Order Date.
It is primarily used to apply time extraction functions.

2. SQL Functions Demonstrated

Time & Date Functions

Functions such as `TIME()`, `DAY()`, `MONTH()`, `YEAR()`, and `DATE_ADD()` are applied on *OrderDate* and *JoinDate* to extract or add time intervals.

Window Functions

Several analytical functions are used to analyze employee salary and joining data:

ROW_NUMBER() – Assigns a unique rank to each employee based on salary.
RANK() – Provides ranking with gaps for duplicate salary values.
DENSE_RANK() – Similar to Rank but without gaps.
PARTITION BY – Groups data by department and evaluates rank within each department.
FIRST_VALUE() – Identifies the first employee who joined in each department.
PERCENT_RANK() – Computes the relative rank of employees’ salaries.

3. Output Flow

1. Display full Employees table
2. Display full Orders table
3. Apply all time functions
4. Apply all ranking and window functions

Conclusion

This assignment demonstrates essential SQL analytical tools that are widely used in reporting, business intelligence, and database querying. The examples help build a strong foundation in date-time handling and window function analysis.

---
If you want, I can also format this as **PDF** for submission.
