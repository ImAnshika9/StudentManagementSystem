# Student Management System (Java Swing + JDBC + MySQL)

This repository contains my Student Management System desktop application developed in Java using Swing for GUI, JDBC for database connectivity, and MySQL for persistent storage.

Download the ZIP file to view the full source code and project structure.

## 🛠 Tech Stack
- Java (Swing GUI)
- MySQL
- JDBC Connector
- Eclipse IDE

## 📦 Features
- Add Student
- Update Student
- Delete Student
- View All Students
- GUI Interface
- Validation & Error Handling

## ▶ How to Run
1. Download and extract the ZIP
2. Import the project into Eclipse IDE
3. Add MySQL JDBC connector JAR to Build Path
4. Create database using provided SQL structure
5. Update DB credentials in `DBConnection.java`
6. Run `Main.java`

## 🗄 Database Structure
```sql
CREATE DATABASE studentdb;
USE studentdb;

CREATE TABLE students (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(50),
  email VARCHAR(80),
  course VARCHAR(50)
);
