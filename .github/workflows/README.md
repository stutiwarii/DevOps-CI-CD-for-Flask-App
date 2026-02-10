# DevOps CI/CD for Flask App

A Flask application with automated CI/CD pipeline for cloud deployment.

## Features
- Containerized Flask app using Docker
- CI/CD pipeline with GitHub Actions
- Deploys to AWS Elastic Beanstalk automatically
- Zero-downtime deployment

## Tech Stack
- Flask (Python)
- Docker
- GitHub Actions
- AWS Elastic Beanstalk

## Usage
1. Clone the repository
2. Build Docker image:
```bash
docker build -t flask-app .
