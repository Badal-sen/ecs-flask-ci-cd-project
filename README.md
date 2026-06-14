# Employee Management System on AWS

## Overview

A cloud-native Employee Management System built with Flask and PostgreSQL and deployed on AWS using ECS Fargate.

This project demonstrates containerization, cloud deployment, CI/CD automation, database integration, and AWS infrastructure management.

## Live Features

* Add Employee
* View Employee List
* Edit Employee Details
* Delete Employee Records
* Persistent PostgreSQL Storage

## Architecture

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

## AWS Services Used

* Amazon ECS Fargate
* Amazon ECR
* Amazon RDS PostgreSQL
* Application Load Balancer
* Amazon CloudWatch
* AWS IAM

## Technology Stack

* Python
* Flask
* PostgreSQL
* Docker
* GitHub Actions
* Terraform
* AWS

## Key Achievements

* Containerized application using Docker
* Automated deployments using GitHub Actions
* Deployed application on Amazon ECS Fargate
* Configured PostgreSQL database on Amazon RDS
* Implemented Application Load Balancer
* Integrated CloudWatch logging
* Implemented CRUD operations for employee management
* Troubleshot ECS deployment, networking, and database connectivity issues

## Screenshots

### Employee Dashboard

Add screenshot here

### AWS ECS Service

Add screenshot here

### GitHub Actions Pipeline

Add screenshot here

### PostgreSQL Database

Add screenshot here

## Project Structure

```text
.
├── .github/workflows
├── terraform
├── templates
├── screenshots
├── app.py
├── Dockerfile
├── requirements.txt
└── README.md
```

## Future Improvements

* Complete Terraform-managed infrastructure
* AWS Secrets Manager integration
* HTTPS with ACM
* ECS Auto Scaling
* Monitoring and Alerts
* Blue/Green Deployments

## Release

Current Stable Release: v1.0-working
