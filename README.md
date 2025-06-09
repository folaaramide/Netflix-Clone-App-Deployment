# Netflix-Clone-App-Deployment
# 🚀 Deploy Netflix Clone on Kubernetes Using CI/CD Jenkins with Integrated Security (SonarQube & Trivy)

## 📖 Project Overview
This project demonstrates how to deploy a Netflix Clone application on Kubernetes (AWS EKS) using Jenkins CI/CD, while integrating static code analysis (SonarQube) and container vulnerability scanning (Trivy) for enhanced security.

## 🛠️ Technologies Used
- AWS (EC2, EKS)
- Jenkins
- Docker & DockerHub
- SonarQube
- Trivy
- Kubernetes (kubectl)
- Netflix Clone App (Node.js, React)

## 📌 Pipeline Workflow
1. **Clone Repository**
2. **Static Code Analysis** using SonarQube
3. **Docker Build & Trivy Scan**
4. **Docker Push** to DockerHub
5. **Kubernetes Deployment** to EKS

## ⚙️ Prerequisites
- AWS account with EKS configured
- Jenkins installed and configured with required plugins
- DockerHub account
- SonarQube server running
- `kubectl` configured for your EKS cluster

## 📂 Project Structure
netflix-clone-k8s-cicd/
├── api/ # Netflix Clone API
├── Jenkinsfile # CI/CD pipeline definition
├── k8s/ # Kubernetes manifests
│ ├── deployment.yaml
│ ├── service.yaml
│ └── configmap.yaml
├── sonar-project.properties
└── README.md

## 🚀 Deployment Instructions
1. Clone this repository:
   git clone https://github.com/k21academyuk/Deploy-Netflix-Clone-on-Kubernetes
   cd Deploy-Netflix-Clone-on-Kubernetes
Configure Jenkins credentials for DockerHub and SonarQube.

Trigger Jenkins Pipeline.

Access Netflix Clone via AWS LoadBalancer URL:

kubectl get svc
