# Student Management System

A simple CRUD (Create, Read, Update, Delete) Student Management System built using **Angular** for the frontend and **Spring Boot** for the backend, with a **MySQL** database.

## 📁 Project Structure
```
Student management system/
│-- Spring_CRUD/     # Backend - Spring Boot
│-- Angular_crud/    # Frontend - Angular
│-- README.md        # Project documentation
```

## 🛠️ Technologies Used
- **Frontend:** Angular, TypeScript, Bootstrap
- **Backend:** Spring Boot, Java, Spring Data JPA
- **Database:** MySQL

## 🚀 How to Run

### **Backend (Spring Boot)**
1. Navigate to the `Spring_CRUD` folder:
   ```bash
   cd Spring_CRUD
   ```
2. Configure your `application.properties` with your MySQL credentials.
3. Build and run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

### **Frontend (Angular)**
1. Navigate to the `Angular_crud` folder:
   ```bash
   cd Angular_crud
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the Angular development server:
   ```bash
   ng serve
   ```
4. Open the browser and go to `http://localhost:4200`

## 📌 Features
- Add new students
- View all students
- Update student details
- Delete students
