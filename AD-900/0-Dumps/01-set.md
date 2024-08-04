1. Your team needs to have a tool that can provide serverless computing capabilities. Which of the following service can be used for this purpose?
 Azure Machine Learning.
 Azure loT Hub.
 Azure Al bot.
 Azure Functions.



Ans - functions


-----



2. Your team needs to have a tool that can be used to process data from millions of sensors. Which of the following service can be used for this purpose?
 Azure Machine Learning.
 Azure loT Hub.
 Azure Al bot.
 Azure Functions.




Ans - Azure loT Hub

Explanation: (important)

The correct answer is **Azure IoT Hub**.

**Reason:**
- **Azure IoT Hub** is designed specifically for managing and processing data from millions of IoT devices and sensors. It provides reliable and secure communication between IoT applications and the devices they manage.

**Azure Machine Learning** is used for building, training, and deploying machine learning models, not for handling raw data ingestion and processing from IoT sensors.

**In short:**
- **Azure IoT Hub**: Manages and processes data from millions of IoT sensors.
- **Azure Machine Learning**: Develops and deploys machine learning models.

Therefore, **Azure IoT Hub** is the appropriate service for processing data from millions of sensors.




----- 

3. A company needs to deploy a set of resources to Azure. Below are the key requirements for the deployment: The need to be deployed across several departments. The resources that need to be deployed are all of the same type. You need to recommend a solution to automate the deployment of the Azure resources. Which of the following would you use for this requirement?
 Virtual Machine scale sets.
 Management Groups.
 Azure AD.
 Azure Resource Manager Templates.


 Take reference from the above notes if required. 



 Ans - Azure Resource Manager Templates



 ------

4. Your company needs to deploy an application to virtual machines hosted in Azure. The solution must ensure an SLA of 99.99%. What is the minimum number of virtual machines and availability zones that you need to recommend for the deployment?
 One virtual machine and One availability zone.
 Two virtual machines and availability zone.
 One virtual machine and Two availability zones.
 Two virtual machines and Two availability zones.


Ans - Two virtual machines and Two availability zones.

Explanation: (important)

To achieve an SLA of 99.99% for an application deployed to virtual machines hosted in Azure, you should ensure redundancy across both virtual machines and availability zones. Here's how to approach this type of question:

### Understanding Azure SLA for VMs:

1. **Single VM with Premium SSD:** Provides an SLA of 99.9%.
2. **Two or more VMs in an Availability Set:** Provides an SLA of 99.95%.
3. **Two or more VMs across Availability Zones:** Provides an SLA of 99.99%.

### Solution for 99.99% SLA:
- **Minimum Requirement:** Two virtual machines deployed across two availability zones.

This configuration ensures that your application remains available even if one zone experiences an outage.

### Answer:
**Two virtual machines and two availability zones.**

### How to Approach Similar Questions in the Azure Exam:
1. **Identify the SLA Requirements:** Understand the specific SLA required (e.g., 99.99%).
2. **Check Azure SLA Documentation:** Know the SLA guarantees for different configurations.
3. **Redundancy and High Availability:** Ensure that the solution includes redundancy across multiple VMs and, if required, across multiple availability zones or regions.
4. **Minimum Configuration:** Choose the minimum number of VMs and zones that meet or exceed the required SLA.

### Answering Example:
For an SLA of 99.99%, you need to recommend:
- **Two virtual machines** and **two availability zones**.

This ensures high availability and meets the SLA requirements.



-----

Your team needs a tool that can be used to correlate events from multiple resources into a central repository. Which of the following can be used for this purpose?
 Azure Event Hubs.
 Azure Security Center.
 Azure AD.
 Azure Log Analytics.




Ans - Azure Log Analytics


Explaning the other 3 options: in important-terms.md

-----

5. A company is planning on hosting an application on an Azure Virtual Machine. It needs to be ensured that the application hosted on the virtual machine is accessible from the Internet over HTTPS. You decide to implement a DDOS protection plan. Would this satisfy the requirement?
 Yes.
 No.


Ans - No. 

