<big><b> Module 9 Homework : SQL </br></b></big>

It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.</br>

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.</br>

<b>Requirements</br></b>
<b>Data Modeling (10 points)</b></br>
Entity Relationship Diagram is included or table schemas provided for all tables</br>
-Using the CSV Files provided, I was able to visusally organize the data, noted the data types required for building visually, and also noted the Primary Keys & Foreign Keys<br>
-Finally, I drew my Entity Relationship Diagram (ERD) using QuickDataBaseDiagram application (seen in image)<br>


![DataModeling](https://github.com/molleighH/SQL-Challenge/assets/144710935/c74f1e69-8ddd-4b12-a119-73e1f887e5c9) <br><br>

<b>Data Engineering (70 points)</b><br>
-All required columns are defined for each table (10 points)<br>
-Columns are set to the correct data type (10 points)<br>
-Primary Keys set for each table (10 points)<br>
-Correctly references related tables (10 points)<br>
-Tables are correctly related using Foreign Keys (10 points)<br>
-Correctly uses NOT NULL condition on necessary columns (10 points)<br>
-Accurately defines value length for columns (10 points)<br>

<br>
<b>Data Analysis (20 points)</b><br>
1. List the employee number, last name, first name, sex, and salary of each employee (2 points)<br>
2. List the first name, last name, and hire date for the employees who were hired in 1986 (2 points)<br>
3. List the manager of each department along with their department number, department name, employee number, last name, and first name (2 points)<br>
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name (2 points)<br>
5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B (2 points)<br>
6. List each employee in the Sales department, including their employee number, last name, and first name (2 points)<br>
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name (4 points)<br>
8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name) (4 points)<br>

