Overview
This project implements a microservices-based online bookstore using Spring Boot, Spring Cloud, Spring Security, Netflix Eureka, and MySQL. It follows a distributed architecture, incorporating service discovery, an API Gateway, and seamless inter-service communication for managing books, processing orders, and tracking inventory.
Key Features
Microservices Architecture: Independent services for books, orders, and inventory.

Service Discovery: Dynamic registration and lookup with Netflix Eureka.

API Gateway: Centralized request routing via Spring Cloud Gateway.

Database: MySQL for persistent data storage using JPA/Hibernate.

API Documentation: Interactive API exploration using Swagger UI.

Testing: Thorough API testing with Postman.

Architecture Overview
The system consists of multiple microservices:

Eureka Server: Manages service registration and discovery.

API Gateway: Acts as the single entry point for client requests.

Book Service: Handles book-related CRUD operations.

Order Service: Manages order processing and tracking.

Inventory Service: Maintains stock levels for books.
🛠️ Setup Instructions
Prerequisites
Ensure the following dependencies are installed:

Java 17

Maven

MySQL

Postman (for API testing)
Setup Steps
1️⃣ Clone the Repository:

sh
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd online-bookstore
2️⃣ Set Up the Database:

Create a MySQL database named bookstoredb.

3️⃣ Run & Access the Application:

Eureka Dashboard: http://localhost:8761

API Gateway: http://localhost:8080

4️⃣ Swagger UI for API Documentation:

Book Service: http://localhost:8081/swagger-ui.html

Order Service: http://localhost:8082/swagger-ui.html

Inventory Service: http://localhost:8083/swagger-ui.html

📖 API Documentation
Explore endpoints via Swagger UI:

Book Service API 📘

Order Service API 📦

Inventory Service API 🏷️

📸 Screenshots
Eureka Dashboard
![image](https://github.com/user-attachments/assets/ea5523d1-fb3d-40a0-9c9c-eacc15377b7c)


Postman API Testing

🧪 Running the API
To authenticate:

Base URL: http://localhost:8080

Username: admin

Password: password
