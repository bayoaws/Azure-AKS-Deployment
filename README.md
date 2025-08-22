# Azure AKS Deployment with Terraform

This project provides Terraform configurations to deploy a production-ready Azure Kubernetes Service (AKS) cluster, along with supporting resources such as a resource group, virtual network, subnet, Log Analytics workspace, and a public IP for ingress.

## Features

- **Automated AKS Cluster Deployment**: Easily deploy a managed Kubernetes cluster on Azure.
- **Customizable Parameters**: Configure cluster name, region, node count, VM size, Kubernetes version, and more via variables.
- **Integrated Monitoring**: Log Analytics workspace is provisioned and integrated for container insights.
- **Virtual Network & Subnet**: Secure networking setup for AKS nodes.
- **Ingress Ready**: Public IP resource for ingress controllers.
- **RBAC & Managed Identity**: Secure cluster with RBAC and Azure-managed identity.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) >= 1.0
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- Azure subscription with sufficient permissions

## Usage

1. **Clone the repository**

   ```sh
   git clone <repository-url>
   cd Azure-AKS-Deployment
   ```
2. **Initialize Terraform**
 ```sh
     terraform init
 ```


