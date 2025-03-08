# DATABASE_SECURITY

## TASK 1 
1- Job History Access (Table Fire with Row Filter Policy): this row-level policy in the
JOB_HISTORY table has the following constraints:
o Allows each employee to view only his/her own job history.
o Allows managers to access the job history of their managed employees.
o Allows HR Managers to access all records.
➢ Hint: You need to use 'JOB_ID','EMPLOYEE_ID' and 'MANAGER_ID'
from EMPLOYEES table.

## TASK 2 
2- Salary Policy (Column Fire with Column Filter): This column-level policy allows
employees to access their own data inside EMPLOYEES table, including salary
information, as well as the data of other employees, with the exception of salary
information, while granting full access to HR Managers and Financial Managers to view
all data including salaries of all employees.
➢ Hint: You need to use 'JOB_ID' and 'EMPLOYEE_ID' from EMPLOYEES
table.

## TASK 3
3- Time-Based Access: This policy controls access to the EMPLOYEES table only during
office hours, applied to all members of the organization.


## TASK 4 
Department Location Updates (Table Fire with Row Filter Policy): For the
DEPARTMENTS table, this row-level policy enables department managers to update
only their department locations (LOCATION_ID column), while granting HR Managers
the ability to update all records.
➢ Hint: You need to use 'JOB_ID' and 'EMPLOYEE_ID' from EMPLOYEES
table.
