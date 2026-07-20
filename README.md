# AWS CI/CD Multi-Service Deployment Pipeline

This repository demonstrates a complete AWS CI/CD pipeline for deploying three different application types using AWS developer tools.

## Overview

The project showcases automated build and deployment workflows for:

- Static website deployment to Amazon S3
- Spring Boot application deployment to Amazon ECS using Docker
- Python AWS Lambda function deployment

The pipeline uses GitHub as the source repository and AWS CodePipeline with CodeBuild to automate the software delivery process.

---

## Project Structure

```
demo-repo/
│
├── static-site/
│   └── index.html
│
├── ecs-app/
│   ├── Dockerfile
│   ├── buildspec-ecs.yml
│   └── src/
│
└── lambda-app/
    ├── lambda_function.py
    └── buildspec-lambda.yml
```

---

## AWS Services Used

- AWS CodePipeline
- AWS CodeBuild
- Amazon ECS
- Amazon ECR
- AWS Lambda
- Amazon S3
- AWS IAM
- CloudWatch
- GitHub

---

## CI/CD Workflow

```
Developer
    │
    ▼
GitHub Repository
    │
    ▼
AWS CodePipeline
    │
    ▼
AWS CodeBuild
    │
    ├──────────────► Static Website → Amazon S3
    │
    ├──────────────► Spring Boot App → Docker → Amazon ECR → Amazon ECS
    │
    └──────────────► Lambda Function → AWS Lambda
```

---

## Technologies

- Java
- Spring Boot
- Python
- Docker
- Git
- GitHub
- YAML
- HTML

---

## Objectives

- Learn Git-based development workflows
- Build automated CI/CD pipelines using AWS
- Deploy applications to multiple AWS compute services
- Understand build automation using CodeBuild
- Implement infrastructure following AWS DevOps best practices

---

## Status

🚧 Work in Progress

This repository is being developed as a hands-on AWS DevOps learning project covering source control, continuous integration, and continuous deployment.
