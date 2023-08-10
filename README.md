# Analysis-of-students-records

## Introduction
This task of data analysis was done using SQL. In this analysis, SQL was used to create a database and also solve some basic questions. I used PostgreSQL to carry out data analysis.

## Problem Statement
To solve and provide solutions to the following problems and questions.
1. Create a database called Student Record?
2. Create the following tables in the database
   - Student Info (Student ID, Gender, Name, Age, Subject)
   - Health records (Student ID, Blood Group, Height, Weight)
   - Performance (Student ID, Score, Grade)
> The ID has to be unique
> Where a student has no score, it should be '0' by default
> Add a constraint that prevents the ID and Subject from taking null values
> Apply the following modifications to the table
   1. Change the column name "Subject" to "Course"
   2. Drop the "Age" column from the 'Students info' table.

## Skills Demonstrated
1. Creation of Database
2. Creation of Table
3. SELECT * FROM table name
4. Insert Into
5. Values
7. Alter Table
8. Alter Column
9. Adding Constraint

## Data Analysis
I had to create a database in pgadmin4. I made use of PostgreSQL for my SQL task.
Firstly, We had to create a database and to do that, 
- You open your pgadmin4(open source tool for PostgreSQL)
- Click on the server you are working with
- Then right-click on databases and select Create
- Type in the name of your database and then save.

Secondly, We have to create a table inside our database
- Click on the database created
- Then click on Query tool
- Create a table for Students info
- Then type the following code in your query tool

  ![](pic1.png)

- Then type the code SELECT * FROM table_name, which is SELECT * FROM students info to check if the table has been created and if has been created then you would receive a message stating that the query has been successfully returned and you would see the table created.
  ![](pic2.png)
  
- Then you Insert some values into your table
  ![](pic3.png)

- Then type the code SELECT * FROM students info to check if the values have been inserted into the table created then you would receive a message stating that the query has been successfully returned and you would see the table with values created.
  ![](pic4.png)

- Create a table called Health records
  ![](pic5.png)

-  Then type SELECT * FROM health records to check if the table has been created and if has been created then you would receive a message stating that the query has been successfully returned and you would see the table created.
  ![](pic6.png)

- Insert values into the table
  ![](pic7.png)

- Then type the code SELECT * FROM health records to check if the values have been inserted into the table created then you would receive a message stating that the query has been successfully returned and you would see the table with values created.
  ![](pic8.png)

- Create a table called Performance
  ![](pic9.png)

- Then type SELECT * FROM performance to check if the table has been created and if has been created then you would receive a message stating that the query has been successfully returned and you would see the table created.
  ![](pic10.png)

- Insert values into the table
  ![](pic11.png)

- Then type the code SELECT * FROM performance to check if the values have been inserted into the table created then you would receive a message stating that the query has been successfully returned and you would see the table with values created.
  ![](pic12.png)

- Adding constraint that prevents the ID and subject from taking null values
  ![](pic13.png)

- Renaming the Subject column to the Course column
  ![](pic14.png)

- Then type the code SELECT * FROM students info to check if the column name has been changed in the table created then you would receive a message stating that the query has been successfully returned and you would see the table with the column name changed.
  ![](pic15.png)

- Dropping the Age column from the table
  ![](pic16.png)

-  Then type the code SELECT * FROM students info to check if the column name has been dropped in the table created then you would receive a message stating that the query has been successfully returned and you would see that the Age column name has been dropped.
  ![](pic17.png)

## Conclusion
Getting introduced to SQL for the first time, had to understand the basic or starting point of working with SQL which is the 
- SELECT, FROM, INSERT INTO, VALUES, ALTER TABLE, ALTER COLUMNS. 
- Knowing the data type (integer, character, character varying, identity/serial, date, numeric, primary key, foreign key.
Understanding and knowing these concepts is the first and most important step in tackling SQL.

  

  

