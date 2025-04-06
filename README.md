# 📚 Online Bookstore using Spring Boot

A microservices-based Online Bookstore System built with **Spring Boot**, **Spring Cloud**, **Spring Security**, **Netflix Eureka**, and **MySQL**. This project demonstrates a distributed system with service discovery, API Gateway, and inter-service communication, featuring book management, order processing, and inventory tracking.

## 🚀 Features
- **Microservices Architecture**: Separate services for books, orders, and inventory.
- **Service Discovery**: Netflix Eureka for dynamic service registration and discovery.
- **API Gateway**: Centralized routing with Spring Cloud Gateway.
- **Database**: MySQL for persistent storage with JPA/Hibernate.
- **API Documentation**: Swagger UI for API exploration.
- **Testing**: Comprehensive API tests with Postman.

## 🏗️ Architecture
The system consists of the following microservices:
- **Eureka Server**: Service registry for discovery.
- **API Gateway**: Entry point for all client requests.
- **Book Service**: Manages book CRUD operations.
- **Order Service**: Handles order creation and management.
- **Inventory Service**: Tracks book stock levels.

## 🛠️ Setup Instructions
### Prerequisites
- Java 17
- Maven
- MySQL
- Postman (for API testing)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/lakshay1341/online-bookstore.git
   cd online-bookstore
   
2. **Set Up the Database**:
  - Create a MySQL database named `bookstoredb`.

3. **Access the Application**:
   - Eureka Dashboard: [http://localhost:8761](http://localhost:8761)
   - API Gateway: [http://localhost:8080](http://localhost:8080)
   - Swagger UI for each service:
     - Book Service: [http://localhost:8081/swagger-ui.html](http://localhost:8081/swagger-ui.html)
     - Order Service: [http://localhost:8082/swagger-ui.html](http://localhost:8082/swagger-ui.html)
     - Inventory Service: [http://localhost:8083/swagger-ui.html](http://localhost:8083/swagger-ui.html)

## 📖 API Documentation
### Swagger UI
Explore the API endpoints using Swagger UI:
- [Book Service Swagger](http://localhost:8081/swagger-ui.html)
- [Order Service Swagger](http://localhost:8082/swagger-ui.html)
- [Inventory Service Swagger](http://localhost:8083/swagger-ui.html)


## 📸 Screenshots
### Eureka Dashboard
![image](https://github.com/user-attachments/assets/ea0bca55-401c-40d6-bea0-bcfa140f80d2)


### Postman Tests
![Postman Test - GET /books](https://github.com/lakshay1341/online-bookstore/blob/main/docs/postman_get_books.png)

## 🧪 Running API
Login:
   - `baseUrl`: `http://localhost:8080`
   - `username`: `admin`
   - `password`: `password`
  
