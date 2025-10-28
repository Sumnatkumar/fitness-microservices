🏋️ Fitness-App
🌐URL = https://radiant-wisp-c6e6f1.netlify.app/
![App UI](https://github.com/Sumnatkumar/fitness-microservices/blob/main/FitnessAppLogin.png)

# 🚀 Microservices-Based Application with Kafka Integration

A **scalable, event-driven microservices architecture** built using modern Java technologies.
This application demonstrates enterprise-grade patterns like asynchronous communication via **Apache Kafka**, service decoupling, persistence using **Spring Data JPA**, and relational storage in **MySQL** in **MongoDB**.

> 🧠 Built to showcase hands-on expertise in Java Full Stack development.


---

## 🧰 Tech Stack

| 🧩 Layer        | ⚙️ Technologies Used                                                                 |
|----------------|----------------------------------------------------------------------------------------|
| **Backend**     | Java 17 · Spring Boot 3 · Spring Web · Spring Validation · Spring JPA (Hibernate),keycloak     |
| **Database**    | MySQL , MongoDB· JPA/Hibernate                                                                 |
| **Messaging**   | Apache Kafka · Spring for Apache Kafka                                                |
| **Build Tool**  | Maven                                                                                 |
| **Dev Tools**   | Lombok · Spring DevTools · Postman · Kafka CLI                                        |
| **Security**    | 🔒 _Planned:_ Spring Security · JWT                                                   |
| **UI (Planned)**| 💻 React.js · Material UI · Axios                                                       |
| **Cloud & Infra**| ☁️ _Planned:_ Docker · AWS (EC2, S3) · GitHub Actions CI/CD                          |

---


## 🧱 Architecture Highlights

- 🧬 **Microservices Pattern** — Modular, loosely coupled services for scalability.
- 📩 **Apache Kafka** — Asynchronous communication via producer-consumer architecture.
- 🔧 **Spring Boot** — Auto-configured, production-ready Java microservices.
- 💾 **Spring Data JPA + MySQL** — Clean ORM-based persistence layer.
- 📦 **DTO + Events** — Clean separation between domain models and transport objects.
- 🔮 **Future Enhancements**:
  - 🐳 Docker-based deployments
  - 🔍 Service discovery with **Eureka**
  - 🌐 API Gateway via **Spring Cloud Gateway**
  - 🛡️ Circuit breaker with **Resilience4j**
  - 📊 Monitoring with **Prometheus + Grafana**

---

## 📦 Current Modules

| 🧩 Service Name  | 📄 Description                                                                                                               |
|------------------|-------------------------------------------------------------------------------------------------------------------------------|
| `activityservice`| Handles user fitness activities like workouts and logs. Stores, updates and tracks progress for analytics.                    |
| `aiservice`      | Processes data using AI such as recommendations and personalized fitness insights. Helps users follow smart training plans.   |
| `configserver`   | Central place to store and manage configuration for all microservices. Makes updates easier without redeploying each service. |
| `eureka`         | Service discovery server that lets microservices find and communicate with each other. Keeps the system scalable and flexible.|
| `gateway`        | Single entry point for all client requests. Protects backend services and manages routing, authentication, and load balancing.|
| `userservice`    | Manages user accounts, profiles, and authentication data. Handles registration, login, and user information storage.          |

---
![App UI](https://github.com/Sumnatkumar/fitness-microservices/blob/main/ArchitfitnessAI.png)


---

## 📨 Kafka Topics

| 🧵 Topic Name              | 🔍 Purpose                                                  |
|----------------------------|--------------------------------------------------------------|
| `kafka-topic-name`         | 🔄 Requests for questions based on `AIService`              |
| `Kafka-topic-name`         | 📤 Responds with a list of matching `ActivityService` DTOs  |

---

----
## Gemini AI 
|Gemini AI integration in your Spring Boot + React.js Fitness App 🏋️🤖  description
|----------------------------------------------------------------------------------------------|
| Gemini AI helps our fitness app intelligently analyze user health and workout data.          |
| It provides personalized exercise suggestions using advanced machine learning models.        |
| Our Spring Boot backend interacts with Gemini APIs to generate smart insights.               |
| React.js consumes those AI-powered responses to deliver a smooth and interactive UI.         |
| Gemini AI enhances the user experience through natural language guidance and fitness tips.   |
| The app uses Gemini to detect workout patterns and recommend improvements.                   |
| Gemini AI boosts engagement by enabling chat-based support for fitness queries.              |
| The system ensures secure API integration aligning with modern authentication standards.     |
| AI-driven features help users track progress more effectively and stay motivated.            |
| Gemini makes our fitness platform more advanced, future-ready, and user-friendly. 💪✨      |
-----

## 🛠️ To-Do /  Features

- [ ] 🔐 Implement `user-service` with authentication (JWT + Spring Security)
- [ ] 🌐 Add API Gateway using Spring Cloud Gateway
- [ ] 🐳 Dockerize all services for containerized deployment
- [ ] 📁 MongoDB integration for unstructured logs
- [ ] 💻 UI Frontend with **React + Material UI**
- [ ] 🧪 Add unit and integration tests using **JUnit + TestContainers**
- [ ] ☁️ Deploy to **Netlify** using GitHub Actions

---
