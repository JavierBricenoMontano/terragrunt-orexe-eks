# EKS AWS - TERRAGRUNT - OREXE

## Project Objective

The goal of this project is to deploy an EKS cluster on AWS using Terraform and Terragrunt. Modules are used for the creation of the network and the EKS cluster to ensure a clean and organized code structure. The final configuration is located in the AWS/live/dev folder, where these modules are implemented using Terragrunt.

## Technologies Used

- AWS: Cloud infrastructure provider.
- EKS (Elastic Kubernetes Service): Managed Kubernetes service by AWS.
- Terraform: Infrastructure as Code (IaC) tool.
- Terragrunt: Terraform wrapper that facilitates managing repetitive configurations and modularity.

## Requirements

Before starting the project, make sure you have the following installed:

    1. Terraform: Download and install Terraform
    2. Terragrunt: Download and install Terragrunt
    3. AWS CLI: Install AWS CLI
    4. AWS credentials configured in your environment.

## Steps to Initialize, Plan, and Apply with Terragrunt

    1. Navigate to the Project Directory.
    ```
    cd AWS/live/dev
    ```
    2. Initialize the Project
    ```
    terragrunt run-all init
    ```
    3. Plan the Deployment
    ```
    terragrunt run-all plan
    ```
    4. Apply the Changes
    ```
    terragrunt run-all apply
    ```
