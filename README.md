## Employee Tracker 



## Demo 

https://watch.screencastify.com/v/P2gWBDU78F3ZocUVQi53

## Description
* Functional application.

* GitHub repository with a unique name and a README describing the project.

* The command-line application should allow users to:

  * Add departments, roles, employees

  * View departments, roles, employees

  * Update employee roles

## User Story
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business

## Criteria

GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager and that employee is added to the database
WHEN I choose to update an employee role


# Tech Used
- inquirer
- mySQL
- console.table
- Javascript
- Node.js


## Usage
1. install npm init -y to create a new .json file
2. npm i
3. npm i inquirer
4. npm i mysql
5. npm i console.table
6. make sure to run .sql file in mySQL workbench before running server.js so that tables are able to render correctly
7. run node server.js
8. make sure server.js is connected to SQL before continuing
9. run through prompts as required 



## Contributions
1. ![GitHub license](https://img.shields.io/badge/Made%20by-%40EdenKhaos-orange)
2. No front end files required.
3. use seed.sql to create an existing table to pull sample information from to make it easier to run through the app.
