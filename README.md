# azure-k8s-deployment
A simple project to deploy an app to Azure Kubernetes

# Azure Kubernetes Deployment with Docker

This project demonstrates how to deploy a simple Flask app to Azure Kubernetes Service (AKS) using Docker.

## Steps:
1. **Dockerize the application**: A simple Python Flask app is containerized using Docker.
2. **Deploy to AKS**: The app is deployed to an Azure Kubernetes cluster using Kubernetes YAML files.
3. **CI/CD with Azure DevOps**: The process is automated with an Azure DevOps pipeline.

## Getting Started
1. Clone the repository to your local machine.
2. Set up an Azure Container Registry and AKS cluster.
3. Configure your Azure DevOps pipeline to trigger on changes to the main branch.
4. Push your changes to GitHub to trigger the pipeline.

## Technologies Used:
- Docker
- Kubernetes (AKS)
- Azure DevOps
- Flask (Python)

========================================================================================================================

**Steps to be followed:**

* Need an Azure account (Free trail / pay as you go)
* Once account is setup reate ACR and AKS 

Created azure ACR: 

az acr create \
  --name azurek8sdemoacr \
  --resource-group azure-k8s-demo \
  --location eastus \
  --sku Basic \
  --admin-enabled true


  --enable-addons monitoring \
  --generate-ssh-keys \
  --location $LOCATION


  

