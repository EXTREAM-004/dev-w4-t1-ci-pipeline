
# DEV-W4-T1 – CI Pipeline Enhancement

This project demonstrates a CI pipeline using GitHub Actions.

## Features
- Build Docker images for frontend and backend
- Validate container build
- Deploy to local Kubernetes cluster
- Handle pipeline failures

## Pipeline Flow
1. Code pushed / Pull Request created
2. GitHub Actions builds Docker images
3. Container build validation runs
4. Deployment to local Kubernetes cluster using kubectl
5. Pipeline fails if build or deploy fails

## Run Locally
Install:
- Docker
- kubectl
- Minikube or Docker Desktop Kubernetes

Then run:

kubectl apply -f k8s/
