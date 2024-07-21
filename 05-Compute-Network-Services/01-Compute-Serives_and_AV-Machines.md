# Azure Compute and Networking Services

## Overview
- Covers various Azure compute services like virtual machines, virtual machine scale sets, app services
- Also includes networking services like virtual networking, VPNs, DNS

## Technical Pillars of Azure
1. Compute Services
2. Networking Services
3. Storage Services (including databases)

## Compute Services
- Execute code in the cloud (websites, apps, banking functionalities)
- Key types of compute services:
  - Virtual Machines
  - Scale Sets
  - Web Apps
  - Container Services (Azure Container Instances, Azure Container Apps, Kubernetes)
  - Azure Virtual Desktop

### Virtual Machines (VMs)
- Closest analog to a physical server or computer
- Full control over the VM, including software installation and settings
- Hosted on a physical machine (host) subdivided into slices (virtualization)

### Virtualization Analogy
- **Standalone Server**: Like a single detached house with private services and infrastructure
- **Virtual Machine**: Like an apartment in an apartment building with shared services (e.g., garbage, sewer, water) and some private services (e.g., air conditioning, refrigeration)

### Virtual Machines as Infrastructure as a Service (IAAS)
- Full control over the operating system (Windows or Linux)
- Supports multiple distributions of Linux and versions of Windows
- Virtual machines are slices of physical machines shared with other customers
- Comparable to AWS EC2 (Elastic Compute Cloud)

### Types of Virtual Machines
- Predefined images and configurations provided by Microsoft
- Over 700 different types to choose from based on needs (CPU, RAM, disk space, operations per second)

## Networking Services
- Includes virtual networking, VPNs, DNS
- Essential for connecting and securing Azure compute services

## Key Points
- Compute services allow for the execution of code and hosting applications in the cloud
- Virtual machines provide a high degree of control and flexibility, akin to physical servers but with the benefits of virtualization
- Azure offers a wide variety of predefined VM configurations to meet different needs
- Networking services ensure secure and efficient connectivity for Azure compute services