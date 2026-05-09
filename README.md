# E-Commerce Microservices Backend

Backend-focused eCommerce application built using Java 17 and Spring Boot with a microservices architecture.

## Features

- User authentication with JWT
- Product catalog management
- Order processing workflow
- API Gateway routing
- Dockerized services
- Redis caching
- REST API communication between services

## Microservices

- User Service
- Product Service
- Order Service
- Payment Service
- Inventory Service
- API Gateway

## Tech Stack

- Java 17
- Spring Boot
- Spring Security
- Spring Cloud Gateway
- MySQL
- Redis
- Docker
- Maven

## Project Goals

This project was built to explore:

- Microservices architecture
- Secure REST API development
- JWT authentication
- Service-to-service communication
- Docker containerization
- Database optimization

## Running the Project

### Clone Repository

```bash
git clone <your-repo-url>
```

### Build Project

```bash
mvn clean install
```

### Start Services

```bash
docker-compose up
```

## API Testing

Postman collections were used to test:
- Authentication APIs
- Product APIs
- Order workflows
- Payment operations

## Future Improvements

- Kafka-based event communication
- Centralized logging
- Distributed tracing
- Kubernetes deployment
