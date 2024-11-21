### My SQL
* any collection of related information like phone book,shoppinglist,todo list.facebook user base etc.
* databases can be stores in different ways
* on paper,in your mind,on a computer,comments section etc
*  for example comparing amazon.com and shopping list
### Database Management Systems(DBMS)
* a special software program that helps users create and maintain the database.
* make it easy to manage large amount of information
* handles security
* interacts with software applications.
* for eg taking amazon and DBMS the amazon will interact with DBMS inorder to CREATE ,READ,UPDATE,DELETE INFORMATION ETC.
* amazon is telling database to undergo these
* ### C.R.U.D
* create,read,update,delete
## two types of Databases
#### Relational databases(SQL)
* organise data into one or more tables
* each table has colums and rows
* a unique key identifies each row
* eg: excel
#### Non-Relational (noSQL/not just SQL)
* organize data is anything but a traditional table
### Relational Database management systems(RDBMS)
* help users to create and maintain a relational database
* mySQL,Oracle,postgreSQL,mariaDB,etc
### Structured Query Language (SQL)
* standerdized language for interating with RDBMS
* Used to perform C.R.UD operations as well as administrative task (user management,backup etc)
* used to define tables and structures
* SQL code used on one RDBMS is not always portable to another without modification.
#### Non-Relational Data bases(noSQL/not just SQL)
* eg: mongoDB,dynamoDB,apache cassandra,firebase etc.
* there is no set of language standard.
* implement there own language with crud
### Database Queries
* queries are requests made to the database management system for specific information
* a  google sreach is a query
* as the database structure is become more and more complex it become more difficult to get the speciifc pieces of information we want.
### tables
#### primary key
* basically a attribute which uniquely defines the row in the database
* it can differentiate two rows
* eg: email id,specific no, SSN
#### foreign key 
* stores primary key of a row in another database table
* composite key,surrogate key,natural keys
## SQL Basics
* SQL is actually a hybrib language,basicallly 4 types of languages in one.
* DATA QUERY LANGUAGE(DQL)
* for information
* DATA DEFINITION DATA BASE(DDL)
* used for defining database schemas
* DATA CONTROL LANGUAGE (DCL)
* Used for controllling access to the data in the database
* DATA MANIPULATION LANGUAGE(DML)
* used for inserting,updating and deleting dat from the database.
### QUERY
 * set of instruction given to RDBMS(written in sql) that tell the RDBMS what information you want it to retrieve for you
 * TONS of data in DB
 * often hidden in complex schema
 * SELECT emplyee.name,employee.age
   FROM employee
   WHERE emplyee.salary > 30000;
### creating tables
### SQLZoo
### MySQL fuctions
* CHAR_LENGTH(): Returns the length of a string in characters.
* CONCAT(): Concatenates two or more strings.
* CONCAT_WS(): Concatenates strings with a separator.
* FIELD(): Returns the index of a value in a list.
* FIND_IN_SET(): Returns the position of a string in a list of strings.
* FORMAT(): Formats a number as a string.
* INSERT(): Inserts a substring at a specified position.
* LENGTH(): Returns the length of a string in bytes.
* LOCATE(): Returns the position of a substring.
* REPLACE(): Replaces occurrences of a substring.
*FLOOR(): Rounds a number down.
* ROUND(): Rounds a number to a specified decimal place.
* MOD(): Returns the remainder of a division
* COUNT(): Returns the number of rows.
* SUM(): Calculates the sum of values.
* AVG(): Calculates the average of values.
* MIN(): Returns the minimum value.
* MAX(): Returns the maximum value.
* GROUP_CONCAT(): Concatenates values from a group into a single string.
* KEYWORDS
* CREATE, ALTER, DROP, TRUNCATE
TABLE, DATABASE, INDEX, VIEW
* Data manipulation
*INSERT, UPDATE, DELETE, SELECT
* data quering
* WHERE, GROUP BY, HAVING, ORDER BY, LIMIT
JOIN, INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN
UNION, DISTINCT
* operators
* =, != or <>, <, >, <=, >=
AND, OR, NOT, IN, LIKE, BETWEEN
