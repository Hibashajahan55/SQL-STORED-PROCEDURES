# SQL STORED PROCEDURES
### Worker Table Stored Procedures
## Introduction
This project demonstrates how to use SQL stored procedures for managing a Worker table. The stored procedures allow you to add records, update data, and retrieve information such as salary, department count, and average salary.
## Table Structure
* Worker_Id INT
* FirstName CHAR(25)
* LastName CHAR(25)
* Salary INT(15)
* JoiningDate DATETIME
* Department CHAR(25))
## QUERIES
1. Create a stored procedure that takes in IN parameters for all the columns in the Worker table and adds a new record to the table and then invokes the procedure call.
2. Write stored procedure takes in an IN parameter for WORKER_ID and an OUT parameter for SALARY. It should retrieve the salary of the worker with the given ID and returns it in the p_salary parameter. Then make the procedure call.
3. Create a stored procedure that takes in IN parameters for WORKER_ID and DEPARTMENT. It should update the department of the worker with the given ID. Then make a procedure call.
4. Write a stored procedure that takes in an IN parameter for DEPARTMENT and an OUT parameter for p_workerCount. It should retrieve the number of workers in the given department and returns it in the p_workerCount parameter. Make procedure call.
5. Write a stored procedure that takes in an IN parameter for DEPARTMENT and an OUT parameter for p_avgSalary. It should retrieve the average salary of all workers in the given department and returns it in the p_avgSalary parameter and call the procedure.
## Conclusion
This project illustrates how stored procedures simplify database operations and enhance code reusability.
