# 🏋️ Fitness Management System

A modern Fitness Management System built using **Spring Boot** that helps users manage their fitness journey through workout plans, nutrition tracking, progress monitoring, and secure authentication.

## 🚀 Features

- 🔐 JWT Authentication & Authorization
- 👥 Role-Based Access Control (Admin/User)
- 🏋️ Workout Management
- 🥗 Nutrition & Meal Planning
- 📈 Progress Tracking
- 👤 User Profile Management
- 🔄 RESTful APIs
- 🗄️ MySQL Database Integration
- 📖 Swagger/OpenAPI Documentation
- 🛡️ Spring Security Integration

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- Maven

### Database
- MySQL

### Authentication
- JWT (JSON Web Token)

### Documentation
- Swagger / OpenAPI

### Development Tools
- IntelliJ IDEA
- Postman
- Git & GitHub
- Docker (Optional)

---

## 📂 Project Structure

```
src
├── controller
├── service
├── repository
├── model
├── dto
├── security
├── config
├── exception
└── util
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/fitness-management-system.git
```

### Navigate to project

```bash
cd fitness-management-system
```

### Configure Database

Update the `application.properties` file with your MySQL credentials.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fitness_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### Run the project

```bash
mvn spring-boot:run
```

or

Run `FitnessMonolithApplication.java` from IntelliJ IDEA.

---

## 🔑 API Authentication

1. Register a new user.
2. Login to receive a JWT token.
3. Add the token in the Authorization header:

```
Authorization: Bearer <your_jwt_token>
```

---

## 📚 API Documentation

After running the application:

```
http://localhost:8080/swagger-ui/index.html
```

---

## 📌 Future Enhancements

- Email Verification
- Password Reset
- Exercise Recommendations
- AI-Based Workout Suggestions
- Cloud Deployment
- Mobile Application Integration
- Docker & Kubernetes Deployment

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

---

## 👩‍💻 Author

**Kirti Sharma**

GitHub: https://github.com/kirtisharma1111
