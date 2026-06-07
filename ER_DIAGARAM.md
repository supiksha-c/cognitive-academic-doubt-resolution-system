ER Diagram Description

Entities

Student

- Student_ID
- Name
- Email
- Password

Faculty

- Faculty_ID
- Name
- Email
- Password

Doubt

- Doubt_ID
- Student_ID
- Subject
- Doubt_Title
- Doubt_Description

Answer

- Answer_ID
- Doubt_ID
- Faculty_ID
- Answer_Text

Category

- Category_ID
- Category_Name

Relationships

- One Student can submit many Doubts.
- One Faculty can answer many Doubts.
- One Doubt can have multiple Answers.
- One Category can contain multiple Doubts.
