EMPLOYEE_SQL


It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

DATA MODELING:
Inspect the CSVs and sketch out an ERD of the tables
See ERD Diagram.png in EmployeeSQL folder


DATA ENGINEERING:
Use the information you have to create a table schema for each of the six CSV files, specifying data types, primary keys, foreign keys, and other constraints.
See schema.sql in EmployeeSQL folder
Import each CSV file into the corresponding SQL table.


DATA ANALYSIS (SQL QUERY)
See query.sql in EmployeeSQL folder for list of queries addressing the following:
List the following details of each employee: employee number, last name, first name, gender, and salary.

List employees who were hired in 1986.

List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.

List the department of each employee with the following information: employee number, last name, first name, and department name.

List all employees whose first name is "Hercules" and last names begin with "B."

List all employees in the Sales department, including their employee number, last name, first name, and department name.

List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
