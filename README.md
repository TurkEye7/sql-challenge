# sql-challenge

# Project Overview
This project focuses on modeling, engineering, and analyzing data from Pewlett Hackard's employee records. The project consists of creating an Entity Relationship Diagram (ERD), importing CSV data into a PostgreSQL database, and executing SQL queries for specific analysis tasks.

# Project Structure
The project is divided into the following three parts:

# 1. Data Modeling
An Entity Relationship Diagram (ERD) was created to model the relationships between tables, which include:
employees
departments
dept_emp
dept_manager
salaries
titles
The ERD visually represents how these tables are related through primary and foreign keys.
The ERD can be found in the file: ERD.png.

# 2. Data Engineering
PostgreSQL tables were created based on the provided CSV files.
Table schemata were designed with appropriate data types, constraints (e.g., primary keys, foreign keys), and relationships.
Data types were chosen to represent integers, dates, and character strings as required.
All tables were imported in the correct order, respecting foreign key relationships.
The SQL file that contains the table schema definitions is: table_schemata.sql.

# 3. Data Analysis
SQL queries were written to analyze the employee data.
The queries include:
Listing employee details, such as employee numbers, names, and salaries.
Retrieving employees hired in specific years (e.g., 1986).
Identifying department managers and employees within specific departments.
Aggregating data, such as counting the frequency of last names.
The SQL queries used in the analysis are saved in the file: queries.sql.
Data Sources
The following CSV files were used for this project:

departments.csv
dept_emp.csv
dept_manager.csv
employees.csv
salaries.csv
titles.csv
These CSV files were imported into PostgreSQL to create the database schema.

SQL Queries
Here is a summary of the SQL queries executed in this project:

List of Employees and Salaries:

Lists employee numbers, last names, first names, sex, and salaries of each employee.
Employees Hired in 1986:

Retrieves first name, last name, and hire date for employees who were hired in 1986.
Department Managers:

Lists the manager of each department along with department number, department name, employee number, last name, and first name.
Employee Department Information:

Lists each employee’s employee number, last name, first name, department number, and department name.
Employees Named 'Hercules' with Last Names Starting with 'B':

Retrieves details of employees whose first name is "Hercules" and whose last name begins with the letter "B."
Sales and Development Departments:

Lists employees working in the Sales and Development departments, including employee numbers, last names, first names, and department names.
Frequency of Last Names:

Counts and lists the frequency of employee last names in descending order.
# I USED AI OPEN SOURCE LANGUAGES SUCH AS CHATGPT to HELP ME DO THIS ASSINGMENT 
