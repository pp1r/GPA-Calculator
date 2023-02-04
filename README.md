GPA Calculator
Team Members
Sulaiman
Abdulkarim
Abdulmjed
Description
This GPA Calculator calculates your total GPA and semester GPA. Your GPA, semester GPA and degree status will be shown to you by this program. The GPA specializes in helping students determine their GPA during different study periods. It is a very accurate and easy-to-use service, made using the C programming language, making it usable on computers.

Features and Capabilities
Search by University ID
Delete record by University ID
Change student name or grade or both
Error message displayed if ID number already exists
User Manual
Insert new record
Display the record
Search by University ID
Delete a record by University ID
Update a record by University ID
Sort all records
Exit
Flow Chart
See here for a description of the flow chart.

Custom Functions
In this project, we have created eight functions to meet project requirements:

void insert(): inserts records into the file. A file is created, then a registry is opened and the following is inserted:
University ID
Student name
Number of subjects
Grades and number of hours
Semester GPA and cumulative grade are calculated based on number of subjects.
void search(): searches for a given record through the ID and displays:
ID
Student name
Total
GPA
Number of hours
void deletefile(): deletes a record by ID.
void update(): updates an existing record with the identifier and can update:
Name only
Total only
Name and total
void disp(): displays the contents of the record, including:
ID
Student name
Total
GPA
Number of hours
void sort(): sorts the records.
int avlsub(int rno): checks if the given ID number is available.
int empty(): checks if the file is empty.
C Standard Library Functions Used
<stdlib.h>: C Standard General Utilities Library. Defines several general purpose functions.
<stdio.h>: defines three variable types, several macros, and various functions for input and output.
Task Breakup
The team worked on the code together using the website Repl.it, which allows for simultaneous code entry with colleagues.
