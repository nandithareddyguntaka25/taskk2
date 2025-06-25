# taskk2
This project demonstrates basic SQL operations—CREATE, INSERT, UPDATE, DELETE, and SELECT—on a simple Student table. It also includes a final exported dataset as a .csv file.

Table Structure
The Student table includes the following columns:

StudentID (Primary Key)

Name

Age (Default value: 18)

Email (Optional)

🛠 SQL Operations Performed
Create Database and Table
Creates a stud database and a Student table with default and nullable fields.

Insert Records
Inserts multiple students with variations:

With full data

With missing Email (NULL)

With missing Age (uses default)

Update Data
Updates a student's missing email using their StudentID.

Delete Record
Deletes a specific student record from the table.

View Table
Displays the final state of the table.

Output
The final dataset contains the active student records and is available as a CSV file:
Final_Student_Table.csv
