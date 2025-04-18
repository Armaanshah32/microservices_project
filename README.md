# 🏦 Bankify Microservices System  

### A Banking System built with **Spring Boot, PostgreSQL, Eureka, and API Gateway**  

---

## **Overview**  
Bankify is a **microservices-based banking system** that manages **users, accounts, and transactions**.  
It is built using **Spring Boot**, **Spring Cloud**, and **PostgreSQL**, ensuring a **scalable** and **resilient** system.

---

## **Architecture**  

###  **Microservices Used**:
**User Service** – Manages user registration and authentication.  
**Account Service** – Handles bank accounts.  
**Transaction Service** – Manages deposits, withdrawals, and transfers.  
**Eureka Server** – Service registry for microservices.  
**API Gateway** – Single entry point for client requests.

All services are containerized using Docker and deployed on a Kubernetes cluster, enabling load balancing, scaling, and fault tolerance.

---

## **📌 Technologies Used**  

- **Java 23**  
- **Spring Boot 3.4.3**  
- **Spring Cloud Netflix Eureka**  
- **Spring Boot Security**  
- **Spring Data JPA (Hibernate)**  
- **PostgreSQL**  
- **API Gateway**  
- **RestTemplate (Inter-service communication)**
- **Docker**
- **Kubernetes**

Note - Snapshot files were removed because of size constraint. Yaml and docker compose files should be at the root of the project.

![image](https://github.com/user-attachments/assets/bf8b957c-e71f-4912-b546-fd8469361bf2)

< Verification of kubernetes working with port forwarding >
