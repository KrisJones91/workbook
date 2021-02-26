# Day 49
__2/23/20__

## What is the difference between a Primary Key and a Foreign Key?
A Primary Key is a unique piece of data in a table that belongs to a specific column, used to identify a record in the database. A Foreign Key provides a link between data in two tables that refers to the Primary Key of another table.
## What is an Alias?
An Alias is created following the name of a table to condense code. After it is declared it can be used in place of the full name to be able to achieve the same results of using the full name without having to write it all out, which could make the code messy and longer than necessary.
## Demonstrate how you would query a JOIN statement that would get all of the doctors patients (from example)?
SELECT 
do.*,
pa.*,
FROM doctors do,
JOIN patients pa ON do.patientId = pa.id
WHERE id = @id

