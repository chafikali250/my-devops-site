# 🚀 Interactive DevOps & Production Engineer Portfolio

This repository contains a high-tech, interactive single-page portfolio designed to showcase production engineering and DevOps expertise. It features an interactive Linux CLI terminal and a live visual simulator for CI/CD & GitOps pipelines.

## 🛠️ Project Tech Stack & Architecture
- **Frontend:** HTML5, CSS3 Glassmorphism, JavaScript ES6
- **Containerization:** Docker (Nginx Alpine base image)
- **Infrastructure as Code:** Terraform (Azure App Service / Storage)
- **CI/CD Pipeline:** GitHub Actions (Automated build, registry push, and deployment)
- **GitOps:** Argo CD & Kubernetes

## ⚙️ Local Deployment Quickstart

1. **Build the Docker Image:**
   ```bash
   docker build -t devops-portfolio:v1 .
