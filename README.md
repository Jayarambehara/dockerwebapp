# DevSecOps CI/CD Pipeline with Docker

## Overview
This project demonstrates a CI/CD DevSecOps pipeline where code is built, analyzed, containerized, scanned, and deployed using Docker and DevSecOps tools.

## Tools Used
- GitHub
- Maven
- SonarQube
- Nexus Repository
- Docker
- Trivy
- CI/CD Pipeline tool (Jenkins etc.)
- Docker Stack

## CI/CD Pipeline Flow

1. Developer pushes code + Dockerfile to GitHub
2. Code quality analysis done using SonarQube
3. Maven used to build the project
4. Artifact stored in Nexus Repository
5. Docker image built using Dockerfile
6. Image scanned using Trivy for security issues
7. Image pushed to Docker registry
8. Application deployed using Docker stack (production)
9. Email notification sent after pipeline completion

## Pipeline Flow

GitHub → SonarQube → Maven → Nexus → Docker Build → Trivy Scan → Registry → Deploy → Email

## Outcome
This pipeline ensures secure, automated and production-ready deployment.

<img width="953" height="394" alt="sonatype" src="https://github.com/user-attachments/assets/7f644474-55ae-404b-9c0e-7a7769a2a02a" />
<img width="927" height="470" alt="Docker-deployment" src="https://github.com/user-attachments/assets/3839bf41-f3bc-420b-b2b9-02270da9392b" />
<img width="955" height="472" alt="Deploy-output" src="https://github.com/user-attachments/assets/c2c3b9ae-e076-4151-9055-772a98e76a1a" />
<img width="914" height="462" alt="deploy-success" src="https://github.com/user-attachments/assets/6fc3fef0-db30-4a0a-bcbf-6c349849c09a" />





