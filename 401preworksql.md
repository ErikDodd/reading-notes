# Code 401 - Pre-work - Intro to SQL


## What is SQL?

- **SQL (Structured Query Language)**: A search language used to access information stored in a database. It allows you to query, manipulate, and transform data from a relational database.

- **Relational Database**: a collection of two-dimensional related tables. Contains named columns and rows of different types of data. Similar to an excel spreadsheet.

## Different concepts in SQL

- **SELECT**: Used to retrieve data from a SQL database. Also called 'queries'.

- Example: SELECT title FROM movies;

- **WHERE**: Used to write conditions that allow you to filter for only specific data from certain columns.

- Example:
    SELECT column, another_column, …
    FROM mytable
    WHERE condition
        AND/OR another_condition
        AND/OR …;

- **DISTINCT**: Allows you to discard rows where there are duplicate column values.

- Example:
    SELECT DISTINCT column, another_column, …
    FROM mytable
    WHERE condition(s);

- **ORDER BY**: Allows you to sort the results of your query by focusing on a specific column. You can sort by **ascending(ASC)** or **descending(DESC)**.

- Example:
    SELECT column, another_column, …
    FROM mytable
    WHERE condition(s)
    ORDER BY column ASC/DESC;

- **LIMIT**: Allows you to reduce the total amount of data returned by limiting the number of rows/results you query for.

- Example:
    LIMIT num_limit;

- **OFFSET**: Allows you to choose where to start where to begin counting the number of rows you want to query from.

- Example:
    OFFSET num_offset;

- **JOIN**: Allows you to merge data from separate rows in separate tables.

- **INNER JOIN**: Allows you to match rows from separate tables and return results that contains combined columns from both tables.

-**SCHEMA**: This describes the structure of the table and what datatypes can be entered in each column.

-**INSERT**: Allows you to insert new data into a database. Specifcy which table to add the data to, the columns of data to add, and also rows of data to insert.

- Example:
    INSERT INTO boxoffice
    (movie_id, rating, sales_in_millions)
    VALUES (1, 9.9, 283742034 / 1000000);

- **UPDATE**: Allows you to make changes to existing data in table.

- Example:
    UPDATE mytable
    SET column = value_or_expr,
        other_column = another_value_or_expr,
        …
    WHERE condition;

- **DELETE**: Allows you to remove data from a table. Be sure to utilize the **WHERE** clause to specifiy which rows of delete. If you don't include the WHERE clause you simple delete the whole table.

- Example:
    DELETE FROM mytable
    WHERE condition;

- **CREATE TABLE**: Allows you to create a new database table.

- Example:
    CREATE TABLE movies (
    id INTEGER PRIMARY KEY,
    title TEXT,
    director TEXT,
    year INTEGER,
    length_minutes INTEGER
);

- **ALTER TABLE**: Allows you to adjust tables and the database schema. You can add, remove, modify columns. Removing columns is **DROP** and. renaming columns is **RENAME TO**

- Example:
    ALTER TABLE mytable
    ADD column DataType OptionalTableConstraint
    DEFAULT default_value;

- Example: 
    ALTER TABLE mytable
   DROP column_to_be_deleted;

- Example:

    ALTER TABLE mytable
    RENAME TO new_table_name;
