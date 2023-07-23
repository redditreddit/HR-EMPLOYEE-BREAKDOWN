
# Human Resources Employee Breakdown

![Screenshot 2023-07-22 213342](https://github.com/redditreddit/HR-EMPLOYEE-BREAKDOWN/assets/137014414/c287ea11-c29f-4298-b42c-86e425d774f0)

## Data Used

#### Data - Human Resources Data with over 22,000 rows from years 2000 to 2020

#### Data Cleaning - MySQL Workbench

#### Data Visualization - PowerBI

## Questions

 1. What is the gender breakdown of employees in the company?
 2. What is the race/ethnicity breakdown of employees in the company?
 3. What is the age distribution of employees in the company?
 4. How many employees work at headquarters versus remote locations? 
 5. What is the average length of employment for employees who have been terminated?
 6. How does the gender distribution vary across departments and job titles? 
 7. What is the distribution of job titles across the company?
 8. Which department has the highest turnover rate?
 9. What is the distribution for employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Summary of Findings

- There are predominantly male employees
- The gender distribution across departments is fairly balanced but there are generally more male than female employees
- Most employees are white while the least are Native Hawaiian
- The youngest employee is 20 years old and the oldest is 57 years old.
- 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). The largest number of employees were between 25-34 followed by 35-44 while 55-64 was the smallest
- The average length of employment for terminated employees is around 8 years
- The Marketing department has the highest turnover rate followed by Training. The lowest turnover rate departments are the Research and development, Support and Legal departments.
- The largest number of employees come from the state of Ohio
- The net change in employees has increased over the years.
- The average tenure(time as job title) for each department is about 8 years with Legal and Auditing having the highest and Service, Sales and Marketing having the lowest.

## Limitations

- Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
