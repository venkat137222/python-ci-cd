# 🚀 API Testing CI/CD Pipeline using Jenkins, Docker, and Postman

This project demonstrates a simple and powerful CI/CD pipeline that automatically runs **API tests** using **Postman and Newman**, integrated into a Jenkins pipeline running inside a **Docker container**.

## 🧰 Tech Stack

- **Jenkins** – Automation server for CI/CD
- **Docker** – Containerization of Jenkins and API test runner
- **Postman** – API testing
- **Newman** – CLI runner for Postman collections
- **Git** – Version control

## 🎯 Features

- Automated API testing pipeline triggered via Jenkins
- Jenkins containerized using Docker
- Postman collection and environment run through Newman
- Easy to deploy and extend for real-world APIs
- 100% FREE to run locally (no cloud costs)

## 🗂️ Project Structure

├── docker-compose.yml
├── Jenkinsfile
├── postman/
│ ├── sample-collection.json
│ └── sample-environment.json
└── README.md
