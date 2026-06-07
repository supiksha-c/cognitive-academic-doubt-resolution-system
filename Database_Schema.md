Database Schema

Student Table

Field Name| Data Type
Student_ID| INT (PK)
Name| VARCHAR(100)
Email| VARCHAR(100)
Password| VARCHAR(100)

Faculty Table

Field Name| Data Type
Faculty_ID| INT (PK)
Name| VARCHAR(100)
Email| VARCHAR(100)
Password| VARCHAR(100)

Doubt Table

Field Name| Data Type
Doubt_ID| INT (PK)
Student_ID| INT (FK)
Subject| VARCHAR(100)
Doubt_Title| VARCHAR(200)
Doubt_Description| TEXT

Answer Table

Field Name| Data Type
Answer_ID| INT (PK)
Doubt_ID| INT (FK)
Faculty_ID| INT (FK)
Answer_Text| TEXT

Category Table

Field Name| Data Type
Category_ID| INT (PK)
Category_Name| VARCHAR(100)
