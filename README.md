# DevOps Capstone

## Project Overview

This project demonstrates an end-to-end DevOps pipeline for deploying a secure Python Flask microservice on Kubernetes using AWS.

## Technology Stack

- Python Flask
- Docker
- Kubernetes
- Terraform
- Jenkins
- Ansible
- Prometheus
- Grafana
- AWS EC2

## Project Progress

### ✅ Step 1 – Repository Initialization

- Created GitHub repository
- Initialized Git
- Created project structure
- Added `.gitignore`

### ✅ Step 2 – Flask Microservice

Completed:

- Created Flask application
- Added `/` endpoint
- Added `/health` endpoint
- Configured application to run on port **8080**

Status: ✔ Completed

### ✅ Step 3 – Dockerization

Completed:

- Created a multi-stage Docker build.
- Used `python:3.11-slim` as the base image.
- Created a non-root user (`appuser`).
- Configured Gunicorn as the production server.
- Exposed port `8080`.
- Built and tested the Docker container locally.

Status: ✔ Completed
