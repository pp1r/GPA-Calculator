# GPA Calculator

## Contributors
- Sulaiman
- Abdulkarim
- Abdulmjed

## Description
A C programming language based GPA calculator that calculates your total GPA and semester GPA. This program displays your GPA, semester GPA, and degree status to help students determine their GPA during different study periods. The program is accurate and easy to use. 

## Features and Capabilities
1. Search by University ID
2. Delete a record by University ID
3. Update a record by University ID (change name or grade, or both)
4. Error message for duplicate University ID

## User Manual
1. Insert a new record
2. Display the record
3. Search by University ID
4. Delete a record by University ID
5. Update a record by University ID
6. Sort all records
7. Exit

## Flow Chart
See [here](https://app.code2flow.com/MR08iwDH6csZ) for the flow chart description.

## Custom Functions
The project consists of eight functions to meet project requirements:
1. `void insert()`: Inserts records to the file. Creates a file, opens a registry and inserts the following:
    - University ID
    - Student's name
    - The number of subjects
    - Grades and the number of hours
    - Calculates semester GPA and cumulative grade.
2. `void search()`: Searches for a record by ID and displays:
    - ID
    - Student's name
    - Total
    - GPA
    - The number of hours.
3. `void deletefile()`: Deletes a record by ID.
4. `void update()`: Updates an existing record by ID and includes:
    - Name only
    - Total only
    - Name and total.
5. `void disp()`: Displays the contents of a record and includes:
    - ID
    - Student's name
    - Total
    - GPA
    - The number of hours.
6. `void sort()`: Sorts the records.
7. `int avlsub(int rno)`: Checks if the given ID number is available.
8. `int empty()`: Checks if the file is empty or not.

## C Standard Library functions used
1. `<stdlib.h>`: C Standard General Utilities Library. Defines general purpose functions.
2. `<stdio.h>`: Defines variable types, macros, and functions for input and output.
