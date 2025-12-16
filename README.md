# Simple Docker CI/CD Project

This is a beginner-friendly CI/CD project demonstrating Docker and GitHub Actions.

## What this project does
- Simple Python application
- Dockerized using a Dockerfile
- CI/CD pipeline using GitHub Actions
- Automatically builds and pushes Docker image to Docker Hub on every push

## Tools used
- AWS EC2 (Ubuntu)
- Docker
- Docker Hub
- GitHub
- GitHub Actions

## CI/CD Flow
1. Code is pushed to GitHub
2. GitHub Actions triggers automatically
3. Docker image is built
4. Image is pushed to Docker Hub

## How to run the image
```bash
docker pull akshathagkdocker012/simple-ci-docker:latest
docker run akshathagkdocker012/simple-ci-docker:latest
