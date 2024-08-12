# Create-table-in-MS-SQL

## Languages and Utilities Used

- **Microsoft SQL**

## Environments Used

- **Windows 11**

## Description
Complete the following exercise:
1. Create a student table. The student table needs to include the following columns:
   - Student ID
   - Student First Name
   - Student Last Name
   - Middle Name
   - City
   - State
   - ZIP Code
   - GPA
2. Use the appropriate data types for each column.
3. Create a Primary Key constraint for the table.
4. Make sure all columns contain either a NULL or NOT NULL constraint.

## SQL Code
```SQL
create table student
(
student_id int primary key,
student_f_name varchar(30) not null,
student_l_name varchar(30) not null,
student_m_name varchar(30) null,
city varchar(30) not null,
state varchar(20) not null,
zip_code varchar(14) not null,
gpa float null
)
```
## Screenshot
<img src="https://i.imgur.com/JDcwXCL.png"/>
Successful code execution.
