# Sec and DevOps Assignment

Submitted by: **Amrish Kumar**

This repository contains the solutions for both assignments given as part of the **DevSecOps Programme**.

The project covers:

1. **Assignment 1 — Automated Container Build Pipeline**
2. **Assignment 2 — Foundational Cloud Provisioning using Terraform**

---

# Assignment 1 — Automated Container Build Pipeline

## Overview

The objective of this assignment was to containerize a Node.js application and automate the build process using **Docker** and **GitHub Actions**.

A simple Express.js application was created, Dockerized, and configured to automatically build and run whenever code is pushed to GitHub.

## Technologies Used

* Node.js
* Express.js
* Docker
* GitHub Actions

## Features

✅ Containerized Node.js Application
✅ Dockerfile using best practices
✅ Automated Docker build pipeline
✅ GitHub Actions workflow automation

## Project Workflow

1. Create a Node.js Express application
2. Write Dockerfile for containerization
3. Configure GitHub Actions workflow
4. Trigger automatic build on push
5. Build and run Docker container

## Project Structure

```text
Sec-and-DevOps-Assignment/
│── .github/
│   └── workflows/
│       └── docker-runner.yaml
│── Dockerfile
│── docker-compose.yml
│── index.js
│── package.json
│── README.md
```

---

# Assignment 2 — Foundational Cloud Provisioning

## Overview

This assignment focuses on provisioning AWS infrastructure using **Terraform Infrastructure as Code (IaC)**.

The infrastructure includes:

* Custom VPC
* Public Subnet
* Internet Gateway
* Route Table
* Security Group
* EC2 Instance

All infrastructure is created through Terraform configuration files.

## Technologies Used

* Terraform
* AWS
* EC2
* VPC
* Security Groups

## Features

✅ Automated Infrastructure Provisioning
✅ VPC and Networking Setup
✅ EC2 Instance Deployment
✅ Security Group Configuration
✅ Terraform Outputs for Instance Details

## Terraform Workflow

### Initialize Terraform

```bash
terraform init
```

### Check Infrastructure Plan

```bash
terraform plan
```

### Apply Infrastructure

```bash
terraform apply
```

### Destroy Infrastructure

```bash
terraform destroy
```

---

## Deliverables

* Terraform Configuration Files
* Dockerized Node.js Application
* GitHub Actions Workflow
* Docker Build Pipeline
* AWS Infrastructure Provisioning
* Screenshots and Outputs

---

## Conclusion

This assignment demonstrates practical implementation of **DevOps and Cloud Automation concepts**, including:

* Containerization using Docker
* CI/CD Automation using GitHub Actions
* Infrastructure Provisioning using Terraform
* AWS Resource Management

The goal was to automate application deployment and cloud infrastructure provisioning using modern DevOps practices.
