# 🏥 Hospital Management System

A modern Full Stack Hospital Management System built using **React.js**, **Spring Boot**, **Spring Security**, **JWT Authentication**, and **MySQL**. The application provides secure role-based access for Administrators, Doctors, and Patients while streamlining appointment scheduling, patient management, and medical record handling.

---

## 📖 Overview

This project demonstrates a production-style healthcare management platform developed using modern full-stack technologies. The system enables hospitals and clinics to manage doctors, patients, appointments, and medical records through a secure and scalable architecture.

---

## ✨ Features

### 🔐 Authentication & Security
- JWT Authentication
- Spring Security
- Role-Based Access Control (RBAC)
- Protected REST APIs
- Secure Login & Logout

### 👨‍💼 Admin Module
- Doctor Management
- Patient Management
- Appointment Management
- Department Management
- Dashboard Analytics

### 👨‍⚕️ Doctor Module
- View Assigned Patients
- Manage Appointments
- Update Treatment Status
- Access Medical Records
- Daily Schedule Management

### 🧑‍🤝‍🧑 Patient Module
- Patient Registration
- Profile Management
- Appointment Booking
- Appointment History
- Medical Record Access

### 📅 Appointment Management
- Schedule Appointments
- Update Appointment Status
- Doctor Availability Tracking
- Patient Appointment History

### 📊 Dashboard & Analytics
- KPI Statistics
- Doctor Count
- Patient Count
- Appointment Reports
- Interactive Dashboard

---

# 🛠 Technology Stack

| Layer | Technologies |
|---------|-------------|
| Frontend | React.js, JavaScript, HTML5, CSS3, Bootstrap, Axios, React Router |
| Backend | Java, Spring Boot, Spring Security, JWT, REST APIs, Maven |
| Database | MySQL |
| Tools | Git, GitHub, Postman, VS Code, Eclipse, MySQL Workbench |

---

# 📂 Project Structure

```text
hospital-management-system/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   ├── mvnw
│   └── ...
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/sanket9322/hospital-management-system.git
cd hospital-management-system
```

---

## Backend Setup

```bash
cd backend
```

Configure database settings inside:

```text
src/main/resources/application.properties
```

Run backend:

```bash
mvn spring-boot:run
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

# 🗄 Database Configuration

Create a MySQL database:

```text
hospital_db
```

Update:

```properties
spring.datasource.url=
spring.datasource.username=
spring.datasource.password=
```

Import the SQL schema before starting the application.

---

# 🔒 Security Features

- JWT Authentication
- Spring Security
- Password Encryption
- Role-Based Authorization
- Protected API Endpoints

---

# 📡 REST API Modules

- Authentication
- Doctor Management
- Patient Management
- Appointment Management
- Medical Records
- Dashboard Analytics

---

# 📸 Screenshots

Create a folder:

```text
screenshots/
```

Add screenshots such as:

```text
screenshots/
├── login.png
├── admin-dashboard.png
├── doctor-dashboard.png
├── patient-dashboard.png
├── appointments.png
└── medical-records.png
```

---

# 🚀 Future Enhancements

- Email Notifications
- SMS Integration
- Prescription Management
- Laboratory Module
- Billing & Payments
- Docker Deployment
- AWS Cloud Deployment
- CI/CD Pipeline

---

# 🎯 Learning Outcomes

This project demonstrates practical experience in:

- Full Stack Java Development
- Spring Boot
- Spring Security
- JWT Authentication
- React.js
- REST API Development
- MySQL Database Design
- CRUD Operations
- Enterprise Application Architecture
- Role-Based Access Control

---

# 👨‍💻 Author

**Sanket Telgar**

**Full Stack Java Developer**

- GitHub: https://github.com/sanket9322
- LinkedIn: https://www.linkedin.com/in/sanket-telgar
- Email: sankettelgar9322@gmail.com

---

## ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
