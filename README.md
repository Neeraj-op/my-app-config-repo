# ArgoCD Learning Project

This is a simple project to learn ArgoCD with Kubernetes.

## Contents
- **manifests/deployment.yaml** - Nginx deployment with 2 replicas
- **manifests/service.yaml** - NodePort service exposing nginx on port 30001

## How to Deploy with ArgoCD
1. Install ArgoCD on Kubernetes cluster
2. Create an ArgoCD Application pointing to this repository
3. ArgoCD will automatically sync and deploy the application

## Access the Application
- Minikube IP: \`minikube ip\`
- URL: http://<minikube-ip>:30001