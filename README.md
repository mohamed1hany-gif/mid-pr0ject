# 🛠️ Mid-Project: 3-Tier Application with Full DevOps Pipeline

A comprehensive DevOps project for building and deploying a microservices-based 3-tier application. This project demonstrates modern software development practices, including containerization, CI/CD automation, and infrastructure as code (IaC).

---

## 📌 Project Overview

This project showcases the development and deployment of a microservices application, consisting of separate backend and frontend services, supported by a PostgreSQL database. It leverages a complete DevOps pipeline to enable continuous integration, automated testing, and seamless deployment.

---

## ⚙️ Technologies & Tools

### 🖥️ Infrastructure & Automation
- **Ubuntu Linux 24.04 LTS**
- **Git & GitLab**
- **Ansible 2.15**
- **Docker 24.0 & Docker Compose**

### 🧑‍💻 Development
- **Python 3.10** (Flask for REST API)
- **React 18** (Frontend)
- **PostgreSQL 15** (Database)
- **Swagger** (API Documentation)

### 🧪 Testing & Code Quality
- **Pytest** (Backend testing)
- **Jest + React Testing Library** (Frontend testing)
- **SonarQube** (Static code analysis)

---

## 🏗️ Application Architecture

### 🔙 Backend
- Flask REST API using Python 3.10
- API documentation with Swagger
- Unit tested using Pytest

### 🖼️ Frontend
- Built with React 18
- Unit tested using Jest and RTL

### 💾 Database
- PostgreSQL 15
- Used for persistent data storage

---

## 🚀 Infrastructure & Automation

### 🖥️ Server Setup
- Two Ubuntu VMs:
  - **Development/Staging server**
  - **Production server**

### ⚡ Ansible Playbooks
- Configure base servers
- Install Docker & Docker Compose
- Setup PostgreSQL
- Automate application deployment

### 🐳 Docker Configuration
- Multi-stage Dockerfiles for optimized image builds
- Separate containers for backend, frontend, and database
- Docker Compose for local orchestration

---

## 🔁 CI/CD Pipeline (GitLab)

### 📦 Build
- Linting and code quality checks (Python, JS)
- Build Docker images for each service

### 🔍 Security Scanning
- Trivy integration to detect vulnerabilities in Docker images

### ✅ Test
- Run unit tests for both frontend and backend

### 📣 Notify
- Slack integration for pipeline status updates

### 🚢 Deploy
- Deploy to **Staging**
- Run smoke tests
- Deploy to **Production** on approval

---

## 📂 Project Deliverables

1. **📘 Documentation**: Clear and comprehensive markdown files for usage and deployment
2. **🧾 Infrastructure Code**: Ansible playbooks, Dockerfiles, and Compose files
3. **🛠️ CI/CD Pipelines**: GitLab pipeline config with Slack integration
4. **🧱 Architecture**: Visual diagrams and infrastructure descriptions

