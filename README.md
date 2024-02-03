
# Infrastructure as Code (IAC) for Amazon EKS with Terraform

This repository contains Terraform code for provisioning and managing an Amazon Elastic Kubernetes Service (EKS) cluster on AWS.

## Prerequisites

Before you begin, ensure you have the following prerequisites:

- AWS CLI installed and configured with the necessary access credentials.
- Terraform CLI installed on your local machine.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/iac-eks.git
   cd eks-terraform
Initialize the Terraform configuration:


terraform init
Review and customize the variables.tf file to suit your requirements.

Deploy the EKS cluster:


terraform apply
Confirm the deployment by typing yes when prompted.

Configuration
variables.tf: Define variables such as region, cluster name, and node group settings.
eks-cluster.tf: Defines the EKS cluster configuration.
node-group.tf: Configures the worker nodes using an Auto Scaling Group.
Usage
To apply changes to the infrastructure, run:


terraform apply
To destroy the EKS cluster and associated resources, run:


terraform destroy
