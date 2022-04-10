# Pewlett-Hackard-Analysis
## Overview
Pewlett-Hackard is preparing for the future. HR is asked to prepare anaylsis of who will be retiring in the next few years and how many positions will Pewlett-Hackard need to fill. The analysis will help Pewlett-Hackard by providing a list of all employees who will be eligible for retirement packages and build an employee database using SQL to analyze data from multple CSV sources.

## Purpose
After analyzing the CSV files, Pewlett-Hackard has requested additional information, including determining the number of retiring employees per title and identifying employees who are eligible to participate in a mentorship program.

## Results
### The Number of Retiring Employees by Title
We created a table that holds all the titles of employees born between Janary 1, 1952 and December 31, 1995, and accounted for each employee's most recent job title and employment end date to ensure they are still employed by the company. After running the analysis, it was found:

* The number of employees eligible for retirement is quite high: 72,458 employees
* The greatest number of employees eligible for retirement by title are Senior Engineers and Senior Staff:

![Retirement by title](https://user-images.githubusercontent.com/99205688/162638536-9bbb486f-b933-49da-b50e-ea2a374bb355.PNG)

### The Employees Eligible for the Mentorship Program
We created a mentorship-eligiblity table that holds current employees born between January 1, 1965 and December 31, 1965 to help Pewlett-Hackard prepare for the wave of retirees. After running the analysis, it was found:

* There are 1,549 employees eligible to participate in a mentorship program
* The number of employees eligible to participate in a mentorship program is much smaller than and would not replace the "silver tsunami" of employees currently eligible to retire

![Mentorship Count](https://user-images.githubusercontent.com/99205688/162638581-a788f4e7-53b6-47ce-a0f4-484de9a0ca3b.PNG)

![mentorship count 2](https://user-images.githubusercontent.com/99205688/162638559-2564b07a-f559-4a11-956f-2ec45d9f2fa2.PNG)

## Summary 
Given that the number of employees eligible to participate in a mentorship program is much smaller than the number of employees eligible for retirement, Pewlett-Hackard has to work on preparations for the coming "silver tsunami." After reviewing the data, additional queries that Pewlett-Hackard can consider are:

* Determining the number of employees eligible for a mentorship program by title. At this time, 418 Engineers and 268 Staff are eligible for mentorship. Given that the largest number of employees eligible for retirement are Senior Engineers and Senior Staff, Pewlett-Hackard should focus on training and promoting the Engineers and Staff in this group for the upcoming changes in employees.

![mentor count code](https://user-images.githubusercontent.com/99205688/162638592-651fd024-6f07-4c29-8a5b-95ca39d3c12f.PNG)

![mentor title count](https://user-images.githubusercontent.com/99205688/162638597-7774e462-ed6e-43d1-a14a-b94b6f4a2c4d.PNG)


* Determining the departments that have the most employees eligible for retirement. Pewlett-Hackard can strategically target training, promotions and recruitment in the departments that expect the greatest turnover in employees. The departments with the three largest populations of employees that are eligible for retirement are Development, Production, and Sales and should be the focus of Pewlett-Hackard's preparations for the future. 

![dept code 1](https://user-images.githubusercontent.com/99205688/162638603-6142212b-30ab-46cf-8d65-5702014fd852.PNG)

![dept code 2](https://user-images.githubusercontent.com/99205688/162638606-fbf8ff21-1f5d-4d31-b63a-2098462db4f2.PNG)

![retire by dept](https://user-images.githubusercontent.com/99205688/162638610-c0f86444-89ab-42f4-ad7c-edf843393492.PNG)

