# Pewlett-Hackard-Analysis

# Abstract

Determining the overall health of the workforce by analyzing the number of upcoming retirments by sorting employees by birthyear, and by departments. In order to accomplish this data from the overall workforce of Pewlett Hackard was taken into account. Problem statments were as follows:
    - Determine the total number of employees of each title that will be retiring soon.
    - Identify employees who would be eligible to act as mentors for future title holders.

## Data interpretation
- Data consisted of six .CSV files. the database relationships can be seen in figure 1. ERD. The schema code is located in the Module activity folder as a .txt file.
    - departments
    - empoyees
    - managers
    - dept_emp (employees in each department)
    - salaries
    - titles
 
#### FIg 1.
![FIG 1.](https://github.com/ChrFoley/Pewlett-Hackard-Analysis/blob/master/Module%20Exercise/EmployeeDB.png)

Step one, identified three tables (employees, titles, salaries) that needed to be joined in order to identify those employees that would be retiring. Employees born between 1952 and 1955 were considered, and grouped by title.

Step two, identified two tables (ret_by_title, and dept_emp) that needed to be joined and partitioned to remove duplicates. The table to delete duplicates and include only the most recent title held by each employee.

Step three, joined the employee and title databases to determine a list of possible employee mentors. Employees with birthdates in 1965 were considered.

## Results
The initial analysis on possible employees shows that there is a high likely hood that as many as 90,398 employees would be eligible for retirement in the near future. Additionaly, 3125 employees would qualify to become employee mentors. 

### Further analysis
specifically dealing with mentors, titles, departments and from dates should be further analysed to determine suitability. 



 
