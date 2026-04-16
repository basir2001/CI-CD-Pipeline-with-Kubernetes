# CI/CD Pipeline with Kubernetes

## Short description
This project demonstrates a CI/CD pipeline that builds, tests, and deploys a containerized application automatically to a Kubernetes cluster.

The goal of this project is to simulate a real-world DevOps workflow, from code push to deployment, using modern tools like Docker, CI/CD pipelines, and Kubernetes.

## Goals
- Build a complete CI/CD pipeline from scratch  
- Automate build, test, and deployment processes  
- Containerize an application using Docker  
- Deploy and manage the application using Kubernetes  
- Understand real-world DevOps workflows 

## Tech Stack
- Java / Node.js
- Docker
- Kubernetes (Minikube)
- Kubectl
- GitHub Actions

## Architecture
Code push → CI pipeline → Docker build → Image registry → Kubernetes deployment

## How to run
1. Clone repository
2. Build Docker image
3. Apply Kubernetes manifests
4. Trigger pipeline via push

## CI/CD Pipeline
- Build stage: compile application
- Test stage: run unit tests
- Build image: create Docker image
- Deploy stage: push to Kubernetes cluster

## Future Improvements
- Add monitoring (Prometheus/Grafana)
- Add Helm charts
- Improve rollback strategy
