# 📘 Student Management App (Express + MongoDB + Pug)

A simple full-stack web application built using **Express.js**, **MongoDB**, and **Pug** templating engine. This project allows users to **Create**, **Read**, **Update**, and **Delete (CRUD)** student records.

## 🚀 Features

- View all students
- Add new students
- Edit existing student details
- Delete student records
- Clean and responsive UI with Pug
- MongoDB integration using Mongoose

---

## 🏗️ Folder Structure


express-pug-students/
├── models/
│ └── Student.js # Mongoose model
├── views/ # Pug templates
│ ├── layout.pug # Base layout
│ ├── index.pug # List all students
│ ├── new.pug # Form to add new student
│ └── edit.pug # Form to edit student
├── public/
│ └── style.css # Optional styling
├── server.js # Main server file
├── package.json
└── README.md


---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone: https://github.com/nagesh-makanapur/express-pug-students.git
cd express-pug-students
  2. Install Dependencies
      npm init -y
      npm install
      npm install express mongoose pug
3. Start MongoDB
    Ensure MongoDB is running on your system (default port 27017).
4. Run the Application
    node server.js

** Technologies Used**

    Backend: Node.js, Express.js

    Database: MongoDB, Mongoose

    Templating Engine: Pug (formerly Jade)

    Styling: Basic CSS

**UI Screens**

    Homepage - List of all students with Edit/Delete buttons

    Add Student - Simple form to enter details

    Edit Student - Pre-filled form to update data

**Sample MongoDB Schema**
    const studentSchema = new mongoose.Schema({
  name: String,
  age: Number,
  course: String
});




