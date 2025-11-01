# 🚀 Smart Cloud DevOps Automation System (SCDAS)

**Smart Cloud DevOps Automation System (SCDAS)** is an end-to-end **DevOps cloud automation project** designed to streamline infrastructure provisioning, configuration, deployment, and monitoring of modern applications.  
It integrates **Terraform**, **Ansible**, **Docker**, **Kubernetes**, **Helm**, **Jenkins**, and **Prometheus-Grafana** into a unified automation workflow on **AWS**.

---

## 🧩 Project Overview

This project automates:

- 🌐 Cloud infrastructure provisioning using **Terraform**
- ⚙️ Server configuration and software installation with **Ansible**
- 🐳 Application containerization via **Docker**
- ☸️ Orchestration and deployment using **Kubernetes (EKS)**
- 🔄 Continuous Integration & Delivery using **Jenkins**
- 📊 Monitoring & alerting through **Prometheus**, **Grafana**, and **Alertmanager**


## 🧱 Tech Stack

| Category | Tool |
|-----------|------|
| **Infrastructure** | Terraform |
| **Configuration Management** | Ansible |
| **Containerization** | Docker |
| **Orchestration** | Kubernetes (EKS) |
| **CI/CD** | Jenkins, Helm |
| **Monitoring** | Prometheus, Grafana, Alertmanager |
| **Cloud Provider** | AWS |

---

## ⚙️ Setup Steps

```bash
# 1️⃣ Clone the repository
git clone https://github.com/atef-reda/Smart-Cloud-DevOps-Automation-System-SCDAS-.git
cd Smart-Cloud-DevOps-Automation-System-SCDAS-

# 2️⃣ Create the project architecture (if not already generated)
bash scripts/setup.sh

# 3️⃣ Initialize Git (if new environment)
git init
git add .
git commit -m "Initialize project structure"
git push origin main



