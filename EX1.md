![image](https://github.com/Sachin-vlr/G2_DBMS/assets/113497666/0ae1008e-fa7c-4659-b53d-2a3cdcbccb2b)# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
```sql
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/G2_DBMS/assets/113497666/fe91cdd8-d569-4dd9-b356-3f159f92ab32)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student add department char(30);
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/G2_DBMS/assets/113497666/3f9ff69e-9429-4783-a2ce-239f3635f301)



### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student;
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/G2_DBMS/assets/113497666/75136d48-5af5-4074-bffe-fad953b38304)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student;
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/G2_DBMS/assets/113497666/66bb1677-4a7e-45ce-875f-709f54b673a2)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to mystudent;
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/G2_DBMS/assets/113497666/67b74f41-f0f5-4129-9f9c-9ec4a85fd24a)

# RESULT:
To create a student database and execute DDL queries using SQL is executed successfully...

