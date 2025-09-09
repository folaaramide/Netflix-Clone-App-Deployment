Deploy Netflix Clone on Kubernetes Using CI/CD Jenkins with Integrated Security (SonarQube & Trivy)

## Project Overview
This project demonstrates how to deploy a Netflix Clone application on Kubernetes (AWS EC2-1 master and 1 worker) using Jenkins CI/CD, while integrating static code analysis (SonarQube) and container vulnerability scanning (Trivy) for enhanced security.

## Technologies Used
- AWS (EC2)
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
5. **Kubernetes Deployment**

## ⚙️ Prerequisites
- AWS account with Kubernetes configured on one master and one worker node.
- Jenkins installed and configured with required plugins
- DockerHub account
- SonarQube server running
- `kubectl` configured for your kubernetes cluster

## 🚀 Deployment Instructions
1.Clone this repository:
git clone https://github.com/k21academyuk/Deploy-Netflix-Clone-on-Kubernetes

2.cd Deploy-Netflix-Clone-on-Kubernetes

3.Configure Jenkins credentials for DockerHub and SonarQube.

4.Trigger Jenkins Pipeline.

5.Access Netflix Clone via AWS EC2 public DNS and NordPort.

6.kubectl get svc
