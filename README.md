# 🏥 MediSync

### Enterprise Healthcare Management Platform

**Production-Deployed | Microservices Architecture | Hospital Environment**

Designed, architected, and deployed as a production-grade microservices system in a live hospital environment.

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Architecture](https://img.shields.io/badge/architecture-microservices-orange)
![Spring Boot](https://img.shields.io/badge/backend-Spring%20Boot-success)
![React](https://img.shields.io/badge/frontend-React-61DAFB)
![License](https://img.shields.io/badge/license-Private-red)
![Status](https://img.shields.io/badge/status-Production--Deployed-success)

---

# 📌 Executive Overview

**MediSync** is an enterprise-grade **B2B healthcare management platform** originally developed as a graduation project and later refactored into a **production-deployed system** serving **Holy Family Hospital**.

The platform is built using a **distributed microservices architecture**, designed to:

* Streamline hospital administrative workflows
* Manage and secure patient data
* Automate appointment scheduling
* Enforce role-based security policies
* Support long-term institutional scalability

This system operates in a real hospital environment and was engineered with production-readiness, modularity, and extensibility in mind.

---

# 🚀 Production Deployment

* Successfully deployed in a live hospital environment
* Used by administrative and medical staff
* Secure role-based access implemented across services
* Designed for service isolation and horizontal scalability
* Architecture prepared for future domain expansion

---

# 🧩 System Architecture

MediSync follows a **microservices-based distributed architecture**, where each domain is isolated into independently deployable services.

## Architecture Diagram

![image alt](https://github.com/ObjectOrienters/MediSync/blob/main/assets/p1.png)

## Architectural Highlights

* Domain-driven service separation
* Independent service deployment
* Database per service (loose coupling)
* Stateless JWT authentication
* Role-Based Access Control (RBAC)
* Scalable and modular infrastructure

---

# 🔁 Appointment Scheduling Flow

This diagram illustrates the production flow when hospital staff create or update an appointment.

![image alt](https://github.com/ObjectOrienters/MediSync/blob/main/assets/p2.png)

---

# 🏗 Microservices

## API Gateway

* Centralized request routing
* Security filtering
* Entry point for all client communication

## Security Service

* Authentication & Authorization
* JWT generation and validation
* Role-based access enforcement
* Request filtering

## MediSync Core Service

* Business logic orchestration
* Patient data management
* Medical record handling
* Domain rule enforcement

## Appointments Service

* Appointment lifecycle management
* Scheduling coordination
* Doctor availability handling
* Integration with Notifications Service

## Notifications Service

* Appointment reminders
* Status updates
* System alerts
* Email/SMS integration (planned extension)

---

# ✨ Core Capabilities

* Centralized patient records management
* Secure hospital-grade access control
* Appointment lifecycle automation
* Modular microservices infrastructure
* Production deployment in healthcare domain
* Designed for long-term scalability

---

# 🧠 Architectural Decisions

* Microservices chosen for scalability and service isolation
* Database-per-service to reduce tight coupling
* Stateless authentication using JWT for horizontal scaling
* Clear domain boundaries between security, scheduling, and business logic
* Designed for future event-driven evolution

---

# 🚀 Strategic Roadmap

## Planned Services

### Patients Service

* Self-service patient portal
* Online appointment booking
* Medical history access
* Profile management

### Employees Service

* Staff management
* Department and role assignment
* Workforce scheduling
* Internal workflow optimization

These services will extend the system into a full healthcare digital ecosystem.

---

# 🛠 Technology Stack

## Backend

* Spring Boot
* Spring Security
* JWT Authentication
* RESTful APIs
* MySQL
* Maven
* Docker

## Frontend

* ReactJS
* TypeScript
* React Query
* Material UI
* Material React Table
* React Hook Form
* Zustand

## Infrastructure

* Production-ready architecture
* Containerization-ready services
* Designed for on-premise or cloud scalability

---

# 🔐 Security & Compliance

* Role-Based Access Control (RBAC)
* Stateless JWT Authentication
* Service-level authorization
* Isolated data per service
* Secure healthcare data handling

---

# 📊 Project Evolution

| Phase            | Description                                    |
| ---------------- | ---------------------------------------------- |
| Academic Phase   | Developed as Graduation Project                |
| Production Phase | Refactored & deployed for Holy Family Hospital |
| Expansion Phase  | Scaling architecture and adding new services   |

---

# 👥 Team

Designed and Developed by:

* **Angela Salem**
* **Husam Ramoni**
* **Yousef Albandak**

Graduation Project — Bethlehem University
Now operating as a production healthcare system.

---

# 📬 Contact

For business or collaboration inquiries:

📧 [angel.salem.008@gmail.com](mailto:angel.salem.008@gmail.com)
📧 [husamramoni@gmail.com](mailto:husamramoni@gmail.com)
📧 [yousef.bandak@gmail.com](mailto:yousef.bandak@gmail.com)

---

# 📌 Repository Notice

This is a **private enterprise repository**.
Source code and deployment configurations are restricted.

---
