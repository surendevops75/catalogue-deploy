# 🚀 Catalogue Service Deployment

![Jenkins](https://img.shields.io/badge/CI%2FCD-Jenkins-blue)
![Kubernetes](https://img.shields.io/badge/Platform-Kubernetes-blue)
![Helm](https://img.shields.io/badge/Package_Manager-Helm-green)
![DevOps](https://img.shields.io/badge/Automation-DevOps-orange)

## 📌 Overview

This repository contains deployment configurations for the RoboShop Catalogue Microservice using Helm Charts, Jenkins CI/CD pipelines, and Kubernetes.

The project demonstrates how application deployments can be automated across multiple environments using Infrastructure as Code and GitOps-friendly deployment practices.

---

## 🏗️ Architecture

```text
Developer
    │
    ▼
 GitHub Repository
    │
    ▼
 Jenkins Pipeline
    │
    ▼
 Helm Chart
    │
    ▼
 Kubernetes Cluster
    │
    ▼
 Catalogue Service
```

---

## 📂 Repository Structure

```text
.
├── templates/
├── Chart.yaml
├── Jenkinsfile
├── Jenkinsfile.bkp
├── values.yaml
├── values-dev.yaml
└── values-prod.yaml
```

---

## 📁 Components

### templates/

Contains Kubernetes resource templates used by Helm.

Examples:
- Deployment
- Service
- ConfigMaps
- Ingress
- Secrets

---

### Chart.yaml

Defines Helm chart metadata.

Includes:
- Chart name
- Version
- Description
- Dependencies

---

### Jenkinsfile

Pipeline definition for CI/CD automation.

Responsibilities:
- Build validation
- Deployment automation
- Environment selection
- Helm release management

---

### values.yaml

Default configuration values used by Helm.

Contains:
- Application settings
- Replica count
- Resource configurations
- Image information

---

### values-dev.yaml

Development environment configurations.

Examples:
- Development replicas
- Development resources
- Development-specific settings

---

### values-prod.yaml

Production environment configurations.

Examples:
- Production replicas
- Production resources
- High availability settings

---

## 🔄 Deployment Workflow

1. Developer pushes code changes.
2. Jenkins pipeline is triggered.
3. Pipeline validates deployment configuration.
4. Helm renders Kubernetes manifests.
5. Kubernetes applies resources.
6. Catalogue service gets deployed or updated.

---

## 🛠 Technologies Used

- Jenkins
- Helm
- Kubernetes
- YAML
- CI/CD
- RoboShop Microservices

---

## 🎯 Learning Objectives

This repository helps you understand:

- Helm Chart Development
- Kubernetes Deployments
- Jenkins Pipelines
- CI/CD Automation
- Environment-Based Configuration
- DevOps Best Practices
- Infrastructure as Code

---

## 👨‍💻 Ideal For

- DevOps Engineers
- Kubernetes Administrators
- Platform Engineers
- Cloud Engineers
- Site Reliability Engineers (SREs)

---

## 🚀 Features

- Helm-based deployment
- Jenkins CI/CD automation
- Environment-specific configurations
- Kubernetes-native deployment
- Scalable application management
- Infrastructure as Code

---

## ⭐ Support

If you find this repository useful:

- Star the repository ⭐
- Fork the project 🍴
- Share it with fellow DevOps Engineers 🚀

---

## 📚 Topics

Helm • Kubernetes • Jenkins • CI/CD • DevOps • Deployment Automation • RoboShop • Cloud Native