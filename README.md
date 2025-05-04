# DevOps API Testing Pipeline with Jenkins and Postman

This project demonstrates a simple and cost-free DevOps pipeline using **Jenkins**, **Postman**, and **Docker Compose** to automate API testing. It is ideal for DevOps portfolios and job applications. The entire stack runs locally—no paid cloud services required.

## 🚀 Features

- Automates API tests using Postman Collection Runner via Jenkins
- Uses Newman CLI to run Postman tests in Jenkins pipelines
- Runs everything in isolated Docker containers
- No cloud or paid service dependencies

## 🛠️ Tech Stack

- 🐳 [Docker](https://www.docker.com/) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat)
- 🧰 [Docker Compose](https://docs.docker.com/compose/) ![Docker Compose](https://img.shields.io/badge/-Docker%20Compose-34495e?logo=docker&logoColor=white&style=flat)
- ☕ [Jenkins](https://www.jenkins.io/) ![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?logo=jenkins&logoColor=white&style=flat)
- 📬 [Postman](https://www.postman.com/) ![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white&style=flat)
- 📦 [Newman CLI](https://www.npmjs.com/package/newman) ![Newman](https://img.shields.io/badge/-Newman-333333?logo=npm&logoColor=white&style=flat)
- 🧑‍💻 [Git](https://git-scm.com/) ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat)

## 📁 Project Structure

```text
devops-api-testing-pipeline/
├── docker-compose.yml
├── Jenkinsfile
└── postman/
    ├── sample-collection.json
    └── sample-environment.json
