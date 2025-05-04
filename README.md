# DevOps API Testing Pipeline with Jenkins and Postman

This project demonstrates a simple and cost-free DevOps pipeline using **Jenkins**, **Postman**, and **Docker Compose** to automate API testing. It is ideal for DevOps portfolios and job applications. The entire stack runs locally—no paid cloud services required.

## 🚀 Features

- Automates API tests using Postman Collection Runner via Jenkins
- Uses Newman CLI to run Postman tests in Jenkins pipelines
- Runs everything in isolated Docker containers
- No cloud or paid service dependencies

## 🛠️ Tech Stack

- Docker
- Docker Compose
- Jenkins
- Postman
- Newman CLI
- Git

## 📁 Project Structure

```text
devops-api-testing-pipeline/
├── docker-compose.yml
├── Jenkinsfile
└── postman/
    ├── sample-collection.json
    └── sample-environment.json
