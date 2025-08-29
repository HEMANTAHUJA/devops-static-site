# 🚀 Static Site on Azure

This is a Dockerized static website deployed via a CI/CD pipeline using GitHub Actions, Azure Container Registry, and Azure Web App.

## 🔧 Tech Stack

- HTML/CSS (Static Site)
- Docker
- GitHub Actions (CI/CD)
- Azure Container Registry (ACR)
- Azure Web App (Linux)

## 📦 CI/CD Pipeline

Every push to `main`:
1. Builds Docker image
2. Pushes to ACR
3. Deploys to Azure Web App

![Build Status](https://github.com/HEMANTAHUJA/devops-static-site/actions/workflows/deploy.yml/badge.svg)

## 🌐 Live Site

👉 [Visit Site](https://webapp-hemant-static-a3d6cng6djdfe6hg.centralindia-01.azurewebsites.net/)

## 📈 Highlights

- Fully automated deployment
- Clean, minimal UI
- Scalable via Azure App Service