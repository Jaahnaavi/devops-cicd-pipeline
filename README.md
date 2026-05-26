# DevOps CI/CD Pipeline with Docker, GitHub Actions & Kubernetes

## Project Overview

This project demonstrates an end-to-end DevOps CI/CD workflow using Docker, GitHub Actions, and Kubernetes.

The application is containerized using Docker, automatically built and pushed to Docker Hub using GitHub Actions, and deployed locally on Kubernetes using Minikube.

---

## Tech Stack

- Python Flask
- Docker
- Docker Hub
- GitHub Actions
- Kubernetes
- Minikube
- Linux
- Git & GitHub

---

## Features

- Containerized Flask application using Docker
- Automated CI/CD pipeline using GitHub Actions
- Automatic Docker image build and push to Docker Hub
- Kubernetes Deployment and Service configuration
- Local Kubernetes deployment using Minikube
- Scalable deployment with replicas

---

## Project Architecture

```text
Developer Pushes Code
          ↓
      GitHub Repo
          ↓
   GitHub Actions CI/CD
          ↓
     Docker Image Build
          ↓
      Docker Hub Push
          ↓
 Kubernetes Deployment
