# Java Core JDBC Online Examination System

This project is a Java-based Online Examination System developed using **Core Java**, **JDBC**, and **MySQL**.  
It enables students to take online examinations and allows administrators to manage exams, questions, and results.

---

## 🔧 Technologies Used
- Core Java
- JDBC
- MySQL
- JSP (Presentation Layer)
- Maven
- Apache Tomcat

---

## 📌 Key Features

### Admin
- Create and manage exams
- Add and manage questions
- Manage students and batches
- Publish notices
- View examination results

### Student
- Secure login
- View available exams
- Attend MCQ-based exams
- Automatic evaluation
- View results

---

## 🛢️ Database Design

### Main Tables
- User – authentication and roles  
- Student – student profile data  
- Exam – exam information  
- Question – MCQ questions  
- Answer – submitted answers  
- Result – exam results  
- Batch / Enroll – student–exam mapping  

---

## 🔐 Security
- PreparedStatement used to prevent SQL Injection
- OTP-based email verification
- Centralized database connection handling

---

## ▶️ How to Run
1. Clone the repository  
2. Import as a Maven project  
3. Configure database credentials  
4. Deploy on Apache Tomcat  
5. Access via browser  

---

## 🎯 Objective
To demonstrate a complete Java backend workflow using Core Java and JDBC with a structured and maintainable architecture.

---

## 👨‍💻 Author
Garvesh
