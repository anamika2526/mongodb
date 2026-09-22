NoSQL Student Management System using MongoDB

📌 Project Overview

This project is a Student Management System developed using MongoDB, a NoSQL database. It demonstrates how student records can be stored, managed, queried, updated, and deleted using MongoDB.

The project covers basic MongoDB database operations such as creating databases and collections, inserting documents, querying data, updating records, deleting records, and using MongoDB query operators.

🎯 Objectives

- To understand the basics of NoSQL databases.
- To learn MongoDB database and collection creation.
- To store student information in MongoDB documents.
- To perform CRUD operations.
- To use MongoDB query operators for searching and filtering data.
- To understand how MongoDB can be used for student record management.

🛠️ Technologies Used

- MongoDB
- MongoDB Compass / MongoDB Shell
- NoSQL
- JSON/BSON Documents

📂 Student Information

The student records may contain information such as:

- Student ID
- Student Name
- Age
- Gender
- Course
- Semester
- Email
- Phone Number
- Marks
- City

🔧 MongoDB Operations Covered

1. Create Database and Collection

A database and student collection are created to store student records.

2. Insert Documents

Student information is inserted into the MongoDB collection.

3. Read / Query Documents

MongoDB queries are used to retrieve student records based on different conditions.

4. Update Documents

Existing student information can be modified using update operations.

5. Delete Documents

Student records can be removed from the collection when required.

6. Query Operators

The project demonstrates MongoDB operators such as:

- "$gt"
- "$gte"
- "$lt"
- "$lte"
- "$eq"
- "$ne"
- "$in"
- "$nin"
- "$and"
- "$or"

📊 Example Queries

// Display all students
db.students.find()

// Find students whose marks are greater than 80
db.students.find({ marks: { $gt: 80 } })

// Find students belonging to BCA
db.students.find({ course: "BCA" })

// Update a student's marks
db.students.updateOne(
    { student_id: 101 },
    { $set: { marks: 90 } }
)

// Delete a student
db.students.deleteOne({ student_id: 101 })

📁 Project Structure

NoSQL-Student-Management-MongoDB-Project/
│
├── README.md
├── MongoDB_Commands/
│   └── student_management.js
│
├── Screenshots/
│   ├── database.png
│   ├── collection.png
│   ├── insert.png
│   ├── query.png
│   ├── update.png
│   └── delete.png
│
└── Documentation/
    └── Project_Report.pdf

🚀 How to Run the Project

1. Install MongoDB on your computer.
2. Open MongoDB Compass or MongoDB Shell.
3. Create the student database and collection.
4. Run the MongoDB commands provided in the project.
5. Perform insert, query, update, and delete operations.
6. Verify the results in MongoDB Compass or MongoDB Shell.

📸 Screenshots

Screenshots of database creation, document insertion, queries, updates, and deletion operations can be added to the "Screenshots" folder.

👩‍💻 Author

Anamika Gupta

BCA – Data Science & AI

📄 License

This project is created for educational and academic purposes.
