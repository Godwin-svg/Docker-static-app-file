# Static Website Deployment Using Docker, Docker Hub, and AWS ECR

This project demonstrates how to containerize and deploy a static website using Docker, push the image to Docker Hub and Amazon Elastic Container Registry (ECR), and set up a secure AWS infrastructure with a three-tier VPC and Application Load Balancer (ALB).

---

## Prerequisites

- Docker installed locally
- AWS CLI installed and configured
- Docker Hub account
- AWS account with permissions to create ECR repositories and networking resources
- Git installed locally

---

## Steps to Deploy the Static Website

### 1. Setup Your GitHub Repository
- Create a GitHub repository to store your Dockerfile and website files.
- Clone the repository locally:
  ```bash
  git clone <your-repository-url>
  cd <repository-folder>
  
### 2. Create a Dockerfile
Inside your project folder, create a file named Dockerfile and add your website setup commands.

#### 3. Build and Run the Docker Container Locally
## Build your Docker image:
docker build -t jupiter .
