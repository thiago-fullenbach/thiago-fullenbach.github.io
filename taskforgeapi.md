---
layout: post
title: TaskForgeAPI
---

Backend application for task management, built with Kotlin and Spring Boot.
Designed with real-world API concerns such as security, concurrency control, auditing, and scalable data handling in mind.

🔗 **GitHub:** [View Repository](https://github.com/thiago-fullenbach/TaskForgeAPI)

### 🚀 Features
- Full CRUD for tasks and categories
- Status transition control (TODO → DOING → DONE)
- JWT-based authentication and secure endpoints
- Audit logging for task changes
- Filtering and paginated queries
- Soft delete to preserve data integrity
- Optimistic locking for concurrency handling

### 🏗️ Architecture & Tech

- Kotlin 2.2, Spring Boot
- Spring Security (JWT)
- Spring Data JPA
- PostgreSQL / H2
- Flyway (database migrations)
- TestContainers, JUnit 5
- Docker/Docker Compose for Infrastructure

### ⚙️ Highlights
- State machine implementation for task status transitions
- Optimistic locking to prevent concurrent update conflicts
- Audit trail design for tracking entity changes
- Clean layered architecture (Controller, Service, Repository, DTO)
- Environment-based configuration with secure variables