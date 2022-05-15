# Pewlett-Hackard-Analysis
---
## Overview of Analysis
The purpose of this analysis was to determine which employees at a company were eligible for retirement.  In order to accomplish this, a SQL database was created with tables to store the raw data from the company.  Then, queries were performed with SQL, starting with retrieving all employees of retirement age and storing them in a table.  That table was then filtered again to remove duplicates and show only active employees.  This data was then further broken down by showing the count of employees of retirement age within each department.  Afterward, a separate query was run to retrieve employees born in 1965 who are now eligible for a Mentorship Program.

## Results
- Overall, there are 72,458 employees who are currently eligible for retirement
- The majority of these employees are at the Senior level with approximately 26,000 being Senior Engineers and approximately 25,000 being Senior Staff
- This means that roughly 70% of the employees eligible for retirement are of the Senior level
- There are currently 1,549 employees who are eligible for the Mentorship Program at the company

## Summary
With over 70 thousand employees eligible for retirement, there is likely to be many roles which will need to be filled at the company.  However, since many of the positions are Senior level positions, it is likely that there are already employees at the company who could be eligible to fill these roles.  Therefore the number of roles which need to be filled as the "silver tsunami" begins to make an impact is probably substantially less than 70 thousand.  Additionally, if there are current employees who are replacing the Senior level employees, then many of the roles which need to be filled from outside the company could likely be lower level positions with more candidates and lower wages.  Additionally, since there is currently only 1,549 employees who are eligible for the mentorship program, there are more than enough 'retirement-ready' employees to mentor this next generation.

I believe that in order to more accurately understand how the "silver tsunami" will effect the company there is several other queries which might be helpful.  The first query I would want to add would be perform a count of the employees, grouping them by their hire dates.  By using a query like this it would be easier to see the distribution of the employees in terms of how long they have worked for the company, and therefore it would be more possible to see how likely they would be to fill one of the senior positions which needs filled.  Another pair of queries which I believe would be helpful to understand how the silver tsunami will impact the company would be to show the sum as well as the average salaries for the employees eligible for retirement to see how much the company will likely have to pay the replacements for these positions.
