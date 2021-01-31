# Pewlett-Hackard-Analysis Module 7
Using PostgreSQL and pgAdmin

## Overview and Parameters

Pewlett Hackard a well established company with a large and loyal workforce has requested that we develop a list of employees nearing retirement based on age and time with the company the refer to it as the "silver tsunami." We will also develop a list of employees who are eligible to participate in a mentorship program base on their age. Using PostgreSQL, pgAdmin and Entity Relationship Diagrams we will filter, join, and create new tables to deliver a list of eligible employees for retirement or a mentorship program.

### Deliverable 1 : Part 1 The Number of Retiring Employees by Title
Using the Pewlett Hackard supplied csv files we created a visual relationship reference to create a Retirement Titles table that holds all the tiles of current employees who were born between January 1, 1952 and December 31, 1955.
The following tables were used to create the retirement titles data:
1. Employee table
2. Titles table

![retirement_titles](https://github.com/JimmyJ-D/Pewlett-Hackard-Analysis-/blob/main/retirement_titles.png)

### Deliverable 1 : Part 2 Removing Duplicate Entries
It was discovered that over the years employees that had multiple positions had duplicate employees titles in the database. To remove the duplicate entries we used the "DISTINCT ON" statement to create the Unique_Titles table that removed any duplicate employees data.
The following table was used to create the unique titles data:
1. Retirement Titles table

![unique_titles](https://github.com/JimmyJ-D/Pewlett-Hackard-Analysis-/blob/main/unique_titles.png)

### Deliverable 1 : Part 3 Retiring Titles
We provided a condensed table of the number of employees by their most recent job title who are nearing retirement as Retiring Titles table.
The following table was used to create the retiring titles data:
1. Unique Titles table

![retiring_titles](https://github.com/JimmyJ-D/Pewlett-Hackard-Analysis-/blob/main/retiring_titles.png)

### Deliverable 2: The Employees Eligible for the Mentorship Program  
Now that Pewlett Hackard has a condensed table with employees' title, hire date, employee number, and birth date they requested a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
![mentorship_eligibilty](https://github.com/JimmyJ-D/Pewlett-Hackard-Analysis-/blob/main/mentor_eligibility.png)

### Summary:
Pewlett Hackard has over 90,000 employees that are eligible for retirement. While this number is large, employees enter or delay retirement for different reasons. With the silver tsunami on the horizon, Pewlett Hackard should proactively start the global recruiting process of new talent and champion their mentorship program to existing employees to replace senior engineers and staff. 
