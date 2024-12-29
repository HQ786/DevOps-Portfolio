# DevSecOps Jenkins CI/CD Pipeline for Node.js Application

## Project Overview
This project involves setting up a **Jenkins CI/CD pipeline** for a **Node.js application** with a focus on **DevSecOps** practices. The pipeline includes the following features:
- **Code quality analysis** using **SonarQube**.
- **Security testing** using **OWASP tools**.
- **Docker image vulnerability scanning** with **Trivy**.
- **Automated deployment** with Jenkins.

### Key Components:
- **Jenkins**: Used for setting up and managing the CI/CD pipeline.
- **Docker & Docker Compose**: For containerizing the Node.js application and orchestration.
- **SonarQube**: For automated code quality checks.
- **OWASP tools**: For security vulnerability scanning.
- **Trivy**: For scanning Docker images for vulnerabilities.
- **DevSecOps practices**: Integrated into every phase of the software development lifecycle.

## Project Structure

- `Dockerfile`: Defines the Docker image for the Node.js application.
- `docker-compose.yaml`: Defines the services for running the application and its dependencies.
- `Jenkinsfile`: Defines the Jenkins pipeline for the project.
- `sonar-project.properties`: Configuration file for SonarQube analysis.
- `app.js`: Main application file for the Node.js app.
- `package.json`: NPM configuration file.
- `package-lock.json`: Dependency lock file for the Node.js application.
- `test.js`: Example test script for the Node.js application.
- `views/`: Contains the application views (e.g., HTML or templates).
- `terraform/`: Contains Terraform configurations for infrastructure as code.
- `k8s/`: Contains Kubernetes configurations for deployment.

## Prerequisites

Before you begin, ensure you have the following tools installed on your machine:

- **Docker** and **Docker Compose**: For containerization.
- **Jenkins**: For CI/CD pipeline automation.
- **SonarQube**: For code quality analysis.
- **OWASP tools**: For security testing.
- **Trivy**: For Docker image vulnerability scanning.

## Setup Instructions

 Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/HQ786/devops-portfolio.git
cd devops-portfolio/project-3-devsecops-pipeline

