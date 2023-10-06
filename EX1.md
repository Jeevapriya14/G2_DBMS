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
create table Studentsdetails(rollno numeric(12),name varchar(20),age numeric(2),address varchar(100),phoneno numeric(10));
```


### OUTPUT:
![Create table](https://github.com/Jeevapriya14/F2_DBMS/assets/121003043/5309e192-aa2c-458e-a94e-c4274deee6e1)



### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table Studentsdetails add dept char(20);
```
### OUTPUT:
https://github.com/Jeevapriya14/F2_DBMS/assets/121003043/ed2e752f-7aa7-4e74-b201-9e583613a692


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table Studentsdetails;
```
### OUTPUT:
![Drop table](https://github.com/Jeevapriya14/F2_DBMS/assets/121003043/d6c40d0f-ca23-4f91-8ddd-65d5df285516)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table Studentsdetails;
```

### OUTPUT:
![Truncate table](https://github.com/Jeevapriya14/F2_DBMS/assets/121003043/af285f67-4c27-4048-98be-2afd893af907)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table Studentsdetails rename to my_student;
```

### OUTPUT:
![Rename table](https://github.com/Jeevapriya14/F2_DBMS/assets/121003043/61cb9cc2-1352-4cf7-a508-94eadfc06a39)
