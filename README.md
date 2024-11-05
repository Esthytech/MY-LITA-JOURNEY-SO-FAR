# MY-LITA-JOURNEY-SO-FAR
## REFRESHING MY MEMORY ON LITA PROJECT

###DATA ANALYSIS OVERVIEW

#### MY OUTLINE
- [DATA ANALYSIS OVERVIEW](#data-analysis-overview)
- [DATA ANAYSIS HAS TO DO WITH](#data-analysis-has-to-do-with)
- [WAYS TO STORE DATA](#ways-to-store-data)
- [TOOLS USED](#tools-used)
- [DATA ANALYSIS LIFE CYCLE](#data-analysis-life-cycle)
- [DATA CLEANNG AND PREPARATION](#data-cleaning-and-preparation)
- [STRUCTURED QUERY LANGUAGE FOR QUERYING DATA](#structured-query-language-for-querying-data)
- [MY PICTURE](#my-picture)
- [NEXT TOPIC](#next-topic)
- [AM STILL LEARNING](#am-still-learning)
- [POWER BI (BUSINESS INTELLIGENCE)](#power-bi-(business-intelligence))
- [SOURCES OF DATA](#sources-of-data)
- [DATA CLEANING PROCESS](#data-cleaning-process)
- [AFTER CLEANING CHECK](#after-cleaning)
- [POWER BI DATA CLEANING ASSIGNMENT](#power-bi-data-cleaning-assignment)
- [LITA CAPSTONE PROJECT](#lita-capstone-project)
- [EXCEL PIVOT TABLE CHARTS](#excel-pivot-table-charts)
- [SQL QUERIES](#sql-queries)
- [POWER BI VISUALISATIONS](#power-bi-visualisations)
- [PROJECT TWO (2) CUSTOMER SEGMENTATION FOR SUBSCRIPTION SERVICE](#project-two-(2)-customer-segmentation-for-subscription-service)
- [EXCEL PIVOT TABLE CHARTS FOR PROJECT 2](#excel-pivot-table-charts-for-project-2)
- [SQL QUERIES FOR PROJECT 2](#sql-queries-for-project-2)
- [POWER BI VISUALISATION FOR PROJECT 2](#power-bi-visualisation-for-project-2)


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

MY EXCEL CHART
![Screenshot (13)](https://github.com/user-attachments/assets/24cd88cd-67aa-437c-820b-f155472793ed)


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

THE TABLES ARE BELOW

![Screenshot (12)](https://github.com/user-attachments/assets/b75001a3-f142-483d-901e-787102d81442)

![Screenshot (9)](https://github.com/user-attachments/assets/e0518683-dc06-4b96-bc14-c877223ca11b)

![Screenshot (6)](https://github.com/user-attachments/assets/1a485ce3-98ab-4539-bd71-bd29db4af081)



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

#### AM STILL LEARNING
- KUDOS TO MY TEACHERS

🥇

✈️

| HEADING 1 | HEADING 2 |HEADING 3|
|-----------|-----------|---------|
|TABLE 1    | TABLE 2   | TABLE 3 |

#### POWER BI (BUSINESS INTELLIGENCE)
- USES OF POWER BI
1. THIS IS A TOOL USED FOR DATA VISUALISATION. 
2. IT CONVERTS DATA FROM DIFFERENT SOURCES TO INTERACTIVE DASHBOARD.
3. Microsoft Power BI is used to find insights within an organization's data.
4. It can help connect disparate data sets
5.  Transform and clean the data into a data model and create charts or graphs to provide visuals of the data.

##### SOURCES OF DATA 
- EXCEL WORKBOOK
- SQL SERVER
- DATAVERSE
- DATAFLOWS
- ANALYSIS SERVICES
- TEST / CSV
- WEB, ETC

#### DATA CLEANING PROCESS
ONCE DATA IS UPLOADED FROM ANY SOURCE, PREVIEW IT AND TRANSFORM BEFORE LOADING.
N/B: AS MECHANIC IS TO A CAR, TRANSFORM IS TO A DATA.
- ANY DIRTY DATA MUST BE TAKEN TO TRANFORM TO EDIT, MANIPULATE AND CLEAN.
- DATA CLEANING IS THE MOST IMPORTANT STEP IN POWER BI

### PROCESSES OF DATA CLEANING
1.  CHECK YOUR COLUMN QUALITY
2.  TRANSPOSE YOUR DATA
3.  PROMOTE THE HEADER
4.  CHECK THE DATA TYPE AND USE THE APPROPIATE DATATYPE
5.  UNPIVOT THE COLUMN WHERE NECESSARY

#### AFTER CLEANING CHECK
- COLUMN QUALITY
- COLUMN DISTRIBUTION
- COLUMN PROFILE
ONCE YOUR DATA IS CLEAN, RENAME IT AND SAVE.

COLUMN QUALITY

![Screenshot (15)](https://github.com/user-attachments/assets/c541582e-deee-4e3f-a0ad-8de0960e33e8)

COLUMN PROFILE AND DISTRIBUTION
![Screenshot (14)](https://github.com/user-attachments/assets/5f2d06b8-116a-4146-aa24-e8e7f6bc6ca6)

THE ABOVE IS MY DATA AFTER CLEANING

### POWER BI DATA CLEANING ASSIGNMENT
THE MOST IMPORTANT AND CRUCIAL STEP AFTER IMPORTING YOUR DATA IS THE DATA CLEANING PROCESS AFTER WHICH YOU CAN CONTINUE WITH YOUR VISUALISATIONS AND ANALYSIS.
BELOW ARE THE RESULT OF THE DATA CLEANING ASSIGNMENT WITH THE APPLIED STEPS

![DATA CLEANING 1](https://github.com/user-attachments/assets/9a3e32dc-605c-42c2-89bd-e1ce66768e07)

![DATA CLEANING 222](https://github.com/user-attachments/assets/c82830c6-068a-4682-8eaa-f5872acc592b)


![DATA CLEANINING 3](https://github.com/user-attachments/assets/4d2ed078-8534-4670-9fd4-a6f7b13ed7ef)


![DATA CLEANING 4](https://github.com/user-attachments/assets/8f45a980-a046-4e91-9dc6-1ef8666a4fe1)

IN THE ABOVE TABLE YOU CAN USE THE COLUMN QUALITY, COLUMN DISTRIBUTION AND COLUMN PROFILE TO FURTHER CONFIRM IF THE DATA IS PROPERLY CLEANED.

### LITA CAPSTONE PROJECT
- PROJECT 1 (SALES DATA)
### EXCEL PIVOT TABLE CHARTS 

![PIVOT TABLE CHART](https://github.com/user-attachments/assets/90cd8c22-4809-4a7d-8e92-0ca523be88f5)

- FROM THE ABOVE PIVOT TABLE, IT CAN BE SEEN THAT
- 1. TOTAL SALES BY PRODUCT AMOUNTED TO 345,000 WITH HATS BEING THE HIGHEST SOLD PRODUCT
  2. SOUTH REGION GENERATED THE HIGHEST REVENUE
  3. SALES OF HAT WAS MORE IN THE EAST
  4. THE PRODUCT THAT HAS THE LOWEST SALE IS SHOES IN THE WESTERN REGION
     
![PI PIVOT CHART](https://github.com/user-attachments/assets/c587747d-e5b3-4138-91da-060760275ed4)
- THIS PIE CHART INDICATES REVENUE BY REGION. THE SOUTH GENERATED THE HIGHEST REVENUE AND THE WEST HAS THE LEAST.

![PI PIVOT CHART 2](https://github.com/user-attachments/assets/5ad3bc70-1ccc-4fa6-af2b-71418ba8ac84)
- THIS LINE CHART INDICATES THE TREND IN SALES BY MONTH, WITH FEBRUARY AND JUNE HAVING THE HIGHEST SALE, MAY AND DECEMBER HAVING THE LOWEST SALES.

![PI PIVOT CHART 3](https://github.com/user-attachments/assets/22bd7c5b-1dc4-4680-a283-120c6e7011e0)
- THE BAR CHART ABOVE INDICATES THE SALES BY PRODUCT. HATS BEING THE HIGHEST SOLD PRODUCT, FOLLOWED BY SHOES.
- GLOVES AND SHIRTS WERE ALSO IN HIGH DEMAND WITH JACKET BEING THE LEAST SOLD PRODUCT.

#### SQL QUERIES


![P1 SQL 1](https://github.com/user-attachments/assets/45859b13-c339-4ede-837b-48bcdfbdee4f)
- THIS QUERY SHOWS THE TOTAL SALES FOR EACH PRODUCT

![P1 SQL 2](https://github.com/user-attachments/assets/df481402-6820-4654-9cfd-dfc7508841d2)
- THIS INDICATES THE NUMBER OF SALES PER REGION

![P1 SQL 4](https://github.com/user-attachments/assets/3f8d2626-57c2-4201-9a38-ca2d19d33c40)
- THIS TABLE SHOWS REVENUE PER PRODUCT

![P1 SQL 5](https://github.com/user-attachments/assets/4c1bea7e-a79a-4bcf-8445-e53343b3da62)
- THIS INDICATES THE MONTHLY SALES FOR CURRENT YEAR (2024)

![P1 SQL 6](https://github.com/user-attachments/assets/85e7377e-c376-4edf-8795-5cad5e7e2224)
- THIS INDICATES THE TOP 5 CUSTOMERS

![P1 SQL 7](https://github.com/user-attachments/assets/7828d31f-5799-4a0a-bcd9-cc404763ac75)
- THIS SHOWS THE PERCENTAGE OF TOTAL SALES BY REGION

![P1 SQL 8](https://github.com/user-attachments/assets/32ff43e7-8468-45fc-a99e-fd0129a85e2d)
- THIS INDICATES THE PRODUCT WITH NO SALES.
- THIS IS SHOWING 0 BECAUSE THERE WAS SALES FOR EACH PRODUCT

### POWER BI VISUALISATIONS

![P1 VISUALS](https://github.com/user-attachments/assets/c966ed85-ce7e-4702-9ad3-d6183720d84c)
THIS VISUALISATION INDICATES THE SALES DATA BY REGION AND ORDER ID BY PRODUCT

![P1 VISUALS 2](https://github.com/user-attachments/assets/65ab6651-3f0d-426a-aba0-60502e2df958)


![P1 VISUALS 3](https://github.com/user-attachments/assets/d8bd11f0-b4cf-4c27-bfcd-08ac46a6fe0a)
- THIS SHOWS SOME OF QUANTITY BY PRODUCT, USING THE SLICER THIS REPORT IS STREAMLINE TO SEPERATE PRODUCT

![P1 VISUALS 4](https://github.com/user-attachments/assets/4843c208-d780-4cca-b51d-29b75ffa441c)
- THIS REPORT SHOW SUM OF REVENUE BY EACH PRODUCT GENERATED

![P1 VISUALS5](https://github.com/user-attachments/assets/a542ab0e-4f84-4dca-8bb8-a4961dfcfb07)
- INTERESTING REPORTS

- DEDUCTIONS:
- FROM THE ABOVE DATA AND CHARTS, I WILL DEDUCE THAT THAT COMPANY SHOULD FOCUS ON THE REGIONS WITH LOW SALES,
  CREATE MORE AWARENESS OF THE PRODUCTS THROUGH ADVERTS AND BILL BOARDS AND RUN PROMOS TO ATTRACT THE CUSTOMERS.

  #### PROJECT TWO (2) CUSTOMER SEGMENTATION FOR SUBSCRIPTION SERVICE
  
  ### EXCEL PIVOT TABLE CHARTS FOR PROJECT 2
  
![P2 PIVOT TABLE](https://github.com/user-attachments/assets/77286d1b-0d72-48dc-aa13-39ffe9d56978)
- THIS PIVOT TABLE INDICATES REVENUE BY SUBSCRIPTION, REGION BY SUBSCRIPTION, QUARTERLY REVENUE BY REGION E.T.C.

![P2 CHART 1](https://github.com/user-attachments/assets/fbdc3ed7-8bc5-4fea-9d53-1eae98044835)
- THIS BAR CHART INDICATES THE REVENUE BY SUBSCRIPTION CANCELLED

![P2 CHARTS 2](https://github.com/user-attachments/assets/283ce7bb-6145-4090-8b9e-bc7d1f0c5094)
- THIS CHART SHOWS THE REVENUE BY SUBSCRIPTION TYPE

![P2 CHARTS 33](https://github.com/user-attachments/assets/0160194a-99b2-4d6c-9931-8b7f7a61ccf6)
- THIS BPIE CHART SHOW THE REGION BY SUBSRIPTION TYPE

 ### SQL QUERIES FOR PROJECT 2
  
![P2 Q1](https://github.com/user-attachments/assets/4f1c1f39-fbff-4600-a0d2-6c30cb59f8b4)
- NUMBER OF CUSTOMER FOR EACH REGION

![P2 Q2](https://github.com/user-attachments/assets/410ced93-e632-4cf4-afb4-203b7f4c9937)
- THE MOST POPULAR SUBSCRIPTION TYPE

![P2 Q3](https://github.com/user-attachments/assets/0e85bfa8-99d1-4981-9ca1-557a2c0676e7)
- CANCELLED SUBSCRIPTION WITHIN 6 MONTHS

![P2 Q4](https://github.com/user-attachments/assets/851a696e-fcda-40a4-88bc-0c15efa16540)
- AVERAGE SUBSCRIPTION DURATION

![P2 Q5](https://github.com/user-attachments/assets/5e37b321-cdf4-4301-9937-a39d9c2a2895)
- SUBSCRIPTION LONGER THAN 12 MONTHS

![P2 Q5B](https://github.com/user-attachments/assets/20cdaf79-5526-4c4d-b05d-e893fb49f3fe)


![P2 Q6](https://github.com/user-attachments/assets/5a3a91bd-d1db-42fd-983c-fdd27133736d)
- REVENUE BY SUBSCRIPTION TYPE

![P2 Q7](https://github.com/user-attachments/assets/25b4ccd6-2892-4ec3-8087-b04c96d5a3e1)
- TOP 3 REGIONS BY SUBSCRIPTION CANCELLATION

![P2 Q8 A](https://github.com/user-attachments/assets/17031547-b7dc-4293-8c0c-5ab28cf9d81c)
- TOTAL NUMBER OF ACTIVE CANCELLED SUBSCRIPTIONS

![P2 Q8B](https://github.com/user-attachments/assets/959afd2c-6f0f-4435-90f0-d4504287d0e3)

### POWER BI VISUALISATION FOR PROJECT 2
