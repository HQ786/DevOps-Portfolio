# Jenkins Integration with Kubernetes for CI/CD Pipeline (Project 8)

## Overview/Description
This project demonstrates the integration of Jenkins with Kubernetes to create a robust CI/CD pipeline for automated deployments. The CI/CD pipeline is designed to deploy applications on Kubernetes clusters, enabling continuous integration and continuous delivery with automatic scaling and high availability.

### Key Components:
- **Jenkins**: Used for automating the build, test, and deployment processes.
- **Kubernetes**: Provides container orchestration and management for the deployed applications.
- **Docker**: Containerizes applications to ensure consistency across environments.
- **Helm**: Kubernetes package manager used for simplifying deployments.
- **GitHub**: Source code repository for version control.
- **Jenkins Kubernetes Plugin**: Used for managing Jenkins agents running within the Kubernetes cluster.

### Steps Involved:
1. **Set Up Jenkins**: Deploy Jenkins on a Kubernetes cluster using Helm.
2. **Configure Jenkins Pipeline**: Create a Jenkins pipeline to automate building and deploying the application.
3. **Integrate Jenkins with Kubernetes**: Set up the Jenkins Kubernetes plugin to use Kubernetes for scaling Jenkins agents dynamically.
4. **Create Dockerfile**: Build a Docker container for the application.
5. **Deploy the Application on Kubernetes**: Use Helm and Kubernetes to deploy the application, ensuring scalability and high availability.

## Tools Required:
- **Jenkins**: For CI/CD automation.
- **Kubernetes**: For container orchestration and management.
- **Docker**: For containerizing the application.
- **Helm**: For managing Kubernetes deployments.
- **GitHub**: For version control and source code repository.

## Code Repository:
- **Repository Platform**: GitHub
- **Repository Link**: [https://github.com/HQ786/devops-portfolio/project-8-jenkins-integration-with-kubernetes](https://github.com/HQ786/devops-portfolio/project-8-jenkins-integration-with-kubernetes)
- **Access Instructions**: Clone the repository and check out the `project-8-jenkins-integration-with-kubernetes` folder for detailed setup and code.

## Folder Structure:
- `Jenkinsfile`: The pipeline script for Jenkins.
- `Dockerfile`: Docker configuration to build the application container.
- `helm/`: Directory for Helm charts to deploy the app on Kubernetes.
- `kubernetes/`: Kubernetes configuration files (deployment, service, etc.).
- `README.md`: Project documentation.

