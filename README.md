Ecommerce Application DevSecOps Pipeline

📌 Project Overview

This project demonstrates a fully automated DevSecOps CI/CD pipeline for deploying an ASP.NET Core Ecommerce application on Azure using Azure DevOps, Docker, Azure Kubernetes Service (AKS), SonarCloud, Trivy, Azure Container Registry (ACR), and Azure Monitor.

The pipeline automates code quality analysis, vulnerability scanning, containerization, Kubernetes deployment, and monitoring in a cloud-native environment.

⸻

🚀 Tech Stack

Cloud Platform

* Microsoft Azure

DevSecOps Tools

* Azure DevOps
* SonarCloud
* Trivy
* Docker
* Kubernetes (AKS)
* Azure Container Registry (ACR)

Monitoring Tools

* Azure Monitor
* Container Insights

Application Stack

* ASP.NET Core (.NET 10)

⸻

⚙️ Features

* Automated CI/CD pipeline using Azure DevOps
* SonarCloud code quality and security analysis
* Trivy filesystem vulnerability scanning
* Docker image vulnerability scanning
* Automated Docker image build and push to ACR
* Kubernetes deployment orchestration using AKS
* Centralized monitoring using Azure Monitor
* Fully automated cloud-native deployment
* Pipeline failure on HIGH/CRITICAL vulnerabilities

⸻

🏗️ Architecture Flow

GitHub / Azure Repos → Azure Pipeline → SonarCloud → Trivy → Docker → Azure Container Registry (ACR) → Azure Kubernetes Service (AKS) → Azure Monitor

⸻

📊 Monitoring

* AKS monitoring using Azure Monitor
* Container Insights integration
* Pod and node metrics monitoring
* Centralized logging and dashboards
* Application health monitoring

⸻

🐛 Problems Solved During Development

* AKS image pull authentication issue with ACR
* Kubernetes LoadBalancer public IP quota issue
* SonarCloud Quality Gate failure troubleshooting

⸻

📄 Detailed Documentation

See Project_Report.pdf for:

* Pipeline screenshots
* AKS deployment
* Azure Monitor dashboards
* Security scanning reports
