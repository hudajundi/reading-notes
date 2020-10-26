# Reading notes
## SQL 
### Introduction to SQL
SQL *Structured Query Language* is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.
* **SQL syntax:** To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries.
* **Queries with constraints** : use a WHERE clause in the query. The clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.
* **Filtering and sorting Query results** : SQL provides a convenient way to discard rows that have a duplicate column value by using the DISTINCT keyword.
* **Multi-table queries with JOINs**: Using the JOIN clause in a query, we can combine row data across two separate tables using this unique key. The first of the joins that we will introduce is the INNER JOIN.The INNER JOIN is a process that matches rows from the first table and the second table which have the same key (as defined by the ON constraint) to create a result row with the combined columns from both tables. After the tables are joined, the other clauses we learned previously are then applied.
* **OUTER JOINs** :two tables have asymmetric data, which can easily happen when data is entered in different stages, then we would have to use a LEFT JOIN, RIGHT JOIN or FULL JOIN instead to ensure that the data you need is not left out of the results.
* **A short note on NULLs**: It's always good to reduce the possibility of NULL values in databases because they require special attention when constructing queries, constraints (certain functions behave differently with null values) and when processing the results.

An alternative to NULL values in your database is to have data-type appropriate default values, like 0 for numerical data, empty strings for text data, etc. But if your database needs to store incomplete data, then NULL values can be appropriate if the default values will skew later analysis (for example, when taking averages of numerical data).


### SQL Statement:
**SELECT * FROM Customers;**