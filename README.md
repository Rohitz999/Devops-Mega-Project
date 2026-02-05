# 🚀 DevOps Mega Project  
## Full Production CI/CD Pipeline using Jenkins

This repository contains a **production-grade DevOps CI/CD pipeline** built using **Jenkins**.  
It automates the complete application lifecycle — from **source code commit** to **Docker image creation and deployment readiness** using industry best practices.

This project is structured to reflect **real-world enterprise DevOps workflows**.

---

## 📌 Project Overview

The objective of this project is to design and implement a **robust, scalable, and automated CI/CD pipeline** using **Jenkins Pipeline as Code**.

Every code change pushed to GitHub triggers an automated workflow that:
- Builds the application
- Runs automated tests
- Performs code quality checks
- Creates and pushes Docker images
- Prepares the application for production deployment

---

## 🛠️ Tools & Technologies
-
- **Jenkins** – CI/CD automation  
- **Git & GitHub** – Source code management  
- **Maven** – Build and dependency management  
- **Maven Wrapper (mvnw)** – Consistent builds across environments  
- **Docker** – Application containerization  
- **SonarQube** – Code quality & security analysis  
- **Java** – Application language  
- **Spring Boot** – Application framework  
- **Linux** – Execution environment  

---

## 📂 Repository Structure

```text
.
├── Dockerfile        # Docker image build instructions
├── Jenkinsfile       # Jenkins declarative pipeline (Pipeline as Code)
├── LICENSE           # Project license
├── mvnw              # Maven wrapper (Linux/macOS)
├── mvnw.cmd          # Maven wrapper (Windows)
├── pom.xml           # Maven project configuration
├── README.md         # Project documentation
├── src/              # Application source code
└── target/           # Compiled artifacts
