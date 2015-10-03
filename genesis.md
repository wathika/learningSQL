##SQL commands

####Glossary of commonly used SQL commands
SQL, 'Structured Query Language', is a programming language designed to manage data stored in relational databases. SQL operates through simple, declarative statements. This keeps data accurate and secure, and helps maintain the integrity of databases, regardless of size.

**Commands**

**CREATE TABLE**
```
CREATE TABLE table_name (
    Column_one datatype,
    Column_two data,
    Colum-three 
);

```

```CREATE TABLE``` creates a new table in the db. Allows to specify the table_name and name of each column.

**SELECT**
```
SELECT * FROM table_name;

SELECT column_name FROM table_name;
```

```SELECT```specifies that the statement is going to be a query that returns unique values in the specified column(s).


**UPDATE**
```
UPDATE table_name
SET some_column = some_value
WHERE some_column = some_value;
```
```UPDATE``` statments allow you to edit rows in a table.


**DELETE**
```
DELETE FROM table_name 
WHERE some_column = some_value;
```
```DELETE``` statements are used to remove rows from a table.