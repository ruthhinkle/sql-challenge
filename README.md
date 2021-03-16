# Employee Database

## Description
My task was to conduct research on fictional employees from a bygone era. All that remains of their time at the firm are six csv files. I created a database to store the data and run queries on the data available. 

## Data Engineering
I began by creating an Entitity Relationship Diagram (ERD) to map the relationships between the tables. Then I created the tables in PostGres and imported the csvs. 

## Data Analysis
Once the data was loaded, I ran queries to do the following: 
* List the following details of each employee: employee number, last name, first name, sex, and salary.
* List first name, last name, and hire date for employees who were hired in 1986.
* List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
* List the department of each employee with the following information: employee number, last name, first name, and department name.
* List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
* List all employees in the Sales department, including their employee number, last name, first name, and department name.
* List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
* In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Repository Contents
* Data
    * departments.csv
    * dept_emp.csv
    * dept_manager.csv
    * employees.csv
    * salaries.csv
    * titles.csv
* EmployeesSQL
    * ERD_Image.png
    * ERD-Image_text.txt
    * Queries.sql
    * Schema.sql