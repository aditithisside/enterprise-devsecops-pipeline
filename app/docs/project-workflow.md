# Enterprise DevSecOps Pipeline Workflow

1. Developer pushes code.
2. GitHub Actions starts automatically.
3. SonarQube performs SAST.
4. Trivy scans dependencies and Docker image.
5. Checkov scans Terraform files.
6. Docker image is built.
7. OWASP ZAP performs DAST.
8. Reports are generated.
9. Application is ready for deployment.
