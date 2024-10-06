# MY-LITA-JOURNEY-SO-FAR
## REFRESHING MY MEMORY ON LITA PROJECT

###DATA ANALYSIS OVERVIEW

DATA ANAYSIS HAS TO DO WITH
- GENERATION OF DATA
- DATA TRANSFORMATION (STRUCTURED, SEMI STRUCTURED OR UNSTRUCTURED)

## WAYS TO STORE DATA
- CLOUD
- PREMISES

- DATA CAN BE TRANSFORM FROM ONE FORM TO ANOTHER.
- THIS CAN BE DONE THROUGH ETL (EXTRACT, TRANSFORM AND LOAD)

  ####  TOOLS USED
  - EXCEL USED FOR
  - I. DATA CLEANING
  - II. ANALYSIS
  - III. DATA VISUALISATION
  - 
  - SQL - STRUCTURED QUERY LANGUAGE FOR QUERYING DATA
    
  - GITHUB FOR PORT FOLIO BUILDING

### DATA ANALYSIS LIFE CYCLE

 - INGESTION
 - TRANSFORMATION
 - MODELLING
 - VISUALISATION
 - ANALYSIS
 - PRESENTATION

#### DATA CLEANNG AND PREPARATION
1. DATA LOADING AND INSPECTION
2. HANDLING MISSING VARIABLES
3. DATA CLEANING AND FORMATTING

``` SQL
 SELECT * FROM TABLE1
WHERE CONDITION = TRUE
```

 #### M S EXCEL [DOWNLOAD HERE](HTTPS://WWW.MICROSOFT.COM)
 
 EXCEL IS A SPREDSHEET APPLICATION USED TO STORE, ANALYSE AND MANAGE DATA.

 #### MY EXCEL TABLE
 
 [MY EXCEL WORK.xlsx](https://github.com/user-attachments/files/17270509/MY.EXCEL.WORK.xlsx)

### PIVOT TABLE 
[Pivot Tables File.xlsx](https://github.com/user-attachments/files/17270523/Pivot.Tables.File.xlsx)

##### STRUCTURED QUERY LANGUAGE FOR QUERYING DATA
- MY SQL QUERIES

[Uploading  

Create table employee (
staffid varchar (10) not null,
firstname varchar (255) not null,
secondname varchar (255),
gender varchar (10),
date_of_birth date,
hiredate datetime,
primary key (staffid)
)

select * from employee

insert into employee (staffid,firstname, secondname, gender, date_of_birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')
select * from employee 
............to drop table .........
drop table employeeSQLQuery1.sql…]()

MY DATA BASE
[UplCreate database EstyDb 

create table Employee(
staffid varchar (10) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)
select * from Employee

insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth, hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')

select * from Employee
...... delete command ........
delete from Employee
where staffid = 'AB260'
Select * from Employee
.... truncate sql command ....
truncate table Employee

Identity in sql
CREATE TABLE PERSON (
personid int identity (1,1) primary key not null,
personname varchar (255) not null,
age int
)
select * from Person
select * from person

....insert more record into Employee table ...

insert into [dbo].[Employee]
values ( 'AB200', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB405', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB282', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB278', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09'),
( 'AB240', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB299', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB268', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB286', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09'),
( 'AB270', 'shukurat', 'lasisi', 'female','1982-10-09', '2018-02-09')

select * from [dbo].[Employee]

---- to create second table call SALARY TABLE-------

select * from [dbo].[Salary]

-----insert records into Salary table-------------

insert into salary (staffid, FirstName, lastname, Department, Salary)


values ( 'AB401', 'ayan', 'olakun', 'Information Tech.', 45000.45),
( 'AB212', 'okorie', 'mercy','Account',500000.99999),
( 'AB223', 'joshua', 'chukwuemeka', 'Human Resources',100560.9339999),
( 'AB234', 'sanni', 'ibrahim', 'Sales and Marketing',845688.99),
( 'AB254', 'mercy', 'olanipekun', 'Account',8889.999999),
( 'AB249', 'johnson', 'mercy', 'Information Tech.',234000.90909090),
( 'AB298', 'ayomide', 'halleluyah', 'Logistics', 678000.991999),
( 'AB260', 'deborah', 'justin', 'Logistics',900099.00697969),
( 'AB281', 'wale', 'olanipekun', 'Information Tech',873093.2344)

select * from salary

insert into [dbo].[Salary]
values ( 'AB200', 'ayomide', 'halleluyah', 'Human Resources',45699.8585),
( 'AB405', 'deborah', 'justin', 'Account',898349.900222),
( 'AB282', 'wale', 'olanipekun', 'Sales and Marketing',362636.564848),
( 'AB278', 'shukurat', 'lasisi', 'Logistics',100000.464647),
( 'AB240', 'johnson', 'mercy', 'Information Tech',3855590.9890093),
( 'AB299', 'ayomide', 'halleluyah', 'Account', 8585858.9292),
( 'AB268', 'deborah', 'justin', 'Human Resources',76767.93939)

select * from salary

...... sum command in sql........
select sum(salary) as totalsalary from salary

......Avereage command in sql .....
select Avg(Salary) as AverageSalary from salary

.....count command in sql ........
select count(staffid) as Employeecount from Employee

select count(staffid) as Number_of_Employee from Salary

.....Update ........
update salary
set salary = 7056999.9994
where Staffid = 'AB401'
select * from salary where staffid = 'AB401'

.....Update command in sql....
select * from [dbo].[Salary]
update salary set department = 'information Tech.'
where staffid = 'AB234'
select * from salary
where staffid = 'AB234'oading ESTYDB.sql…]()

###### LINKEDIN OPTIMISATION
THIS WAS ONE OF THE INTERESTING THING I LEARNT
- HOW TO PUT MY PROFILE PICTURE
- BANNER
- HEADLINE
- SKILLS
- BUILD A GOOD SUMMARY
- EDUCATION AND EXPERIENCE

MY PICTURE

![Screenshot_20240920-080139_Gallery](https://github.com/user-attachments/assets/9701bf0f-abd9-49d9-8fde-f5e654200f0d)

##### NEXT TOPIC
- POWER BI
- THIS IS A BUSINESS INTELLIGENCE TOOL FOR DATA VISUALISATION.
- IT CONVERTS DATA FROM DIFFERENT SOURCES TO INTERACTIVE DASHBOARD

#### AM STILL LEARNING...
- KUDOS TO MY TEACHERS

🥇

✈️

| heading 1| table 2| table 3|
|..........|........|........|
