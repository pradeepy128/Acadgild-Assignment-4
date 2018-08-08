# Acadgild-Assignment-4
Task 1.1
Write a program to implement wordcount using Pig.

Task 1.2
We have employee_details and employee_expenses files. Use local mode while running Pig and write Pig Latin script to get below results:
employee_details (EmpID,Name,Salary,DepartmentID)
https://github.com/prateekATacadgild/DatasetsForCognizant/blob/master/employee_details.txt
employee_expenses(EmpID,Expence)
https://github.com/prateekATacadgild/DatasetsForCognizant/blob/master/employee_expenses.txt
(a) Top 5 employees (employee id and employee name) with highest rating. (In case two employees have same rating, 
employee with name coming first in dictionary should get preference)
(b) Top 3 employees (employee id and employee name) with highest salary, whose employee id is an odd number. 
(In case two employees have same salary, employee with name coming first in dictionary should get preference)
(c) Employee (employee id and employee name) with maximum expense (In case two employees have same expense, 
employee with name coming first in dictionary should get preference)
(d) List of employees (employee id and employee name) having entries in employee_expenses file.
(e) List of employees (employee id and employee name) having no entry in employee_expenses file.

Task 1.3
Implement the use case present in below blog link and share the complete steps along with screenshot(s) from your end.
https://acadgild.com/blog/aviation-data-analysis-using-apache-pig/

Task2.1
https://drive.google.com/file/d/0Bxr27gVaXO5sa0JBamZXdkpYUFk/view?usp=sharing
Create a database named 'custom'.
Create a table named temperature_data inside custom having below fields:
1. date (mm-dd-yyyy) format
2. zip code
3. temperature
The table will be loaded from comma-delimited file.
Load the dataset.txt (which is ',' delimited) in the table.

Task 2.2
● Fetch date and temperature from temperature_data where zip code is greater than 300000 and less than 399999.
● Calculate maximum temperature corresponding to every year from temperature_data table.
● Calculate maximum temperature from temperature_data table corresponding to those years which have at least 2 entries in the table.
● Create a view on the top of last query, name it temperature_data_vw.
● Export contents from temperature_data_vw to a file in local file system, such that each file is '|' delimited.
