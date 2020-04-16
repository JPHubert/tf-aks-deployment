# Introduction
This repository contains the IaC components to deploy an AKS cluster with associated Azure monitoring and operations components.

## Azure Infrastructure Components
- Single Vnet
- KeyVault
    - Restricted Access
- Storage Account
    - Restricted Access
- Log Analytics
- Application Insights
- RBAC
    - AKS SPN
    - Github service connector
    - Azure Devops service connector

## AKS Infrastructure Components
- 4 Node Cluster in a VM Scale Set
- Azure Front Door Ingress