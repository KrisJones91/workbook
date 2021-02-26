# Day 49
__2/24/20__

## What is SQL injection?
SQL injection is a type of attack that can give a hacker complete reign over your database. They would be able to insert random info into your database using SQL code.
## What are 3 methods SQL injection can be done by?
User input, modifying cookies and second-order SQL injetion are the three different types. User input is the simplest form due to front-end passing the submitted information to the back-end. In some cases of SQLi, hackers can modify cookies to disrupt the web apps databse query. The most under-the-radar form of SQL is second order. They're designed to run later opposed to immediately.
## How can we detect and sanitize SQL injection attacks?
We can use automated testing tools to be a step ahead of the attacks. We can limit account privilages of the database user,as well as storing procedures so that the web app can run only a select amount of SQL queries that it needs to.