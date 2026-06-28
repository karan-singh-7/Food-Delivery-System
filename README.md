<div align="center">

# 🍔 Food Delivery System

### A Backend RESTful Food Delivery Application built with Java & Spring Boot

[![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-green?style=for-the-badge&logo=springboot)](https://spring.io/projects/spring-boot)
[![Hibernate](https://img.shields.io/badge/Hibernate-ORM-brown?style=for-the-badge&logo=hibernate)]
[![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)]
[![Maven](https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apachemaven)]
[![Git](https://img.shields.io/badge/Git-Version_Control-orange?style=for-the-badge&logo=git)]

Developed by **Karan Singh**

</div>

---

# 📖 Overview

The **Food Delivery System** is a backend REST API application developed using **Java**, **Spring Boot**, **Spring Data JPA**, **Hibernate**, and **MySQL**.

The application enables customers to browse restaurants, order food, manage carts, and place orders while providing administrators with features to manage restaurants, food items, and categories.

The project follows **Layered Architecture**, making it scalable, maintainable, and easy to understand.

---

# 🚀 Features

### 👤 User Management

- User Registration
- User Login
- User Profile Management

### 🏪 Restaurant Management

- Add Restaurant
- Update Restaurant
- Delete Restaurant
- View Restaurant Details

### 🍕

Food Management

- Add Food Items
- Update Food Items
- Delete Food Items
- View Food Menu

### 📂 Category Management

- Add Category
- Update Category
- Delete Category

### 🛒 Cart Management

- Add Item to Cart
- Remove Item
- Update Quantity
- View Cart

### 📦 Order Management

- Place Order
- View Orders
- Order History

---

# 🛠 Tech Stack

## Backend

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

## Database

- MySQL

## Build Tool

- Maven

## Testing

- Postman
- JUnit 5
- Mockito

## Logging & Code Quality

- SLF4J
- SonarQube

## Version Control

- Git
- GitHub

---

# 📂 Project Structure

```
Food-Delivery-System
│
├── src
│   ├── main
│   │   ├── java
│   │   │
│   │   ├── controller
│   │   ├── service
│   │   ├── repository
│   │   ├── entity
│   │   ├── dto
│   │   ├── config
│   │   ├── exception
│   │   └── FoodDeliveryApplication
│   │
│   └── resources
│       ├── application.properties
│       └── static
│
└── pom.xml
```

---

# 🏗 Architecture

The project follows a **Layered Architecture**.

```
Client
   │
   ▼
Controller Layer
   │
   ▼
Service Layer
   │
   ▼
Repository Layer
   │
   ▼
MySQL Database
```

---

# 💾 Database

- MySQL Database
- Spring Data JPA
- Hibernate ORM
- Entity Relationships

---

# 📡 REST APIs

The project exposes REST APIs for:
- Users
- Restaurants
- Categories
- Food Items
- Cart
- Orders

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/karan-singh-7/Food-Delivery-System.git
```

Move to the project

```bash
cd Food-Delivery-System
```

Configure database

```
src/main/resources/application.properties
```

Example

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/food_delivery

spring.datasource.username=root

spring.datasource.password=your_password
```

Build

```bash
mvn clean install
```

Run

```bash
mvn spring-boot:run
```

Application URL

```
http://localhost:8080
```

---

# 🧪 Testing

The APIs were tested using:

- Postman
- JUnit 5
- Mockito

---

# 💡 Concepts Used

- Object-Oriented Programming
- Spring Boot
- Dependency Injection
- REST APIs
- CRUD Operations
- Spring Data JPA
- Hibernate ORM
- Exception Handling
- Validation
- Layered Architecture
- Maven
- Git

---

# 📈 Future Enhancements

- JWT Authentication
- Payment Gateway Integration
- Email Notification
- Docker Deployment
- Swagger API Documentation
- Redis Cache
- Microservices Architecture

---


# 👨‍💻 Developer

**Karan Singh**

📧 Email: karan.sf234@gmail.com

🔗 GitHub Profile

https://github.com/karan-singh-7

🔗 Project Repository

https://github.com/karan-singh-7/Food-Delivery-System

---

# ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It motivates me to build more projects and contribute to open source.

---

<div align="center">

### ⭐ Star this repository if you like it!

Made with ❤️ using Java & Spring Boot

</div>
