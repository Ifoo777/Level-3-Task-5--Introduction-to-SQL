# Level 3 Task 4 -Introduction to SQL

## Task

Answer the following questions:

● Go to the w3schools website’s SQL browser IDE(https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all). 

This is where you can write and test your SQL code using their databases. Once you are happy with it, paste your code in a text file named Student.txt and save it in your task folder.

● Write the SQL code to create a table called Student. The table structure is summarised in the table below (Note that STU_NUM is the primary key):

Attribute Name, Data Type
STU_NUM, CHAR(6)
STU_SNAME, VARCHAR(15)
STU_FNAME, VARCHAR(15)
STU_INITIAL, CHAR(1)
STU_STARTDATE, DATE
COURSE_CODE, CHAR(3)
PROJ_NUM, INT(2)

● After you have created the table in question 1, write the SQL code to enter the first two rows of the table as below:

STU_NUM, STU_SNAME, STU_FNAME, STU_INITIAL, STU_STARTDATE, COURSE_CODE, PROJ_NUM 
01, Snow, John, E, 05-Apr-14, 201, 6
02, Stark, Arya, C, 12-Jul-17, 305, 11

● Assuming all the data in the Employee table has been entered as shown below, write the SQL code that will list all attributes for a COURSE_CODE of 305.

STU_NUM, STU_SNAME, STU_FNAME, STU_INITIAL, STU_STARTDATE, COURSE_CODE, PROJ_NUM
01, Snow, Jon, E, 05-Apr-14, 201, 6
02, Stark, Arya, C, 12-Jul-17, 305, 11
03, Lannister, Jamie, C, 05-Sep-12, 101, 2
04, Lannister, Cercei, J, 05-Sep-12, 101, 2
05, Greyjoy, Theon, I, 9-Dec-15, 402, 14
06, Tyrell, Margaery, Y, 12-Jul-17, 305, 10
07, Baratheon, Tommen, R, 13-Jun-19, 201, 5

● Write the SQL code to change the course code to 304 for the person whose student number is 07.

● Write the SQL code to delete the row of the person named Jamie Lannister, who started on 5 September 2012, whose course code is 101 and project number is 2. Use logical operators to include all of the information given in this problem.

● Write the SQL code that will change the PROJ_NUM to 14 for all those students who started before 1 January 2016 and whose course code is at least 201.

● Write the SQL code that will delete all of the data inside a table, but not the table itself.

● Write the SQL code that will delete the Student table entirely.
