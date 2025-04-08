# 🚀 MLOps Pipeline 

A modular, scalable machine learning pipeline template using modern MLOps practices including orchestration, containerization, infrastructure as code, and CI/CD.

## ✨ Features

- ✅ Modular training & inference pipelines
- ✅ ML orchestration with Prefect
- ✅ Cloud storage (S3-compatible)
- ✅ Infrastructure provisioning with Terraform
- ✅ Containerized with Docker
- ✅ CI/CD with GitHub Actions

## 🧰 Tech Stack

- Python • Prefect • Docker • Terraform • AWS • GitHub Actions  
- Scikit-learn • Pandas • MLflow • Logging

## 📁 Project Structure

```plaintext
mlops-pipeline-template/
├── src/                   # Pipeline code (training/inference)
├── notebooks/             # Exploration and prototyping
├── terraform/             # Infra as Code (e.g., S3, EC2)
├── docker/                # Dockerfile for image builds
└── .github/workflows/     # CI pipeline for testing/linting
