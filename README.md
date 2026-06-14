# Employee Management System on AWS

## Overview

A cloud-native Employee Management System built with Flask and PostgreSQL and deployed on AWS using Amazon ECS Fargate.

This project demonstrates containerization, cloud deployment, CI/CD automation, database integration, and AWS infrastructure management.

---

## Features

* Add Employee
* View Employee Records
* Edit Employee Information
* Delete Employee Records
* Persistent PostgreSQL Storage
* Responsive Web Interface

---

## AWS Architecture

GitHub Repository
↓
GitHub Actions CI/CD
↓
Amazon ECR (Docker Images)
↓
Amazon ECS Fargate
↓
Application Load Balancer (ALB)
↓
Flask Application
↓
Amazon RDS PostgreSQL

---

## AWS Services Used

* Amazon ECS Fargate
* Amazon ECR
* Amazon RDS PostgreSQL
* Application Load Balancer (ALB)
* Amazon CloudWatch
* AWS IAM

---

## Technology Stack

* Python
* Flask
* PostgreSQL
* Docker
* GitHub Actions
* Terraform
* AWS

---

## Screenshots

### Employee Management Dashboard

![Dashboard](screenshots/dashboard.png)

### Amazon rds

![Release](screenshots/rds.png)

### ECS Service

![ECS Service](screenshots/ecs_service.png)

### GitHub Actions Pipeline

![GitHub Actions](screenshots/githubactions.png)



---

## Project Structure

```text
.
├── .github/workflows
├── screenshots
├── templates
├── terraform
├── app.py
├── Dockerfile
├── requirements.txt
├── README.md
└── .gitignore
```

---

## CI/CD Workflow

1. Developer pushes code to GitHub
2. GitHub Actions workflow starts
3. Docker image is built
4. Image is pushed to Amazon ECR
5. Amazon ECS deploys the latest container
6. Application becomes available through the Application Load Balancer

---

## Key Achievements

* Containerized Flask application using Docker
* Automated deployment using GitHub Actions
* Deployed application on Amazon ECS Fargate
* Integrated PostgreSQL database on Amazon RDS
* Configured Application Load Balancer
* Implemented CloudWatch logging
* Built complete CRUD functionality
* Troubleshot ECS deployments, database connectivity, and container startup issues

---

## Challenges Solved

* ECS task startup failures
* Docker build and deployment issues
* PostgreSQL connectivity problems
* Gunicorn initialization issues
* ECS task definition revisions
* Infrastructure drift troubleshooting
* CI/CD deployment debugging

---

## Future Improvements

* Complete Terraform-managed infrastructure
* AWS Secrets Manager integration
* HTTPS using ACM certificates
* ECS Auto Scaling
* CloudWatch Alarms and Monitoring
* Blue/Green Deployments

---

## Release

**Current Stable Release:** `v1.0-working`

---

## Author

**Badal BK**

Cloud & DevOps Engineering Portfolio Project

2026
