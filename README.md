# Retail Order API

A simple Spring Boot RESTful API for managing product inventory and orders.

## 🚀 Features

- Add, view, and list products
- REST endpoints using Spring Boot
- MySQL integration with Spring Data JPA

## 🛠 Tech Stack

- Java 11
- Spring Boot 2.7.15
- Spring Data JPA
- MySQL
- Maven

## 📦 Running Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/naveenbyroju/retail-order-api.git
   cd retail-order-api
   ```

2. Update `application.properties` with your MySQL credentials.

3. Run the app from your IDE or terminal:
   ```bash
   mvn spring-boot:run
   ```

## 📮 API Endpoints

| Method | Endpoint         | Description     |
|--------|------------------|-----------------|
| GET    | /api/products    | List products   |
| POST   | /api/products    | Add product     |
