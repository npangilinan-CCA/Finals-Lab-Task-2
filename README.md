# [Finals Lab Task 2 - Transforming ER Model to Relational Tables](https://github.com/user-attachments/files/19789037/pangilinan_FinalsLabTask2.docx)
This portfolio is about converting an Entity-Relationship (ER) diagram—centered on student assignment submissions—into a set of MySQL database tables. It involves capturing all relevant entities along with their attributes, and establishing the relationships between students, assignments, and their submissions.

## Step by Step Process
### Creating the student table
- Define username as a VARCHAR (up to 50 characters).
  
### Creating the assignment table
- Define shortname as a VARCHAR (up to 50 characters).
- Define due_date as a date and make it not null.
- Define url as a VARCHAR (up to 255 characters)
  
### Creating the submission table
- Define username as a VARCHAR (up to 50 characters), which will be a foreign key referencing username in the students table.
- Define shortname as a VARCHAR (up to 50 characters), which will be a foreign key referencing shortname in the assignment table.
- Define version as an integer.
- Define submit_date as a date and make it not null.
- Define data as a text.
- Set a composite primary key on the combination of usernmame, shortname, and version.
  

## Query Statements and Table Structures
### Student Table
![Image](https://github.com/user-attachments/assets/155ed6f1-3088-444c-874a-459e0a098ff7)

### Assignment Table
![Image](https://github.com/user-attachments/assets/9c4100c7-c5a4-4792-a9ee-77063b6b9025)

### Submission Table
![Image](https://github.com/user-attachments/assets/82f5c7a6-fd44-4295-805b-a421c225054e)

## EER Diagram
![Image](https://github.com/user-attachments/assets/8e79be44-33a1-4780-be4b-a085b60ca3d0)


