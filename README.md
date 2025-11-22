# Job-Portal

A Java-based RESTful API for a Job Portal Application built using **Servlets** and **MySQL**.  
This backend system manages **user authentication**, **job applications**, **organizations**, and **job listings** for a job portal.

---

## 🚀 Features

### 🔐 Authentication
- User Registration (JSON)
- User Login (JSON)
- Session-based authentication

### 👥 User Roles
- **Job Seeker**
- **Employer / Organization**

### 📄 Job Listings & Applications
- Fetch all organizations (GET)
- Fetch all job listings (GET)
- Apply for a job (POST)
- Employer can post jobs (POST)

### 🔒 Security
- Secure MySQL interaction using **Prepared Statements**
- Role-based access handling

---

## 🧑‍💻 Tech Stack

- **Java Servlet API**
- **Apache Tomcat**
- **MySQL Database**
- **JDBC (Prepared Statements)**
- **JSON Processing** (`javax.json`)
