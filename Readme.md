# Student Management System

## 📌 Project Description

The Student Management System is a web-based application developed using **Python FastAPI, HTML, CSS, JavaScript, and a database**.

This application helps manage student information efficiently. Users can add, view, update, and delete student records. It also provides attendance management and student image display functionality.

## 🚀 Features

- Add new student details.
- View all student records.
- Edit existing student information.
- Delete student records.
- Manage attendance (Present/Absent).
- Store and display student image URLs.
- Manage student name, age, gender, course, and marks.
- User-friendly interface.
- Responsive design.

## 🛠️ Technologies Used

**Frontend:**
- HTML5
- CSS3
- JavaScript
- Jinja2 Templates

**Backend:**
- Python
- FastAPI
- Uvicorn

**Database:**
- MySQL / SQLite

## 📂 Project Structure

```text
Student-Management-System/
│
├── main.py
│
├── templates/
│   ├── index.html
│   ├── add_student.html
│   ├── view_students.html
│   └── edit_student.html
│
├── static/
│   ├── css/
│   ├── images/
│   └── js/
│
├── requirements.txt
│
└── README.md
```

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
```

### Step 2: Navigate to the Project Folder

```bash
cd Student-Management-System
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### Step 4: Install Required Packages

```bash
pip install fastapi uvicorn jinja2 python-multipart
```

Install your database driver if required.

### Step 5: Run the Application

```bash
uvicorn main:app --reload
```

### Step 6: Open the Application

Visit the following URL in your browser:

```text
http://127.0.0.1:8000/
```

### Step 7: Explore API Documentation

FastAPI automatically generates interactive API documentation.

**Swagger UI:**

```text
http://127.0.0.1:8000/docs
```

**ReDoc:**

```text
http://127.0.0.1:8000/redoc
```

## 📋 Student Details

| Field | Description |
|---|---|
| ID | Unique student ID |
| Name | Student name |
| Age | Student age |
| Gender | Student gender |
| Course | Student course |
| Marks | Student marks |
| Image | Student image URL |
| Attendance | Present or Absent |

## 🔄 Application Modules

1. **Add Student:** Add new student information to the database.
2. **View Students:** Display all registered student records.
3. **Edit Student:** Update existing student details.
4. **Delete Student:** Remove student records.
5. **Attendance Management:** Update student attendance status.

## 🎯 Project Objective

The main objective of this project is to develop a simple and efficient student management application using FastAPI. It reduces manual work and makes student record management easier.

## 🔮 Future Enhancements

- Student login and authentication.
- Admin dashboard.
- Attendance reports.
- Search and filter students.
- Export student details to PDF or Excel.
- Direct student image uploads.
- Improved security and data validation.

## 👨‍💻 Author

**Developer:** Your Name

## 📄 License

This project is developed for educational and learning purposes.