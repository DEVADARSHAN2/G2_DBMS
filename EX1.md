# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![Screenshot 2023-09-27 082125](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/d0cca452-375f-412a-9b2b-57e305f4c34d)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![Screenshot 2023-09-27 082059](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/006f294a-08c8-4684-b82b-6242a1cc7175)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![Screenshot 2023-09-27 082019](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/1730d860-4614-42f3-8076-55815ca9b0be)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![Screenshot 2023-09-27 081953](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/4b88d6e9-5c7c-46cb-b34e-e55e4456362a)

### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![Screenshot 2023-09-27 081921](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/8e0122a3-76e1-4cda-b700-d334e4f4b49e)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
