# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE : 04/08/23
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
![image](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/927aa947-4591-478c-96b3-bdc12378e447)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![image](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/5ef29e39-00f4-4f58-a1f8-319c93846c71)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![image](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/d242e227-2914-4221-a82e-11c0b05e4e14)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![image](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/d67e6209-a2f0-45ef-a5c4-1af35f692999)

### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![image](https://github.com/DEVADARSHAN2/G2_DBMS/assets/119432150/c3336980-0d33-4868-b969-d5354bbdf65e)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
