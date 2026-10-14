# maiqora-portfolio

# MAIQORA — Java Backend & WeChat Mini Program

**Independent Software Engineering Project | 2026**

[![Watch Demo](https://img.shields.io/badge/Watch_Project_Demo-YouTube-red?logo=youtube)](https://youtu.be/ZIClSJpDTU4)

## Overview

MAIQORA is an independently developed e-commerce prototype featuring a WeChat mini-program frontend and a Java Spring Boot backend.

The project focuses on reliable order processing, concurrency-safe inventory management, automated testing, and continuous integration.

## Technology Stack

| Category | Technologies |
|---|---|
| Backend | Java 21, Spring Boot, REST APIs, Spring Data JPA |
| Database | MySQL 8, Flyway |
| Frontend | Taro, React, TypeScript |
| Testing | JUnit, Testcontainers, Maven |
| DevOps | Docker, Docker Compose, GitHub Actions |

## Key Features

- Product catalogue and SKU management
- Shopping cart and order processing
- Transaction-safe inventory management
- Order cancellation and stock restoration
- Inventory audit logging
- Simulated payment workflow
- Automated backend testing

## Engineering Highlights

### 1. Concurrency-Safe Inventory

The backend uses MySQL transactions and conditional stock updates to prevent overselling.

In a controlled concurrency test:

| Metric | Result |
|---|---|
| Concurrent buyers | 12 |
| Available inventory | 10 units |
| Successful orders | 10 |
| Rejected orders | 2 |
| Oversold units | 0 |

A consistent SKU processing order also reduces lock-order conflicts during multi-item transactions.

### 2. Automated Testing

The project includes **125 automated tests** covering backend functionality and database interactions.

Testcontainers provides integration testing against a real MySQL environment.

### 3. Database Management

Flyway migrations (V1–V4) provide version-controlled database schema changes.

### 4. Continuous Integration

GitHub Actions runs:

- Maven build and test verification
- Automated backend checks
- Docker image build verification

Docker Compose provides an isolated local demonstration environment.

## Project Demonstration

**[Watch the English MAIQORA Project Demo on YouTube](https://youtu.be/ZIClSJpDTU4)**

The video demonstrates the shopping workflow, backend implementation, automated tests, and CI pipeline.

## Project Scope

MAIQORA is an independent portfolio project, not a production commercial service.

Payments are simulated, and the results described above come from local development and controlled testing.

The complete backend source code can be made available to technical reviewers upon request.

## Developer

**Mengqiao Mai**

Computer Science & Data Science Undergraduate  
Auckland University of Technology (AUT), New Zealand

[GitHub Profile](https://github.com/mai23232)

