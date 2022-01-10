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


The total list of retirement eligible employees in the dataabase is 133,766.  The file that contains this result is contained below.  This file requires analysis as it contains duplicates where employees have changed rols, titles or been promoted.

https://github.com/tchumphrey65/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv

![image](https://user-images.githubusercontent.com/91839403/148708312-a00c5351-7481-4c20-be05-1b53d7068d21.png)





This analysis identified 72,458 specific employees, after removal of duplicates, who are currently employed by Pewlett-Hackard and qualify for retirement per the specification provided.
The retiring employees come from 7 different job titles. The table is provided below.

Sample output - Retiring employees with more current title:

![image](https://user-images.githubusercontent.com/91839403/148707416-f517d857-5e46-4d08-b571-f264db61972d.png)

Complete list of retiring employees contained in file "unique_titles.csv"
https://github.com/tchumphrey65/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv

Query used to create retiring employees list

![image](https://user-images.githubusercontent.com/91839403/148707527-9c861854-a7cc-4fd8-be61-70254ee6f33e.png)

#### The Number of Retiring Employees by Title

![image](https://user-images.githubusercontent.com/91839403/148707639-85646012-c971-47dc-8e88-efe9df8ef4b2.png)

Summary of the number of employees retiring by title contained in file "retiring_titles.csv"
https://github.com/tchumphrey65/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv


#### Query used to determine Number of Retiring Employees by Title

![image](https://user-images.githubusercontent.com/91839403/148707693-9017686b-f796-4440-8838-c88ea8d34685.png)


### 2. The Employees Eligible for the Mentorship Program
There are 1549 employees eligible for the mentorship program.
The list of employees eligible are provided in mentorship_eligibility.csv, link below.

https://github.com/tchumphrey65/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv

The titles of those eligible for the mentorship program are shown below.  Six (6) unique titles make up the population of mentees.

![image](https://user-images.githubusercontent.com/91839403/148708554-0afe09f0-d5aa-4021-bda6-4cea1cb6a650.png)

### 3. Summary
The "silver tsunami" consists of 72,458 current employees eligible for retirement from 7 different job titles will in P-H.
This is as significant number of employees mainly from Engineering and technical roles.  This loss of experience certainly provides a risk and represents the loss of significant years of experience.  The There are plenty of retiring employees to provide metoriing and transfer knowledge to the next generation of employees.

Unfortunately with only 1,549 employees eligible for the mentor program there are not enough employees to bridge the gap of retirements.  This would suggesst that a broader or expanded criteria is needed to identify mentors to pair with the retiring mentors. 

With the impact of this wave of retirements pending additional analysis is needed to create mitigation actions:
Two additional queries that could be performed to provide insight would be:

Query to generate a list of employees that are eligible to retire by department (for all departments).
Query all employees, sorted by length of service, by department with expanded date ranges to increase eligibility to participate in the mentorship program.

