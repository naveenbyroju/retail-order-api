# 🛒 Retail Order API

A Spring Boot RESTful API for managing products in a retail inventory system. Built with Java 11, Spring Boot, JPA, and MySQL.

![Java](https://img.shields.io/badge/Java-11-blue?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.15-brightgreen?logo=spring-boot)
![MySQL](https://img.shields.io/badge/Database-MySQL-blue?logo=mysql)
![REST API](https://img.shields.io/badge/API-RESTful-orange)

---

## 🚀 Features

- Add, retrieve, and list products
- MySQL database integration using Spring Data JPA
- Exposes clean REST endpoints
- Easy to extend for customers, orders, or authentication

---

## 🛠 Tech Stack

- Java 11
- Spring Boot 2.7.15
- Spring Data JPA
- MySQL
- Maven

---

## 📂 Project Structure

src
├── main
│ ├── java/com/naveen/retail
│ │ ├── controller
│ │ ├── service
│ │ ├── repository
│ │ ├── model
│ │ └── RetailOrderApiApplication.java
│ └── resources
│ └── application.properties


---

## ⚙️ Getting Started

### 📦 1. Clone the Repo
```bash
git clone https://github.com/naveenbyroju/retail-order-api.git
cd retail-order-api

🛠 2. Setup MySQL
sql
Copy
Edit
CREATE DATABASE retail;
🧾 3. Configure application.properties
Edit src/main/resources/application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/retail
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
▶️ 4. Run the App
bash
Copy
Edit
./mvnw spring-boot:run
or run RetailOrderApiApplication.java from IntelliJ

🔄 API Endpoints
Method	Endpoint	Description
GET	/api/products	Get all products
POST	/api/products	Add a new product

💡 Future Enhancements
Add Customer & Order entities

Integrate authentication (Spring Security)

Add Docker support and CI/CD

👤 Author
Naveen Byroju
🖥 LinkedIn
📦 GitHub




