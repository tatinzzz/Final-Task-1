# Final-Task-1

This task introduces the fundamentals of MySQL using a multi-level corporate database. It involves writing SQL queries, building table structures, and developing relational schemas or ER diagrams. To demonstrate the database's construction, the portfolio will also contain SQL copies of the database and table architecture.

## Task 1: Create the employees table
- Define employee_id as a unique integer, auto-increment, and primary key.
- Define employee_name as a VARCHAR (up to 255 characters), and make it not null.
 - Define manager_id as an integer, which will be a foreign key referencing employee_id from the same table.

## Task 2: Create the departments table
- Define department_id as a unique integer, auto-increment, and primary key.
- Define department_name as a VARCHAR (up to 255 characters), and make it not null.

## Task 3: Create the employee_departments table
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define department_id as an integer, which will be a foreign key referencing department_id in the departments table.
- Set a composite primary key on the combination of employee_id and department_id.

## Task 4: Create the employee_projects table
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define project_name as a VARCHAR (up to 255 characters), and make it not null.

## Task 5: Create the managers table
- Define manager_id as a unique integer, auto-increment, and primary key.
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.

## Here's The Screenshots of Each Table and Output


## Employee Table Sql Code 
![task1code](https://github.com/user-attachments/assets/5de489a0-fcae-4ee3-96c8-60514d912ef9)
## Employee Table Output
![employeetbl](https://github.com/user-attachments/assets/b7d35f69-2889-47f8-a492-0406eb4a9f83)



## Departments Table Sql Code
![task2code](https://github.com/user-attachments/assets/5217869e-a6f4-4fdc-afcf-c135725f98e3)
## Departments Table Output
![departmenttbl](https://github.com/user-attachments/assets/6aac9d87-4685-4d7d-8d5c-e9f901eec412)



## Employee Departments Table Sql Code
![task3code](https://github.com/user-attachments/assets/5cdd6ad3-c973-44d3-8cfe-287a0320dfbe)
## Employee Departments Table Output
![employee_department_tbl](https://github.com/user-attachments/assets/e398fbce-6aee-4fd4-aee3-08459b3e7e73)


## Employee Projects Table Sql Code
![task4code](https://github.com/user-attachments/assets/d3495414-233d-42f9-bc57-129de3e64774)
## Employee Projects Table Output
![employee_project_tbl](https://github.com/user-attachments/assets/18447185-ab86-4a88-8186-f0b03442882b)



##  Managers Table Sql Code
![manager_tbl](https://github.com/user-attachments/assets/2e8ecf55-d710-4b17-91d2-07193a4c5279)
## Managers Table Output
![task5code](https://github.com/user-attachments/assets/8fd14d48-f89a-4211-a036-5e1c124afd43)


## EER Diagram 
![diagram 1](https://github.com/user-attachments/assets/8ca3e8f6-cb85-4cbb-ad98-4c4823f9a366)


## Sql Code
![final1](https://github.com/user-attachments/assets/163b009d-1486-4bf2-b4dc-b443e5396b17)
![final1 1](https://github.com/user-attachments/assets/a35a6660-3730-4351-84c8-a38a3ba2b60e)
## [BACK TO PORTFOLIO](https://tatinzzz.github.io/EDM-Portfolio/)

