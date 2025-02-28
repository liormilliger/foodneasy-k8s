# Food'N'Easy Kubernetes Manifests

This repository contains Kubernetes manifests to deploy the Food'N'Easy application and PostgreSQL database.

## Prerequisites
- Kubernetes cluster (e.g., Minikube, GKE, EKS)
- Docker images: `liormilliger/liorm-foodneasy` and `liormilliger/liorm-foodneasy-db`
- `kubectl` configured to access your cluster

## Deployment Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/liormilliger/foodneasy-k8s.git
   cd foodneasy-k8s