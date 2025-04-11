Topics: Power BI DAX, Python & SQL

Power BI (DAX):

1. Write a DAX measure to find the top 5 products based on product color from two tables: 'Product' (columns: 'product_id', 'product_color') and 'Sales' (columns: 'product_id', 'profit').
2. Explain how to implement Row-Level Security (RLS) in Power BI.
3. Describe different types of filters in Power BI.
4. Explain the difference between 'ALL' and 'ALLSELECTED' in DAX.
5. Write a DAX formula to calculate the rolling 12 months of average sales using a 'sales': table with a 'DATE' column, 'product_id' and 'profit' column.

Python:

1. Create a dictionary, add elements to it, modify an element, and then print the dictionary in alphabetical order of keys.
2. Find unique values in a list of assorted numbers and print the count of how many times each value is repeated.
3. Find and print duplicate values in a list of assorted numbers, along with the number of times each value is repeated.
4. Write a function to add two numbers, take input from the user, and handle possible input errors such as non-numeric input and empty input.

SQL:

1. Write a SQL query to see employee name and manager name using a self-join on 'employees' table with columns 'emp_id', 'name', and 'manager_id'.
2. Explain the order of execution of queries

Most Asked SQL Interview Questions:

1. Find the nth highest salary from an employee table.
2. Retrieve duplicate records from a table.
3. Delete duplicate rows while keeping only one copy.
4. Find employees with the highest salary in each department.
5. How do you generate a running total in SQL?
6. How do you find the second maximum value without using LIMIT or TOP?
7. How do you swap values of two columns in a table?
8. Write a SQL query to transpose rows into columns.
9. Write a SQL query to get the cumulative sum of a column.
10. How do you generate random rows from a table?


Can you answer these Python - Pandas interview questions?

These were asked at a top service-based company for Data Analyst role:

Sample DataFrame:

data = {
 'EmployeeID': [1, 2, 3, 4, 5],
 'Name': ['Alice', 'Bob', 'Charlie', 'David', 'Eva'],
 'Department': ['HR', 'IT', 'IT', 'HR', 'Finance'],
 'Salary': [60000, 70000, 80000, 65000, 75000],
 'JoiningDate': ['2020-01-15', '2019-06-20', '2018-07-23', '2020-02-10', '2021-03-15'],
 'PerformanceScore': [3, 4, 2, 5, 3]
}

Interview Questions:

1. How can you calculate the average salary for each department?

2. Write a function to find the employee with the highest performance score in each department.

3. How would you add a new column that represents the number of years each employee has been with the company based on the 'JoiningDate'?

4. Create a pivot table to display the total salary and average performance score for each department.

5. How would you create a new DataFrame containing only the employees from the IT department who have a performance score greater than 3?

6. Describe how to perform an inner merge of this DataFrame with another DataFrame containing employee bonus information based on 'EmployeeID'.

7. How can you calculate the cumulative sum of the 'PerformanceScore' column grouped by 'Department'?

8. Write a function to rank employees within each department based on their 'Salary'.

9. How can you filter the DataFrame to show only employees who have been with the company for more than 2 years?
