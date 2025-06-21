# Three-Tier-Web-Application-CI-CD-Pipeline-with-GitOps
This project implements a complete CI/CD pipeline for a three-tier web application (Presentation, Application, Database layers) using modern DevOps tools and GitOps methodology with ArgoCD. The infrastructure is provisioned as code, with automated builds, security scans, and deployments triggered by Git changes.
Technology Stack
Presentation	Java
Application	Java (Dockerized)
Database	MySQL (RDS/Container)
Infrastructure	Kubernetes (KOPS)

Tools Used
Jenkins	- CI Server for build/test automation
Git	Source - code version control
Maven	- Java dependency management
AWS S3- Artifact Storage
SonarQube	- Static code analysis
Trivy	- Container vulnerability scanning
Docker -	Containerization
Slack	- Notifications/alerts
ArgoCD	- GitOps deployment tool
Helm - Kubernetes package management

# CI pipeline 
![Screenshot (231)](https://github.com/user-attachments/assets/9bc1fcdc-340c-4935-8830-4cb58e7cc004)

# S3 as Artifact uploader
![Screenshot (232)](https://github.com/user-attachments/assets/b197e677-1772-4468-bd32-03e050b6996f)

# Using AI Agnets 
![Screenshot (233)](https://github.com/user-attachments/assets/5fa0a154-212c-4730-9ce7-ca81f6c5a5db)

# Deploying application using ArgoCD

Key Features
✅ End-to-End Automation – From code commit to production
✅ Security First – SonarQube + Trivy scans
✅ GitOps Approach – Declarative infrastructure managed via Git
✅ Multi-Environment – Separate dev/stage/prod clusters

Why This Matters
This pipeline reduces manual errors, enforces security checks, and enables auditable deployments through Git history. The GitOps approach ensures cluster state always matches Git, making rollbacks and debugging straightforward.

Star this repo if you find it useful! Contributions welcome.
