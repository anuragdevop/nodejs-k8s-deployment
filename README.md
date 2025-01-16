# Node.js K8s Deployment CI/CD Pipeline

This project demonstrates how to set up a complete CI/CD pipeline using Jenkins for a Node.js application deployed to Kubernetes.

## **Project Overview**

- **Dockerfile**: Builds a Docker image for a simple Node.js application.
- **Kubernetes**: Defines YAML files for deployment, service, and ingress to deploy the application to a Kubernetes cluster.
- **CI/CD Pipeline**: Uses Jenkins to automate the process of building, pushing Docker images to Docker Hub, and deploying to Kubernetes.

## **Technologies Used**
- Docker
- Kubernetes (with a cloud provider or Minikube)
- Jenkins (for CI/CD pipeline)
- Node.js
- GitHub (for version control)

## **Steps to Run**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/anuragdevop/nodejs-k8s-deployment.git
   cd nodejs-k8s-deployment

