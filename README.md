# DevOps CI/CD Pipeline with Kubernetes

## Overview
This project demonstrates a complete DevOps workflow:
- Dockerized Node.js app
- CI/CD pipeline using GitHub Actions
- Kubernetes deployment

## Tech Stack
- Node.js
- Docker
- GitHub Actions
- Kubernetes

## How It Works
1. Code is pushed to GitHub
2. GitHub Actions runs tests
3. Docker image is built and pushed
4. Kubernetes pulls latest image and runs app

## Run Locally
```bash
docker build -t devops-app .
docker run -p 3000:3000 devops-app