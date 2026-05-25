# DevOps Homelab 🚀

![Python](https://img.shields.io/badge/python-3.10-blue)
![Docker](https://img.shields.io/badge/docker-blue)
![Terraform](https://img.shields.io/badge/terraform-purple)
![Azure](https://img.shields.io/badge/azure-cloud-blue)
![Status](https://img.shields.io/badge/status-in%20progress-orange)

---

## 📌 Overview

This project is a DevOps homelab that demonstrates a full end-to-end cloud and CI/CD workflow.

It simulates how a real-world application moves from local development to a fully automated cloud infrastructure using modern DevOps practices.

The goal is to build practical experience with application development, containerization, automation, Infrastructure as Code, and cloud deployment.

---

## 🔁 End-to-End Workflow

Local Development (Flask) → Docker Containerization → GitHub Repository → GitHub Actions (CI/CD - in progress) → Terraform (Infrastructure as Code) → Microsoft Azure (Cloud Resources)

This represents a real-world DevOps pipeline where application delivery and infrastructure provisioning are automated and version-controlled.

---

## 🎯 Goals

- Learn and apply DevOps principles in a real project
- Build CI/CD pipelines using GitHub Actions
- Containerize a Python Flask application using Docker
- Use Terraform for Infrastructure as Code
- Deploy resources on Microsoft Azure
- Build a portfolio-ready cloud engineering project

---

## 🧰 Tech Stack

- Python (Flask)
- Docker
- Git & GitHub
- GitHub Actions
- Terraform
- Microsoft Azure

---

## ☁️ Infrastructure (Terraform + Azure)

Infrastructure is managed using Infrastructure as Code (IaC) with Terraform.

Terraform is used to define and provision cloud resources in Microsoft Azure in a repeatable and version-controlled way.

Current deployment:
- Azure Resource Group created via Terraform

Future improvements:
- Azure App Service or Container Apps deployment
- Virtual Network (VNet) and subnet architecture
- Azure Key Vault for secrets management
- Full CI/CD deployment pipeline to Azure

---

## 🚀 How to run locally

### Build the Docker image

```bash
docker build -t devops-homelab .
```

### Run container

```bash
docker run -p 5000:5000 devops-homelab
```

---

## 📸 Screenshots

All screenshots are stored in: `docs/screenshots/`

Includes:

- Terraform plan output  
- Terraform apply output  
- Azure resource creation  
- CI/CD pipeline runs 

---

## 📈 Project Status

**Status:** 🚧 In progress

**Current focus:**
- Terraform infrastructure setup  
- Azure deployment  
- CI/CD pipeline improvements 

---

## 🧠 What I learned

- Docker containerization  
- GitHub Actions CI/CD pipelines  
- Terraform Infrastructure as Code  
- Microsoft Azure cloud basics  
- End-to-end DevOps workflow 

---

## 👤 Author

Sven Velleman  
Aspiring Cloud & DevOps Engineer