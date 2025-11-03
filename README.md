# MySQL-Queries-Notes

1. Write a query to output all the columns from the Products table.

Table name: Products

answer: SELECT \* FROM Products;

2. Write a query to find all product_name and category that have a price greater than 100.00 from the Products table.

Table name: Products

answer: SELECT product_name, category FROM Products WHERE price > 100;

3. Write a query to calculate the average salary across all companies combined. Rename the column as avg_salary.
   Table name: Works

answer: SELECT AVG(salary) AS avg_salary FROM Works;

4. Write a query to retrieve the department_name and location of people who live in location that starts with 'S'.
   Table name: departments

answer: SELECT department_name, location FROM departments WHERE location LIKE 'S%';

5. Write a query to select all the distinct companies (company_name) in the Works table. (Removing a same company name twice in table ex: tcs: salary 1000, tcs: salary 2000)
   Table name: Works

answer: SELECT DISTINCT company_name FROM Works;

6. Write a query to find the total count of books whose genre is Fiction.
   Note: Output column name should be fiction_count.

answer: SELECT COUNT(\*) AS fiction_count FROM Books WHERE genre = 'FICTION';

7. List of Movies with Ratings
   Task
   Write a query to select only the movie names where the ratings are greater than 7 but less than 9.

Table: Cinema

answer: SELECT Movie_name from Cinema WHERE Rating > 7 AND Rating < 9 ;
