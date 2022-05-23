# Employee Attrition Analysis for a company
## Summary
The company is looking how its data can be transformed to get some actionable insights and rights set of data engineering technology stack. The database contains a huge volume of employees data  with both employee engagement survey results and exit data. This provides a massive, globally diverse, and statistically relevant dataset for conducting research specific to attrition.

## Objective 
To design an end-to-end data pipeline and analyze the data for the organization which is looking for updating its employees policies and dealing with the issues related to the attrition rates over the given time period.

## Why it is a part of Bigdata  
Since the data volume is high and analyzing the data by using traditional approaches is time consuming .


## Project Description:
In this project, you are required to create end to end data pipeline and analyzing the data.

## Technology Stack:
you are required to work on below technology Stack. - MySQL (to create database)
- Linux Commands
- Sqoop (Transfer data from MySQL Server to HDFS/Hive) - HDFS (to store the data)
- Hive (to create database)
- Impala (to perform the EDA)
- SparkSQL (to perform the EDA)
- SparkML (to perform model building)
 Data Description

## Data Description: Please find the details of all the tables
a. Titles (titles.csv):
title_id – Unique id of type of employee 
designation id – Character – Not Null 
Title – Designation – Character – Not Null



b. Employees (employees.csv):
emp_no – Employee Id – Integer – Not Null

emp_titles_id – designation id – Not Null

birth_date – Date of Birth – Date Time – Not Null

first_name – First Name – Character – Not Null

last_name – Last Name – Character – Not Null

sex – Gender – Character – Not Null

hire_date – Employee Hire date –Date Time -Not Null

no_of_projects – Number of projects worked on – Integer – Not Null Last_performance_rating – Last year performance rating – Character – Not Null left – 

Employee left the organization – Boolean – Not Null

Last_date - Last date of employment (Exit Date) – Date Time
