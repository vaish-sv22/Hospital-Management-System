# Hospital Management System

A web-based **Hospital Management System (HMS)** developed using **Java Web Technologies** to simplify hospital operations such as patient registration, doctor management, appointment scheduling, and administrative tasks. The application follows the MVC architecture using JSP, Servlets, JDBC, and MySQL, and is deployed on the Apache Tomcat Server.

---

## Features

### Admin Module
- Admin login authentication
- Add, update, and delete doctors
- Manage doctor specializations
- View registered patients
- View and manage appointments
- Change password

### Doctor Module
- Secure doctor login
- View assigned appointments
- View patient details
- Update appointment status
- Edit profile information
- Change password

### Patient Module
- User registration and login
- Book appointments with doctors
- View appointment history
- Update account password

---

## Technologies Used

### Frontend
- HTML
- CSS
- Bootstrap
- JSP (JavaServer Pages)

### Backend
- Java
- Java Servlets
- JDBC

### Database
- MySQL

### Server
- Apache Tomcat

### Development Tools
- Eclipse IDE
- Maven

---

## Project Architecture


Client (Browser)
        │
        ▼
 JSP Pages (View)
        │
        ▼
Java Servlets (Controller)
        │
        ▼
DAO Layer (JDBC)
        │
        ▼
MySQL Database


---

## Software Requirements

- Java JDK 8 or above
- Apache Tomcat 9.x
- MySQL Server
- Eclipse IDE (Enterprise Edition)
- Maven

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Hospital-Management-System.git
```

### 2. Import the project

- Open Eclipse IDE
- Import the project as a **Maven Project**

### 3. Configure the Database

- Create a MySQL database.
- Import the provided `hospitals.sql` file.
- Update the database credentials in `DBConnection.java`.

### 4. Configure Apache Tomcat

- Add Apache Tomcat to Eclipse.
- Deploy the project to the server.

### 5. Run the Application

Start the Tomcat server and open:

```
http://localhost:8080/MediCare/
```

---

## Workflow

1. Patient registers and logs into the system.
2. Patient books an appointment with a doctor.
3. Admin manages doctors and appointments.
4. Doctor logs in to view assigned appointments.
5. Doctor updates appointment status.
6. Patient can track appointment details.

---

## Database

The application uses **MySQL** to store:

- Patient Details
- Doctor Information
- Admin Information
- Appointment Records
- Doctor Specializations

---

## Key Concepts Implemented

- Java Servlets
- JSP
- JDBC Connectivity
- MVC Architecture
- Session Management
- CRUD Operations
- Form Validation
- Authentication & Authorization
- Maven Project Structure

---

## Learning Outcomes

This project provided practical experience with:

- Java Enterprise Web Development
- Apache Tomcat Deployment
- MySQL Database Design
- JDBC Connectivity
- MVC Design Pattern
- Session and Authentication Management
- CRUD Application Development


## License

This project is developed for educational and learning purposes.
