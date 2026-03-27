# Python-Project
# 🚀 AWS CI/CD Pipeline Project

## 📖 Overview
This project demonstrates an end-to-end CI/CD pipeline using AWS services to automate build and deployment of a Python application.

## 🏗️ Architecture
GitHub → CodePipeline → CodeBuild → S3 → CodeDeploy → EC2

## ⚙️ Tech Stack
- AWS CodePipeline
- AWS CodeBuild
- AWS CodeDeploy
- Amazon S3
- Amazon EC2
- Docker
- GitHub

## 🔄 Pipeline Flow
1. Code pushed to GitHub
2. CodePipeline triggers automatically
3. CodeBuild builds application and pushes Docker image
4. Artifact stored in S3
5. CodeDeploy deploys application to EC2

## 📦 Key Files
- `buildspec.yml` → Defines build steps
- `appspec.yml` → Defines deployment lifecycle
- `scripts/` → Deployment scripts

## 🧠 Learnings
- CI/CD pipeline orchestration in AWS
- IAM roles and permissions handling
- Debugging pipeline failures
- Deployment strategies

## ⚠️ Challenges Faced
- Artifact not generating in S3
- IAM permission issues
- Deployment failures due to appspec.yml

 
