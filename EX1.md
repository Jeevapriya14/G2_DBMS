# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:
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
![image](https://github.com/Jeevapriya14/G2_DBMS/assets/121003043/c17b0d45-3675-42bc-9e8a-13ba921724e4)




### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table Studentsdetails add dept char(20);
```
### OUTPUT:
![image](https://github.com/Jeevapriya14/G2_DBMS/assets/121003043/7b3d065f-5628-46ae-b179-c8b039475f6c)



### 3) Drop the student table
 
### SQL QUERY: 
```
drop table Studentsdetails;
```
### OUTPUT:
![image](https://github.com/Jeevapriya14/G2_DBMS/assets/121003043/27bc4aa1-bb89-4c6c-954d-ef7428ef6368)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table Studentsdetails;
```

### OUTPUT:
![image](https://github.com/Jeevapriya14/G2_DBMS/assets/121003043/fc2999e4-a5fb-4c33-b02b-7bb32569705c)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table Studentsdetails rename to my_student;
```

### OUTPUT:
![image](https://github.com/Jeevapriya14/G2_DBMS/assets/121003043/08384aff-c57a-4ded-a3d9-2539a4368808)

