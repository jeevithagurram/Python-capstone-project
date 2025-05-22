# Python-capstone-project
🐍 Python Fundamentals Capstone Project
This repository contains the Capstone Project for the Python Fundamentals course. It demonstrates the ability to clean, transform, and analyze data using pandas, NumPy, and Python core concepts.

📌 Project Objective
To evaluate and enhance data handling, transformation, and business logic implementation skills using Python. This capstone involves a fictional employee-project dataset and requires applying logic to simulate a real-world data processing workflow.

🧾 Dataset Description
There are three primary datasets:

1. Employee DataFrame
Contains employee demographic information.

Column	Description
ID	Employee ID
Name	Full name of the employee
Gender	M or F
City	City of operation
Age	Employee’s age

2. Seniority Level DataFrame
Tracks the designation level of employees.

Column	Description
ID	Employee ID
Designation Level	Scale from 1 (highest) to 4 (lowest)

3. Project DataFrame
Tracks project assignments and their statuses.

Column	Description
ID	Employee ID
Project	Project title
Cost	Project cost (some missing values)
Status	Can be "Finished", "Ongoing", or "Failed"

📊 Tasks Performed
Below are the key operations and transformations applied:

✅ Task 1
Created 3 separate DataFrames and saved them to CSV files.

✅ Task 2
Imputed missing Cost values in the Project DataFrame using running average via a for loop.

✅ Task 3
Split the Name column into First Name and Last Name.

✅ Task 4
Merged all three DataFrames into a single Final DataFrame.

✅ Task 5
Added a Bonus column (5% of cost) for completed projects only.

✅ Task 6
Decreased Designation Level by 1 for failed projects.

Removed employees with designation level greater than 4.

✅ Task 7
Prefixed First Name with "Mr." or "Mrs." based on gender and dropped the gender column.

✅ Task 8
Promoted employees with Age > 29 by reducing their designation level.

✅ Task 9
Created a new DataFrame TotalProjCost summarizing total project costs by employee.

✅ Task 10
Filtered and displayed employees whose city names contain the letter "o".

🧰 Tools & Libraries
Python 3

Jupyter Notebook (.ipynb)

pandas

numpy

📁 Files Included
File Name	Description
Python_Capstone.ipynb	Notebook with code, outputs, and comments
