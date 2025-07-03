# 📱 Smart Habit Tracker

Smart Habit Tracker is a full-stack web application built using **Spring Boot**, **Thymeleaf**, **MySQL**, and **Spring Security** that helps users track their habits, monitor progress, and stay motivated through a notification system.

---

## 👥 Team Members
- Nand Kapatel
- Srushti Chavan
- [Add more if applicable]

---

## 🌟 Features
- ✅ User Registration and Login with secure authentication
- 📅 Track daily, weekly, and custom habits
- 📊 Dashboard showing habit progress
- 🔔 Notification system for reminders and updates
- 🧑‍💼 Admin/User roles
- 🎨 Responsive UI with Thymeleaf templating
- 🛡️ Password encryption using BCrypt

---

## 🧱 Technologies Used
- Java 21
- Spring Boot 3.3.11 (SNAPSHOT)
- Spring Security
- Spring Data JPA
- Thymeleaf
- MySQL
- Maven
- Lombok

---

### Set up MySQL Database:
Create a database named:
```sql
CREATE DATABASE habittracker;
```

### Configure `application.properties`:
Update `src/main/resources/application.properties` with your DB credentials:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/habittracker
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

###  Build and run the project:
```bash
mvn clean install
mvn spring-boot:run
```

---

## 🔒 Default Roles
- **USER** - Can manage own habits
- **ADMIN** - Has full access to manage all users

---

## 📄 License
This project is for educational purposes under LaSalle College guidelines.