# mapup-assessment

# Sample Application with Docker, AWS ECR, and GitHub Actions

This repository contains a sample application along with configurations for Docker, AWS ECR, and GitHub Actions. The goal is to demonstrate an automated workflow for building and pushing Docker images to AWS ECR using GitHub Actions.

## Table of Contents

1. [GitHub Repository Setup](#github-repository-setup)
2. [Docker Image Creation](#docker-image-creation)
3. [AWS ECR Setup](#aws-ecr-setup)
4. [GitHub Actions Workflow](#github-actions-workflow)
5. [Security and Best Practices](#security-and-best-practices)

## GitHub Repository Setup

- Initialize a GitHub repository with a simple Hello World application.
- Included a Dockerfile for building the application.

## Docker Image Creation

- Ensure the Docker image is optimized for size and build time.

## AWS ECR Setup

Create an AWS ECR repository to store Docker images.

- Configure necessary IAM roles and policies for access management.
-->> AmazonEC2ContainerRegistryFullAccess, AmazonElasticContainerRegistryPublicFullAccess

## GitHub Actions Workflow

Develop a GitHub Actions workflow that triggers on push request events.

- Include steps to build the Docker image and push it to AWS ECR.
- Implemeted slack integration for workflow build status for alert

## Security and Best Practices

Implement security best practices for Docker and GitHub Actions.

- Use secrets for storing sensitive credentials.

### Prerequisites

- Docker Knowledge
- AWS account
- GitHub account and repository
- Basic Knowledge of YAML, CI/CD


