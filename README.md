# ORM_Querying_Django

Note Each task is defined in the views.py file found in the school_db module.

Find all students and print their first_name, last_name, and GPA to the terminal

Problem One:
Find all students who have a GPA greater than 3.0. 
Order the data by highest GPAs first (descending).
Print out each student's full name and gpa to the terminal

Problem Two:
Find all instructors hired prior to 2010
Order by hire date ascending
Print out the instructor's full name and hire date to the terminal

Problem Three:
Find all courses that belong to the instructor that has the primary key of 2
Print the instructors name and courses that he belongs to in the terminal
(Do not hard code his name in the print)

Problem Four:
Get the count of students, courses, and instructors and print them in the terminal 

Problem Five:
Create a new student in the database. Use your information!
Print the new student's id, full name, year, and gpa to the terminal
NOTE: every time you execute this function a duplicate student will be created with a different primary key number

Problem Six:
Query the previously created student by the id and update the "gpa" to a new value
Then query the students table to get that student by their id
Print the new student's id, full name, and gpa to the terminal

Problem Seven:
Delete the student that you have created and updated
Check your MySQL Workbench to confirm the student is no longer in the table!

Bonus Problem:
Find all of the instructors that only belong to a single course
Print out the instructors full name and number of courses to the console
