# Day 50
__2/18/20__

## In a SQL table, what is the difference between information in a row and information in a column?
Information in a row is information for that one item. Information in a column would be multiple items of that same data type, whether it be id, name, or description.
## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE burgers
(
name VARCHAR(255),
age VARCHAR(255),
description VARCHAR(255),
id INT
## What is the difference between DELETE FROM table_name & DROP TABLE table_name?
DELETE FROM table_name would remove data from a table, it also takes in a conditional. DROP TABLE table_name would delete the entire table, which could cause you loads of issues.