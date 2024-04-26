# HR-Dashboard-MySQL-PowerBI
![image](https://github.com/Arya-Prerna/HR-Dashboard-MySQL-PowerBI/assets/168172452/cdf6a004-b3da-40bf-b338-2b4210b6889f) <br>
![image](https://github.com/Arya-Prerna/HR-Dashboard-MySQL-PowerBI/assets/168172452/cfe78791-d1db-4533-84ab-11ee1e0bb9f3)

# Data Used
* Data - HR Data with over 22000 rows from the year 2000 to 2020.<br>
* Data Cleaning & Analysis - MySQL Workbench<br>
* Data Visualization - PowerBI<br>

# Questions
1. What is the gender breakdown of employees in the company? <br>
2. What is the race/ethnicity breakdown of employees in the company? <br>
3. What is the age distribution of employees in the company? <br>
4. How many employees work at headquarters versus remote locations?<br>
5. What is the average length of employment for employees who have been terminated?<br>
6. How does the gender distribution vary across departments and job titles?<br>
7. What is the distribution of job titles across the company?<br>
8. Which department has the highest turnover rate?<br>
9. What is the distribution of employees across locations by state?<br>
10. How has the company's employee count changed over time based on hire and term dates?<br>
11. What is the tenure distribution for each department?<br>
# Summary of Findings<br>
* There are more male employees<br>
* White race is the most dominant while Native Hawaiian and American Indian are the least dominant.<br>
* The youngest employee is 20 years old and the oldest is 57 years old<br>
* 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.<br>
* A large number of employees work at the headquarters versus remotely.<br>
* The average length of employment for terminated employees is around 7 years.<br>
* The gender distribution across departments is fairly balanced but there are generally more male than female employees.<br>
* The Marketing department has the highest turnover rate followed by Training. The least turn over rate are in the Research and development, Support and Legal departments.<br>
* A large number of employees come from the state of Ohio.<br>
* The net change in employees has increased over the years.<br>
* The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.<br>
# Limitations
* Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.<br>
* Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
