### Azure Compute Services Overview

#### Virtual Machines and Virtual Machine Scale Sets
- **Control**: Full control over the server.
- **Customization**: Install any software, change settings, choose operating systems.
- **Type**: Infrastructure as a Service (IaaS).

#### App Services / Web Apps
- **Control**: Limited control over the server.
- **Deployment**: Package code and configuration, upload to Azure.
- **Promise**: Azure guarantees performance without specifying the underlying server details.
- **Type**: Platform as a Service (PaaS).
- **Benefits**:
  - Easier development and testing.
  - Integration with GitHub.
  - A/B testing using deployment slots.
  - Limited server access: FTP, logging, console window.
- **Drawbacks**: Cannot change server settings or install unsupported software.

#### Containers
- **Concept**: Package code and necessary libraries into a container image.
- **Deployment**: Deploy the same image across different environments (staging, development, production) without recompiling.
- **Support**: Azure supports containers extensively.
  
##### Main Container Options in Azure:
1. **Azure Container Instances (ACI)**
   - Quick and easy deployment.
   - Suitable for demos or small applications.
   - Limited scaling options.

2. **Container Apps**
   - Advanced features similar to web services.
   - Not as complex as Azure Kubernetes Service (AKS).

3. **Azure Kubernetes Service (AKS)**
   - Enterprise-grade container orchestration.
   - Uses clusters.
   - Complex tools and commands.

4. **Other Options**: Service Fabric supports containers.

#### Azure Virtual Desktop
- **Functionality**: Virtualized Windows desktop accessible from anywhere.
- **Access**: Log in using user ID and password on any console or device.
- **Flexibility**: Continue the same session across multiple devices (work console, home, phone).
- **Platform**: Runs on Azure.

#### Next Topic Teaser
- **Azure Functions**: Upcoming discussion on another compute service.

### Summary
- **IaaS**: Full control (e.g., Virtual Machines).
- **PaaS**: Limited control with performance promises (e.g., App Services/Web Apps).
- **Containers**: Flexible deployment with varying complexity (ACI, Container Apps, AKS).
- **Azure Virtual Desktop**: Access your Windows desktop from anywhere.

These notes should help you understand the various Azure compute services and their key characteristics, aligning with the concepts covered in the AZ-900 certification exam.