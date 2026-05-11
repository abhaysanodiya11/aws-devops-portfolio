# AWS DevOps Portfolio Website

A production-style cloud portfolio website deployed on AWS using Amazon S3, CloudFront CDN and automated CI/CD pipelines with GitHub Actions.

## Live Website

[Live Demo](https://dkcn0u4a4132m.cloudfront.net/)

---

# Project Overview

This project demonstrates deployment automation and cloud hosting using AWS services and GitHub Actions.

The website is hosted on Amazon S3 and distributed globally using Amazon CloudFront CDN with HTTPS support.

CI/CD automation is implemented using GitHub Actions, allowing automatic deployment whenever new code is pushed to the GitHub repository.

---

# Architecture

Developer
↓
Git Push
↓
GitHub Repository
↓
GitHub Actions CI/CD
↓
Amazon S3
↓
CloudFront CDN
↓
Global Users

---

# AWS Services Used

- Amazon S3
- Amazon CloudFront
- AWS IAM

---

# DevOps Tools Used

- Git
- GitHub
- GitHub Actions
- CI/CD Pipeline

---

# Features

- Static website hosting
- HTTPS enabled delivery
- Global CDN distribution
- Automated deployment pipeline
- Git version control
- Responsive portfolio design

---

# CI/CD Workflow

Whenever code is pushed to the `main` branch:

1. GitHub Actions workflow starts automatically
2. AWS credentials are securely loaded using GitHub Secrets
3. Updated files are synced to Amazon S3
4. CloudFront serves the latest deployed version

---

# Project Structure

```bash
aws-devops-portfolio/
│
├── index.html
├── style.css
├── script.js
│
└── .github/
    └── workflows/
        └── deploy.yml
```

---

# Skills Demonstrated

- AWS Cloud Hosting
- CI/CD Automation
- Git & GitHub Workflow
- CloudFront CDN
- Infrastructure Deployment
- DevOps Fundamentals

---

# Future Improvements

- Terraform Infrastructure as Code
- Docker Containerization
- Automated CloudFront Cache Invalidation
- Custom Domain Integration
- Monitoring & Logging

---
