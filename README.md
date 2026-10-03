# 🛒 E-Commerce Full-Stack Platform

A modern full-stack e-commerce web application built using **Java, Spring Boot, React.js, and PostgreSQL**. The project demonstrates complete frontend-backend integration through RESTful APIs, relational database management, and layered backend architecture.

> **Build. Browse. Cart. Checkout.**

---

## 📌 Project Overview

The **E-Commerce Full-Stack Platform** is designed to provide a seamless online shopping experience.

The frontend is developed using **React.js**, while the backend is powered by **Java and Spring Boot**. The application communicates through RESTful APIs, with **PostgreSQL** used for persistent data storage.

The backend follows a layered architecture using **Spring MVC, Hibernate, service layers, repositories, validation, and exception handling**.

---

## ✨ Features

- 🛍️ Product listing and browsing
- 🔎 Product information management
- 🛒 Shopping cart functionality
- 💳 Checkout workflow
- 🔗 RESTful API integration
- 🗄️ PostgreSQL relational database
- ✅ Input validation
- ⚠️ Global exception handling
- 🧩 Reusable React components
- 🔄 Frontend API integration
- 📡 Backend REST API development
- 🧪 API testing using Postman
- 🔧 Git-based source code management

---

## 🛠️ Technologies Used

### Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- REST API Integration

### Backend

- Java
- Spring Boot
- Spring MVC
- Hibernate
- REST APIs
- Exception Handling
- Validation

### Database

- PostgreSQL
- Relational Database Design
- Normalized Database Schemas

### Tools

- Git
- GitHub
- Postman
- IntelliJ IDEA / VS Code
- Maven

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      React.js       │
                    │      Frontend       │
                    └──────────┬──────────┘
                               │
                               │ HTTP / REST API
                               ▼
                    ┌─────────────────────┐
                    │    Spring Boot      │
                    │     Backend         │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
       ┌────────────┐   ┌────────────┐   ┌────────────┐
       │ Controller │   │  Service   │   │ Repository │
       └────────────┘   └────────────┘   └──────┬─────┘
                                                │
                                                ▼
                                      ┌─────────────────┐
                                      │    Hibernate    │
                                      └────────┬────────┘
                                               │
                                               ▼
                                      ┌─────────────────┐
                                      │   PostgreSQL    │
                                      │    Database     │
                                      └─────────────────┘

# 🛒 E-Commerce Full-Stack Platform

A modern full-stack e-commerce web application built using **Java, Spring Boot, React.js, and PostgreSQL**. The project demonstrates complete frontend-backend integration through RESTful APIs, relational database management, and layered backend architecture.

> **Build. Browse. Cart. Checkout.**

---

## 📌 Project Overview

The **E-Commerce Full-Stack Platform** is designed to provide a seamless online shopping experience.

The frontend is developed using **React.js**, while the backend is powered by **Java and Spring Boot**. The application communicates through RESTful APIs, with **PostgreSQL** used for persistent data storage.

The backend follows a layered architecture using **Spring MVC, Hibernate, service layers, repositories, validation, and exception handling**.

---

## ✨ Features

- 🛍️ Product listing and browsing
- 🔎 Product information management
- 🛒 Shopping cart functionality
- 💳 Checkout workflow
- 🔗 RESTful API integration
- 🗄️ PostgreSQL relational database
- ✅ Input validation
- ⚠️ Global exception handling
- 🧩 Reusable React components
- 🔄 Frontend API integration
- 📡 Backend REST API development
- 🧪 API testing using Postman
- 🔧 Git-based source code management

---

## 🛠️ Technologies Used

### Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- REST API Integration

### Backend

- Java
- Spring Boot
- Spring MVC
- Hibernate
- REST APIs
- Exception Handling
- Validation

### Database

- PostgreSQL
- Relational Database Design
- Normalized Database Schemas

### Tools

- Git
- GitHub
- Postman
- IntelliJ IDEA / VS Code
- Maven

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      React.js       │
                    │      Frontend       │
                    └──────────┬──────────┘
                               │
                               │ HTTP / REST API
                               ▼
                    ┌─────────────────────┐
                    │    Spring Boot      │
                    │     Backend         │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
       ┌────────────┐   ┌────────────┐   ┌────────────┐
       │ Controller │   │  Service   │   │ Repository │
       └────────────┘   └────────────┘   └──────┬─────┘
                                                │
                                                ▼
                                      ┌─────────────────┐
                                      │    Hibernate    │
                                      └────────┬────────┘
                                               │
                                               ▼
                                      ┌─────────────────┐
                                      │   PostgreSQL    │
                                      │    Database     │
📂 Project Structure
E-Commerce-Full-Stack/
│
├── frontend/
│   │
│   ├── public/
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   ├── ProductCard.jsx
│   │   │   └── CartItem.jsx
│   │   │
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── Products.jsx
│   │   │   ├── Cart.jsx
│   │   │   └── Checkout.jsx
│   │   │
│   │   ├── services/
│   │   │   └── api.js
│   │   │
│   │   ├── App.jsx
│   │   └── index.js
│   │
│   └── package.json
│
├── backend/
│   │
│   ├── src/
│   │   └── main/
│   │       │
│   │       ├── java/
│   │       │   └── com/
│   │       │       └── ecommerce/
│   │       │           │
│   │       │           ├── controller/
│   │       │           │   ├── ProductController.java
│   │       │           │   ├── CartController.java
│   │       │           │   └── CheckoutController.java
│   │       │           │
│   │       │           ├── service/
│   │       │           │   ├── ProductService.java
│   │       │           │   ├── CartService.java
│   │       │           │   └── CheckoutService.java
│   │       │           │
│   │       │           ├── repository/
│   │       │           │   ├── ProductRepository.java
│   │       │           │   └── CartRepository.java
│   │       │           │
│   │       │           ├── model/
│   │       │           │   ├── Product.java
│   │       │           │   ├── Cart.java
│   │       │           │   └── Order.java
│   │       │           │
│   │       │           ├── exception/
│   │       │           │   └── GlobalExceptionHandler.java
│   │       │           │
│   │       │           └── EcommerceApplication.java
│   │       │
│   │       └── resources/
│   │           └── application.properties
│   │
│   └── pom.xml
│
└── README.md

⚙️ Prerequisites
Before running the project, make sure you have installed:
Java 17+
Node.js
npm
PostgreSQL
Maven
Git

You can verify the installations using:
java -version
node -v
npm -v
mvn -version
psql --version
git --version

🚀 Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/e-commerce-full-stack.git

Navigate to the project:
cd e-commerce-full-stack



☕ Backend Setup
Navigate to the backend directory:
cd backend

Install dependencies and build the project:
mvn clean install

Run the Spring Boot application:
mvn spring-boot:run

The backend server will start at:
http://localhost:8080

⚛️ Frontend Setup
Open a new terminal and navigate to the frontend:
cd frontend

Install dependencies:
npm install

Start the React application:
npm start

The frontend will run at:
http://localhost:3000

# 👨‍💻 Author

## Mrigank Pandey

**Computer Science & Engineering**

📧 Email: [mrigankpandey2284@gmail.com](mailto:mrigankpandey2284@gmail.com)
