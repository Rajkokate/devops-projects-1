# devops-projects-1 == EKS + K8s + CI/CD + Monitoring

# Kubernetes CI/CD Project

## Features
- Dockerized Python App
- Deployed on AWS EKS
- CI/CD via GitHub Actions
- Monitoring using Prometheus & Grafana
- Alerting via Alertmanager

## Setup Steps

1. Build Docker Image
2. Push to AWS ECR
3. Deploy to EKS using kubectl/Helm
4. Setup Monitoring using Helm

## Architecture
Developer → GitHub → CI/CD → ECR → EKS → Monitoring
