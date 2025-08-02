# 🎓 Student Details Management App – Java Swing + JDBC Mini Project


### 📌 Project Overview

A desktop-based application built using **Java Swing**, **JDBC**, and **MySQL** to manage student records through a **user-friendly GUI**. It supports full **CRUD operations** — Add, Update, Delete, and View—integrated with a MySQL database. This project demonstrates real-world form handling, database interaction, and modular GUI design as part of a Java GUI practice series.

---

### 🎯 Objective

- Learn to build GUI-based desktop applications using Java
- Understand JDBC integration for persistent database storage
- Implement real-world form handling and validation
- Practice CRUD operations in a modular, interactive system


### 🧱 Architecture

The project follows a **layered architecture** combining the GUI, database logic, and control flow:

- **UI Layer (Swing)**: Uses `JFrame`, `JPanel`, `JLabel`, `JTextField`, and `JButton` to build the form interface
- **Database Layer (JDBC)**: Interacts with MySQL for executing SQL operations (**insert, update, delete, select**)
- **Control Flow**: Event listeners attached to buttons capture user actions and trigger corresponding database functions
- **Exception Handling**: Catches SQL or connection errors and shows messages to the user


![student-mang-system](https://github.com/ahsan598/js-mini-projects/blob/master/JAVA/student-management-system/screenshots/student-management-system.png)


### 📂 Project Structure

```sh
student-management-system/
├── src/                     # Java source code
│   └── Main.java
├── screenshots/             # UI screenshot for README
│   └── student-management-system.png
├── build.xml                # Build script (used by NetBeans)
└── README.md                # Project overview
```


### 🛠️ Technologies Used

| Tool / Technology | Purpose                          |
|-------------------|----------------------------------|
| Java              | Core programming logic           |
| Swing             | GUI interface                    |
| JDBC              | Database connectivity layer      |
| MySQL             | Data persistence (students table)|
| IntelliJ / Eclipse| Java IDE for development         |



## 🚀 Execution Steps

### 🗂️ Database Requirements

1. **Create MySQL database**:
   ```sql
   CREATE DATABASE student_db;
   USE student_db;

   CREATE TABLE students (
     id INT PRIMARY KEY AUTO_INCREMENT,
     name VARCHAR(100),
     roll_no VARCHAR(50),
     email VARCHAR(100),
     course VARCHAR(100)
   );


2. **Configure JDBC in the Code:**

  - Update DB credentials in your Java file:

    ```java
    String url = "jdbc:mysql://localhost:3306/student_db";
    String user = "root";
    String password = "your_password";
    ```

3. **Compile and Run:**

  ```sh
  javac StudentDetailsApp.java
  java StudentDetailsApp
  ```

> ✅ Make sure the MySQL server is running and connector JAR is added to the classpath if you're using raw terminal.


### 📚 Key Concepts Explored

- GUI design with Java Swing (`JTextField`, `JTable`, `JButton`)
- Event handling using `ActionListener`
- CRUD operations via JDBC
- SQL query execution and result parsing
- Exception handling and user feedback
- Reset/clear logic and input validation (optional)


### 🧠 Learnings

- Gained practical experience integrating Java applications with a relational database
- Learned to structure GUI layouts and bind them to backend logic
- Faced issues with JDBC driver configuration and SQL query execution
- Improved understanding of form-based applications and database error handling


### 📝 Summary

This project provides a complete learning cycle of how Java GUI applications can interact with databases through JDBC. It’s a foundational example of real-world student record management systems and demonstrates how to tie together frontend and backend logic in desktop applications.
