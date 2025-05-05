Healthcare Dataset available at https://www.kaggle.com/datasets/prasad22/healthcare-dataset

This repository showcases SQL skills applied to healthcare data analysis and cleaning using SQLite. Key demonstrated abilities include:
Data Retrieval and Inspection: Writing basic SELECT queries to view and understand data structure and content.
Data Cleaning and Transformation:
Utilizing string functions (LOWER, UPPER, SUBSTR, INSTR, REPLACE, TRIM, ||) for data standardization, specifically for correcting name formats (proper casing) and removing unwanted prefixes (Mr, Mrs, Ms).

Data Aggregation and Grouping:
Employing aggregate functions (COUNT, SUM, AVG) to summarize data.
Using the GROUP BY clause to perform calculations on subsets of data (e.g., counting patients per doctor, summing billing amounts per insurance provider, averaging billing amounts per age group).
Filtering grouped data using the HAVING clause (e.g., identifying doctors with a minimum number of patients).

Data Filtering:
Applying the WHERE clause to select specific rows based on conditions.
Using the IN operator to filter based on a list of values (e.g., selecting data for specific doctors).
Handling missing data using IS NOT NULL.

Conditional Logic: Implementing CASE statements for complex data categorization and comparison (e.g., grouping patients into age ranges, comparing age to an average).

Data Ordering: Sorting results using ORDER BY, including sorting by calculated values and by complex CASE expressions for custom order.

Subqueries: Using subqueries to filter data based on the results of another query (e.g., finding diagnoses for doctors with over a certain number of patients).

Basic Data Type Handling: Working with different data types and using functions like ROUND for numerical formatting.

This code demonstrates practical SQL techniques for cleaning, transforming, aggregating, and analyzing structured data.
