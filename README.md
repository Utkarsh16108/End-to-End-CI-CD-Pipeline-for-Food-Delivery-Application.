# 🚀 **End-to-End-CI-CD-Pipeline-for-Food-Delivery-Application.**

## Project Overview

This project demonstrates the implementation of a complete DevOps CI/CD pipeline for a containerized Food Delivery Application using modern DevOps practices, security scanning, monitoring, Kubernetes orchestration, and GitOps deployment strategies.

The objective of this project is to automate the software delivery lifecycle, improve deployment reliability, enforce security standards, and provide real-time monitoring of application and infrastructure health.

The project covers Continuous Integration, Continuous Deployment, Security Scanning, Containerization, Monitoring, Kubernetes Orchestration, and GitOps-based deployment workflows.

## 🛠️ Tools & Services Used:

1. **GitHub** ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
2. **Jenkins** ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
3. **SonarQube** ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
4. **Docker** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
5. **Kubernetes** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
6. **Prometheus** ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
7. **Grafana** ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
8. **ArgoCD** ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
9. **OWASP** ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
10. **Trivy** ![Trivy](https://img.shields.io/badge/Trivy-00979D?style=flat-square&logo=trivy&logoColor=white)

---

## Architecture

Developer → GitHub → Jenkins → SonarQube → OWASP Dependency Check → Trivy Security Scan → Docker Build → DockerHub → Kubernetes (EKS) → ArgoCD → Application Deployment

Monitoring Stack:

Prometheus → Node Exporter → Grafana Dashboards

---

## Key Features

- Automated CI/CD Pipeline using Jenkins
- Static Code Analysis using SonarQube
- Dependency Vulnerability Scanning using OWASP Dependency Check
- Container Security Scanning using Trivy
- Docker Containerization
- DockerHub Image Management
- Kubernetes Deployment using Amazon EKS
- GitOps Deployment using ArgoCD
- Infrastructure Monitoring using Prometheus
- Dashboard Visualization using Grafana
- Automated Email Notifications
- Security-First DevOps Workflow

---

## Technologies Used

### DevOps Tools
- Jenkins
- Docker
- Kubernetes
- ArgoCD
- Git
- GitHub

### Security Tools
- SonarQube
- OWASP Dependency Check
- Trivy
- Docker Scout

### Monitoring Tools
- Prometheus
- Grafana
- Node Exporter

### Cloud Platform
- AWS EC2
- AWS EKS
- AWS IAM

### Application Stack
- Node.js
- NPM

---

## CI/CD Pipeline Workflow

### Stage 1 – Source Code Management
Application source code is stored in GitHub and acts as the central repository.

### Stage 2 – Continuous Integration
Jenkins automatically triggers the pipeline whenever changes are pushed to the repository.

### Stage 3 – Code Quality Analysis
SonarQube performs static code analysis and enforces quality standards.

### Stage 4 – Security Validation
OWASP Dependency Check and Trivy perform vulnerability analysis on application dependencies and source files.

### Stage 5 – Docker Image Creation
The application is containerized using Docker.

### Stage 6 – DockerHub Integration
Container images are automatically tagged and pushed to DockerHub.

### Stage 7 – Kubernetes Deployment
The application is deployed to Amazon EKS for container orchestration and scalability.

### Stage 8 – GitOps Delivery
ArgoCD continuously synchronizes Kubernetes deployments from Git repositories.

### Stage 9 – Monitoring & Observability
Prometheus collects infrastructure and application metrics while Grafana provides real-time dashboards.

---

## Monitoring Architecture

### Prometheus
Collects metrics from:

- Jenkins
- Node Exporter
- Kubernetes Cluster

### Grafana
Visualizes:

- CPU Utilization
- Memory Consumption
- System Metrics
- Kubernetes Metrics
- Jenkins Metrics

### Node Exporter
Provides host-level operating system metrics.

---

## Security Implementation

- Static Code Analysis using SonarQube
- Dependency Scanning using OWASP Dependency Check
- Container Security Scanning using Trivy
- Docker Image Inspection using Docker Scout
- Secure Credential Management in Jenkins

---

## AWS Services Used

- Amazon EC2
- Amazon EKS
- IAM
- Security Groups
- Load Balancers

---

## Project Outcomes

- Fully automated deployment pipeline
- Faster and reliable software releases
- Improved application security posture
- Real-time monitoring and alerting
- Scalable Kubernetes-based deployment
- GitOps-based deployment automation

---

## Screenshots

### Jenkins Pipeline
<img width="953" height="440" alt="6  build" src="https://github.com/user-attachments/assets/326a8af2-ea11-4088-953c-4a8477859d1b" />


### Argo cd
<img width="941" height="471" alt="image" src="https://github.com/user-attachments/assets/feb7d6ac-3776-48f0-ae69-8d4fca9a100c" />

<img width="940" height="511" alt="image" src="https://github.com/user-attachments/assets/c9f65d77-3b4b-459b-98b5-5cef0dbf489c" />



### Prometheus Dashboard
<img width="941" height="377" alt="image" src="https://github.com/user-attachments/assets/464ded26-7bb9-4d2f-994b-577394dc75fd" />


### Grafana Dashboard
<img width="941" height="469" alt="image" src="https://github.com/user-attachments/assets/340bd9c5-451f-4bfd-8071-63b316c200e6" />

<img width="941" height="350" alt="image" src="https://github.com/user-attachments/assets/26dd7bd7-b1c4-415c-9ca0-50df2d809f94" />


### Application Homepage deployment on Kubernetes port and port number
<img width="1000" height="708" alt="image" src="https://github.com/user-attachments/assets/015a0a89-f14e-49aa-8fd7-764c275a8cf0" />


---

## Key Learnings

- End-to-End CI/CD Pipeline Design
- DevSecOps Practices
- Containerization with Docker
- Kubernetes Orchestration
- GitOps Deployment Strategy
- Infrastructure Monitoring
- Cloud-Native Application Deployment
- Security Automation in DevOps

---

## Future Enhancements

- Terraform Infrastructure as Code
- Helm Chart Deployment
- Multi-Environment Deployment Strategy
- Automated Rollback Mechanism
- AWS CloudWatch Integration
- Kubernetes Autoscaling
- Advanced Alerting System

---

## Author

Utkarsh Rathor

DevOps | Cloud | Automation | Kubernetes | AWS
