ER Diagram Description

Entities

Student

- Student_ID (Primary Key)
- Name
- Email
- Password

Faculty

- Faculty_ID (Primary Key)
- Name
- Email
- Password

Doubt

- Doubt_ID (Primary Key)
- Student_ID (Foreign Key)
- Subject
- Doubt_Title
- Doubt_Description

Answer

- Answer_ID (Primary Key)
- Doubt_ID (Foreign Key)
- Faculty_ID (Foreign Key)
- Answer_Text

Category

- Category_ID (Primary Key)
- Category_Name

Relationships

- Student submits Doubts
- Faculty answers Doubts
- Doubts belong to Categories
- Doubts contain Answers
