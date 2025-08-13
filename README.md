# Capstone-Project---Python

**Project Overview**
This capstone project was designed to demonstrate proficiency in Python programming, particularly using Pandas and NumPy for data manipulation and analysis. The project simulates a real-world scenario involving employee data, project assignments, and performance evaluations.

**Dataset Description**
The project uses three datasets:

Employee DataFrame: Contains employee ID, name, gender, city, and age.
Seniority Level DataFrame: Maps employee ID to their designation level.
Project DataFrame: Includes project details such as ID, project name, cost, and status.

**Tasks Performed**
Task 1: Data Preparation
Created three separate DataFrames from raw data.
Saved each DataFrame as a .csv file for further use.

Task 2: Handling Missing Values
Identified missing values in the cost column of the Project DataFrame.
Replaced missing values using a running average calculated via a for loop.

Task 3: Column Transformation
Split the name column in the Employee DataFrame into First Name and Last Name.
Removed the original name column.

Task 4: Data Merging
Merged all three DataFrames into a single consolidated DataFrame named Final.

Task 5: Bonus Calculation
Added a new column bonus to the Final DataFrame.
Applied a 5% bonus on project cost for employees who completed their projects.

Task 6: Demotion Logic
Demoted designation level by 1 for employees with failed projects.
Removed employees whose designation level exceeded 4.

Task 7: Title Assignment
Added “Mr.” or “Mrs.” to the First Name based on gender.
Dropped the gender column.

Task 8: Promotion Logic
Promoted designation level by 1 for employees older than 29 years using an if condition.

Task 9: Project Cost Aggregation
Created a new DataFrame TotalProjCost with total project cost per employee.
Included columns: ID, First Name, and Total Cost.

Task 10: City-Based Filtering
Filtered and printed employee details where the city name contains the letter “o”.

**Tools & Libraries Used**
Python
Pandas
NumPy
Jupyter Notebook


**Learning Outcome**
This project helped reinforce core Python skills including:

Data cleaning and transformation
Conditional logic and loops
Data aggregation and filtering
Real-world problem-solving using Pandas
