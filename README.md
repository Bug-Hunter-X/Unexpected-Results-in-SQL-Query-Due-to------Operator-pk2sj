# SQL Query Bug: Unexpected Salary Threshold Handling

This repository demonstrates a common SQL query error where using the '>' operator without considering edge cases can lead to unexpected results.

The `bug.sql` file contains a query that intends to select employees from the Sales department with salaries greater than 100000. However, it excludes employees with salaries exactly equal to 100000.

The `bugSolution.sql` file provides a corrected query that addresses the issue using the '>=' operator, ensuring that all employees with salaries greater than or equal to 100000 are included.