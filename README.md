# SQL  Glossary


|SELECT | extracts data from a database|
| ----- | -----|
|SELECT * FROM BaseName | extracts ALL from base|
|SELECT someColumn, oneMoreColumn FROM BaseName| extracts two column from base |
|SELECT (someAction) AS newNameColumn FROM someBase | Do some action and show result at new column|
|SELECT COUNT(DISTINCT someThing) FROM Customers; | Count Distinct|

.
.
.

|INSERT INTO | inserts new data into a database|
| -----| -----|
|INSERT INTO nameOfBase (someColumn, secondColumn, oneMoreColumn) <br> VALUES ('forSome', 'forSecond', 'ForMore'); | Example|
|INSERT INTO table_name <br>VALUES (value1, value2, value3, ...);|If you are adding values FOR ALL <br> the columns of the table, you do not need to <br> specify the column names in the SQL query.|


.
.
.

### UPDATE -  updates data in a database EXAMPLE
      UPDATE table_name 
            SET column1 = value1, 
                column2 = value2 
            WHERE condition;


### SOME ACTION
|MIN()| - |
|------| ------|
|MAX()| - |
|SUM()| - |
|AVG()| - |
|COUNT()| - |



### CASE
      SELECT 
        firstname, 
        lastname, 
        salary, 
        CASE 
            WHEN salary <= 1500 THEN salary*0.1
            WHEN salary > 1500 AND salary <= 2000 THEN salary*0.2
            ELSE salary*0.3
        END
        AS tax 
        FROM Employees

        ORDER BY lastname ASC
