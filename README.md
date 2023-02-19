# SQL Glossary


|SELECT | extracts data from a database|
| ----- | -----|
|SELECT * FROM BaseName | extracts ALL from base|
|SELECT someColumn, oneMoreColumn FROM BaseName| extracts two column from base |
|SELECT (someAction) AS newNameColumn FROM someBase | Do some action and show result at new column|

.
.
.

|INSERT INTO | inserts new data into a database|
| -----| -----|
|INSERT INTO nameOfBase (someColumn, secondColumn, oneMoreColumn) <br> VALUES ('forSome', 'forSecond', 'ForMore'); | Example|
|INSERT INTO table_name <br>VALUES (value1, value2, value3, ...);|If you are adding values FOR ALL <br> the columns of the table, you do not need to <br> specify the column names in the SQL query.|


|UPDATE | updates data in a database|
|DELETE | deletes data from a database|

|CREATE DATABASE | creates a new database|
|ALTER DATABASE | modifies a database|
|CREATE TABLE | creates a new table|
|ALTER TABLE | modifies a table|
|DROP TABLE | deletes a table|
|CREATE INDEX | creates an index (search key)|
|DROP INDEX | deletes an index|
