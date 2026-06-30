# Enterprise IaC DevSecOps Pipeline

## Overview
This project demonstrates an automated DevSecOps pipeline for a sample e-commerce application. The pipeline integrates Static Application Security Testing (SAST), Software Composition Analysis (SCA), Infrastructure as Code (IaC) scanning, container security, and Dynamic Application Security Testing (DAST).

## Tech Stack
- GitHub Actions
- Docker
- SonarQube
- Trivy
- Checkov
- OWASP ZAP
- Terraform
- Flask

## Pipeline Flow

Developer → GitHub → GitHub Actions → SonarQube → Trivy → Checkov → Docker Build → OWASP ZAP → Secure Deployment

## Objective
Automate security validation across the software development lifecycle before deployment.
