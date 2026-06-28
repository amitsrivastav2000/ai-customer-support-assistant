# AI-Powered Customer Support Assistant

![Java](https://img.shields.io/badge/Java-21-blue)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-brightgreen)
![React](https://img.shields.io/badge/React-19-61DAFB)
![Kafka](https://img.shields.io/badge/Apache_Kafka-Event_Driven-black)
![Redis](https://img.shields.io/badge/Redis-Cache-red)
![Spring AI](https://img.shields.io/badge/Spring_AI-LLM-orange)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-orange)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered customer support platform built using **Spring Boot**, **Spring AI**, **React**, **Apache Kafka**, **Redis**, **Prometheus**, and **Grafana**.

The application demonstrates how modern backend systems can leverage event-driven architecture, AI-assisted automation, caching, and observability to process customer support tickets efficiently.

---

## ✨ Features

### Backend

* Spring Boot 3
* REST APIs
* Event-driven architecture with Apache Kafka
* AI-powered ticket categorization
* AI-generated response suggestions
* Redis caching
* Spring Boot Actuator
* Global exception handling
* Input validation

### Frontend

* React + Vite
* Axios
* Ticket submission form
* Ticket dashboard
* AI response viewer

### Observability

* Prometheus metrics
* Grafana dashboards
* JVM metrics
* API metrics
* Kafka metrics
* Redis metrics

### Infrastructure

* Docker
* Docker Compose
* Kafka
* Redis
* Prometheus
* Grafana

---

## 🏗️ High-Level Architecture

```text
                    React UI
                       │
                       ▼
              Spring Boot REST API
                       │
         ┌─────────────┼─────────────┐
         │             │             │
         ▼             ▼             ▼
      Kafka         Spring AI      Redis
         │             │             │
         └─────────────┼─────────────┘
                       ▼
                 Prometheus
                       │
                       ▼
                   Grafana
```

---

## 🛠️ Technology Stack

| Layer            | Technology           |
| ---------------- | -------------------- |
| Language         | Java 21              |
| Backend          | Spring Boot 3        |
| Frontend         | React + Vite         |
| AI               | Spring AI            |
| Messaging        | Apache Kafka         |
| Cache            | Redis                |
| Monitoring       | Prometheus + Grafana |
| Build Tool       | Gradle               |
| Containerization | Docker               |

---

## 📁 Project Structure

```text
ai-customer-support-assistant/
│
├── backend/
├── frontend/
├── docker/
├── docs/
├── screenshots/
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

## 🚀 Development Roadmap

* [ ] Project setup
* [ ] Docker environment
* [ ] Kafka integration
* [ ] Redis integration
* [ ] Spring AI integration
* [ ] Ticket APIs
* [ ] React dashboard
* [ ] Prometheus metrics
* [ ] Grafana dashboards
* [ ] Production enhancements

---

## 🎯 Learning Goals

This project focuses on practical implementation of:

* Event-driven architecture
* AI integration in enterprise applications
* Redis caching strategies
* Asynchronous processing
* Frontend-backend integration
* Monitoring and observability
* Production-ready project structure

---

## 🔮 Future Enhancements

* JWT Authentication
* PostgreSQL persistence
* Retrieval-Augmented Generation (RAG)
* Kubernetes deployment
* CI/CD pipeline
* OpenAPI/Swagger documentation
* Unit & Integration testing

---

## 📌 Status

🚧 **Work in Progress**

This repository is being developed incrementally with a strong focus on clean architecture, production-ready practices, and interview-oriented learning.