explanation: (important)
While DDoS protection enhances the security and availability of your application, it does not configure the necessary components to ensure HTTPS access. You need to set up the VM with a public IP, configure NSG rules, set up a web server for HTTPS, and install an SSL certificate.



6. A team is currently planning on using Azure for hosting resources. They are going to create users which would have access to the Azure resources. The want to implement Multi-Factor authentication for the users. Is it required to deploy a federated solution to implement Multi-Factor authentication?
 Yes.
 No.



Ans - No

Explanation: (important)

**Answer: No**

### Reason:
Implementing Multi-Factor Authentication (MFA) for users in Azure does not require deploying a federated solution. 

### Key Points:
1. **Azure Active Directory (Azure AD):** Azure AD natively supports MFA without the need for a federated solution.
2. **Azure AD MFA:** You can enable MFA directly through the Azure AD settings.
3. **Configuration:** MFA can be configured and enforced using Azure AD security policies and conditional access policies.

### Summary:
Azure provides built-in support for Multi-Factor Authentication through Azure Active Directory, which can be enabled and managed without requiring a federated solution.

What is a federated solution?
A federated solution simplifies user management and enhances security by centralizing authentication and enabling Single Sign-On (SSO) across different applications and systems. This reduces the need for multiple logins and helps streamline access management.


Which of the following support plan gives you access to best practice information, health status and notifications, and 24/7 access to billing information at the lowest possible cost.
 Basic.
 Standard.
 Premier.
 Developer.


 Ans - Basic

 ----


If you plan to host a web application in the Azure platform as a service solution of Azure Web Apps, then you will have complete control over the underlying operating system.
 Yes.
 No.

 Ans - No.


 Explanation: (important)
When you use Azure Web Apps, which is part of Azure App Service, you are using a Platform as a Service (PaaS) solution. In a PaaS environment, you do not have complete control over the underlying operating system. Instead, Azure manages the infrastructure, including the OS, for you.


Using Azure Web Apps (PaaS) means you benefit from a managed service where Azure takes care of the underlying OS, but you do not have complete control over it. This is different from Infrastructure as a Service (IaaS), where you would have full control over the VM and OS.

---

Just read the below 2 questions once
You decide to create a virtual machine which is of the size D2s_v3. If you plan to stop the virtual machine, will you incur any costs for the storage associated with the virtual machine.
 Yes.
 No.

Ans - Yes

Your company is planning on using Azure for hosting Infrastructure level resources such as Azure Virtual Machines. When planning for the costing aspect for these resources, is there a flexibility offered when it comes to Capital and Operational Expenditure.
 Yes.
 No.

Ans - Yes


-----

You are looking at using a Software as a Solution service in Azure. Which of the following would you be responsible for?
 High availability of the solution.
 Configuration of the solution.
 Installing the solution.
 Scalability of the solution.

Ans - Configuration of the solution.

explanation: (important)

When using a Software as a Service (SaaS) solution in Azure, you are responsible for configuring the solution to meet your specific requirements. The SaaS provider is responsible for maintaining the underlying infrastructure, ensuring high availability, managing scalability, and handling software updates and maintenance. Your role is to configure the SaaS application to suit your business needs and user requirements.

-----


An administrator needs to run a script written in PowerShell. This script is going to create a virtual machine in Azure. Would the script run on a computer that runs Linux and has the Azure CLI tools installed?
 Yes.
 No.

 Ans - No

Ans - PowerShell scripts are typically executed using the PowerShell environment, which is not natively available on Linux systems without specific installation and configuration. While Azure CLI tools can be installed on a Linux computer, they are used to run Azure CLI commands, not PowerShell scripts. 


-----


An administrator needs to run a script written in PowerShell. This script is going to create a virtual machine in Azure. Would you be able to run the script on a machine that has Chrome OS installed and uses Azure Cloud Shell?
 Yes.
 No.

Ans - Yes


----


An administrator needs to run a script written in PowerShell. This script is going to create a virtual machine in Azure. Would you be able to run the script on a machine that has macOS and PowerShell core installed?
 Yes.
 No.

 Ans - Yes



