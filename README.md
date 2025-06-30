# 🧨 Chaotic Project

## ⚠️ Purpose

This repository was intentionally created with vulnerabilities and bad practices to serve as a controlled environment for learning about **container security**.

It is designed for hands-on practice with tools such as:

- [Docker Scout](https://www.docker.com/products/docker-scout/)
- [Trivy](https://aquasecurity.github.io/trivy/)
- And other image and container scanning tools

> **WARNING:** Do not deploy this project in production environments. It is intentionally insecure.

---

## 📂 Project Structure

This is a basic Node.js web application that includes:

- Outdated and vulnerable dependencies
- Insecure Dockerfile configuration
- Weak or unsafe coding patterns

---

## 🚀 Getting Started

> Requirements: Docker installed

```bash
cd src
docker build -t chaotic-project .
docker run -p 3000:3000 chaotic-project
Access the app at: http://localhost:3000
```

🔍 What to Look For
Use this project to identify and analyze:

Vulnerabilities in Node.js dependencies (package.json)

Security issues in the Dockerfile

Insecure network and runtime configurations

Potential code vulnerabilities (XSS, RCE, etc.)

Example usage:

```bash
trivy image chaotic-project
docker scout quickview chaotic-project
```

🎯 Educational Intent
This project is aimed at:

Security learners and enthusiasts

DevSecOps professionals

Instructors and students in application security courses

