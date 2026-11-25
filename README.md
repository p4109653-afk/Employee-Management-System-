
# 👨‍💼 Employee Management System

<p align="center">
  A simple and user-friendly Employee Management System built with Python, Tkinter, and MySQL.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-MySQL-orange?logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/GUI-Tkinter-green" />
  <img src="https://img.shields.io/badge/Project-Beginner%20Friendly-brightgreen" />
</p>

---

## 📌 About the Project

The **Employee Management System** is a desktop application developed using Python and MySQL to manage employee records efficiently.

It provides a simple graphical user interface where users can add, view, update, and delete employee information.

This project helped me practice Python programming, database connectivity, SQL queries, and CRUD operations.

## ✨ Features

- ➕ Add new employee records
- 📋 View all employee details
- ✏️ Update existing employee information
- 🗑️ Delete employee records
- 🔄 Refresh employee data
- 🧹 Clear input fields
- ✅ Input validation for salary and age
- 🗄️ Automatic database and table creation
- 🖥️ User-friendly graphical interface

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application development |
| Tkinter | Graphical User Interface (GUI) |
| MySQL | Database management |
| mysql-connector-python | Python-MySQL connectivity |

## 📂 Project Structure

```text
Employee-Management-System/
│
├── app.py          # Main application and GUI
├── database.py     # Database connection and CRUD operations
├── README.md       # Project documentation
└── .gitignore      # Files excluded from Git
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Employee-Management-System.git
```

### 2. Navigate to the project folder

```bash
cd Employee-Management-System
```

### 3. Install the required package

```bash
pip install mysql-connector-python
```

### 4. Configure MySQL

Make sure MySQL Server is installed and running.

Update your MySQL username and password in `database.py` according to your MySQL configuration.

The application automatically creates the database and employees table when it connects for the first time.

### 5. Run the application

```bash
python app.py
```

## 🗃️ Database Details

**Database Name:** `employee_management`

**Table Name:** `employees`

| Column | Description |
|---|---|
| employee_id | Unique employee ID |
| employee_name | Employee name |
| salary | Employee salary |
| department | Employee department |
| age | Employee age |
| gender | Employee gender |

## 📚 Concepts Practiced

- Python functions
- Tkinter GUI development
- MySQL database connectivity
- SQL CRUD operations
- Exception handling
- Input validation
- Python modules and imports
- Database transactions

## 🎯 Project Objective

The main objective of this project is to develop a simple desktop application that makes employee record management easier and demonstrates the practical use of Python with a MySQL database.

## 👩‍💻 Developer

**Purvi Jain**

Aspiring Data Analyst | Python | SQL | MySQL

---

⭐ If you find this project useful, feel free to star the repository!

