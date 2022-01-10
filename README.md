# Pewlett-Hackard-Analysis
## Purpose

The purpose of this project is to analyze employee data to assess risk and help prepare for an expected high number of retirements.  This analysis will be conducted utilizing SQL. This output of this analysis will provide the company with the number of current employees eligible for retirement and evaluate by title the number of employees expected to retire.  This data will aid the company in understanding where the greatest impact will be felt and plan actions to mitigate the impact.

Part of the solution to what is being called a "silver tsunami" will be a transfer of knowledge via a mentorship program so that experienced employees can mentor remaining employees helping with continuity of operations.  This project will analyze the employee data to generate a list of those eligible for the mentorship program.

## Project deliverables are:
 1. The Number of Retiring Employees by Title
 2. The Employees Eligible for the Mentorship Program
 3. A written report on the employee database analysis (README.md)

## Resources
Data: Employee data csv files)
Software: PostgreSQL 11.14; PgAdmin 6.1; VS Code version 1.63.2

## Results
### 1. The Number of Retiring Employees by Title

This analysis identified 72,458 employees currently employed by Pewlett-Hackard who qualify for retirement.
The retiring employees come from 7 different job titles. The table is provided below.

Sample output - Retiring employees with more current title:

![image](https://user-images.githubusercontent.com/91839403/148707416-f517d857-5e46-4d08-b571-f264db61972d.png)

Complete list of retiring employees contained in file "unique_titles.csv"
https://github.com/tchumphrey65/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv

Query used to create retiring employees list

![image](https://user-images.githubusercontent.com/91839403/148707527-9c861854-a7cc-4fd8-be61-70254ee6f33e.png)

#### The Number of Retiring Employees by Title

![image](https://user-images.githubusercontent.com/91839403/148707639-85646012-c971-47dc-8e88-efe9df8ef4b2.png)

Complete list of retiring employees contained in file "retiring_titles.csv"



#### Query used to determine Number of Retiring Employees by Title

![image](https://user-images.githubusercontent.com/91839403/148707693-9017686b-f796-4440-8838-c88ea8d34685.png)


### 2. The Employees Eligible for the Mentorship Program





