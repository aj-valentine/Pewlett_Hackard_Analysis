# Pewlett Hackard Analysis
Analysis Using SQL 

## Overview of the Pewlett Hackard Analysis :open_file_folder:

This project was created for Bobby, an HR manager at a company called Pewlett Hackard. The purpose of the analysis is to provide information about their employees who are retiring within the next few years. They will use this information to gather data about which departments will have the most retirees and how many people they need to hire and train in order to replace the thousands of positions that will become available when the employees retire. This analysis will also help the team generate the retirement packages for all of the retiring employees. This analysis was done entirely in pgAdmin 4 and PostgreSQL 11. We pulled data from 6 CSV files in order to build an employee database and create tables using SQL. 

## Pewlett Hackard Retiring Employees Results 

In the first part of our analysis, we created a "Retirement Table" that contains all of the titles of employees who were born between January 1, 1952 and December 31, 1955. Then we created an additional table called "Retiring Titles" to show the count for each recent job title. In the second part of our analysis, we wanted to focus on the retiring employees that could be considered for a mentorship program to help younger employees successfully replace them. This chart is labeled "Mentorship Eligibility" and shows all of the employee information and the lastest title for employees that were born between January 1, 1965 and December 31, 1965. 

### Results from Part 1 of Analysis:

Top 10 Screenshot of Retirement Titles:

<img width="419" alt="retirement_titles" src="https://user-images.githubusercontent.com/67871338/92340367-ffbc4080-f087-11ea-951b-83cc1ee7d7fb.PNG">

Top 10 Screenshot of Last Title for Employees: 

<img width="303" alt="unique_titles" src="https://user-images.githubusercontent.com/67871338/92340370-034fc780-f088-11ea-850a-946fd14ca2f7.PNG">

Total Number of Retirees Per Department:

<img width="123" alt="retiring_titles" src="https://user-images.githubusercontent.com/67871338/92340371-06e34e80-f088-11ea-94d6-cb9cbe100a64.PNG">

### Results from Part 2 of Analysis: 

Top 10 Screenshot of Employees Available for Mentorship Program:

<img width="466" alt="mentorship_eligibility" src="https://user-images.githubusercontent.com/67871338/92340372-09de3f00-f088-11ea-9d72-6b13229c3ccc.PNG"> 

### Overall Results 

1. As one would assume, most of the senior level members of the organization are retiring. The top two highest positions of retirees are Senior Engineer at 29,414 roles and Senior Staff at 28,254 roles. 
2. Most of the retirees are Engineers, a department that requires significant training and education. So, the mentorship program would be most useful for the Enigneer positions. 
3. The second highest department of retirees is the Staff department. The mentorship program would also be helpful for these employees. 
4. There are 1,549 employees in the "Mentorship Eligibility" group, and 90,398 employees that are in the "Retiring Titles" group - so the company needs to find more employees to help wih the mentorship program. 

## Pewlett Hackard Analysis Summary

From our analysis, we can see that 90,398 employees will be retiring from Pewlett Hackard in the near future across various departments. Unfortunately, there are not enough employees in the mentorship group to mentor the next group of Pewlett Hackard employees. There are only 1,549 employees in this mentorship group. 

<img width="466" alt="mentorship_eligibility" src="https://user-images.githubusercontent.com/67871338/92340372-09de3f00-f088-11ea-9d72-6b13229c3ccc.PNG"> 

- The below table lists all of the titles per mentorship eligibility. The highest department is Senior Staff at 569 employees. 

<img width="207" alt="mentorship_eligibility_per_title" src="https://user-images.githubusercontent.com/67871338/92340373-0cd92f80-f088-11ea-93b1-3ca569a2c45f.PNG">

