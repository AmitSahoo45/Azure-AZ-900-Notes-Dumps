1. A team of developers at your company plans to deploy, and then remove, 50 virtual machines each week. All the virtual machines are configured by using Azure Resource Manager templates. You need to recommend which Azure service will minimize the administrative effort required to deploy and remove the virtual machines. What should you recommend?
 Azure Reserved Virtual Machine (VM) Instances.
 Azure DevTest Labs.
 Azure virtual machine scale sets.
 Microsoft Managed Desktop.


Ans - Azure Dev Test Labs
explanation: Azure DevTest Labs is the best fit for your requirement of minimizing administrative effort while frequently deploying and removing virtual machines. It provides automated management, cost control, and self-service capabilities tailored for development and testing scenarios.


2. A support engineer plans to perform several Azure management tasks by using the Azure CLI. You install the CLI on a computer. You need to tell the support engineer which tools to use to run the CLI. Which two tools should you instruct the support engineer to use? Each correct answer presents a complete solution.
 Command Prompt.
 Azure Resource Explorer.
 Windowe PowerShell.
 Windows Defender Firewall.
 Network and Sharing Center.

Ans - Command Prompt, Windows PowerShell

----


3. You need to identify the type of failure for which an Azure Availability Zone can be used to protect access to Azure services. What should you identify?
 A physical server failure.
 An Azure region failure.
 A storage failure.
 An Azure data center failure.


Ans - An Azure data center failure.

Kindly refer to Zones notes for better understanding.

4. You have a virtual machine named VM1 that runs Windows Server 2016. VM1 is in the East US Azure region. Which Azure service should you use from the Azure portal to view service failure notifications that can affect the availability of VM1?
 Azure Service Fabric.
 Azure Monitor.
 Azure virtual machines.
 Azure Advisor.


Ans - Azure Monitor
Azure Monitor is the correct service to use from the Azure portal to view service failure notifications that can affect the availability of your virtual machine (VM1) running in the East US Azure region. It provides comprehensive monitoring and integrates with Azure Service Health to keep you informed about any issues affecting your services.


-----

4. You have an Azure environment that contains multiple Azure virtual machines. You plan to implement a solution that enables the client computers on your on-premises network to communicate to the Azure virtual machines. You need to recommend which Azure resources must be created for the planned solution. Which two Azure resources should you include in the recommendation?
 A virtual network gateway.
 A load balancer.
 An application gateway.
 A virtual network.
 A gateway subnet.



Ans - A virtual network gateway, A gateway subnet

----

5. Your company plans to move several servers to Azure. The company compliance policy states that a server named FinServer must be on a separate network segment. You are evaluating which Azure services can be used to meet the compliance policy requirements. Which Azure solution should you recommend?
 A resource group for FinServer and another resource group for all the other servers.
 A virtual network for FinServer and another virtual network for all the other servers.
 A VPN for FinServer and a virtual network gateway for another server.
 One resource group for all the servers and a resource lock for FinServer.

[need to re-answer this]


Ans - A virtual network for FinServer and another virtual network for all the other servers.

----

6. You plan to map a network drive from several computers that run Windows 10 to Azure Storage. You need to create a storage solution in Azure for the planned mapped drive. What should you create?
 An Azure SQL database.
 A virtual machine data disk.
 A Files service in a storage account.
 A Blobs service in a storage account.


[need to re-answer this]

Ans - A Files service in a storage account.
-----

7. Your company plans to migrate all its network resources to Azure. You need to start the planning process by exploring Azure. What should you create first?
 A subscription.
 A resource group.
 A virtual network.
 A management group.



ANs - A subscription.
explanation:
The subscription is the primary entity you must create first because it provides the framework for organizing and managing all subsequent Azure resources. Without a subscription, you cannot create resource groups, virtual networks, or other resources.

-----

9. You have an on-premises application that sends email notifications automatically based on a rule, You plan to migrate the application to Azure. You need to recommend a serverless computing solution for the application. What should you include in the recommendation?
 A web app.
 A server image in Azure Marketplace.
 A logic app.
 An API app.


Ans - A logic app.
explanation: Logic Apps is the correct serverless computing solution to recommend for your application that sends email notifications based on a rule. Logic Apps provides a visual designer to automate workflows and integrate with various services, including email services, without the need to write code.

-----

10. You have an Azure web app. You need to manage the settings of the web app from an iPhone. What are two Azure management tools that you can use? Each correct answer presents a complete solution.
 Azure CLI.
 The Azure portal.
 Azure Cloud Shell.
 Windows PowerShell.
 Azure Storage Explorer.



Ans - The Azure portal, Azure Cloud Shell.

-----

11. You have an Azure subscription named Subscription1. You sign in to the Azure portal and create a resource group named RG1. From Azure documentation, you have the following command that creates a virtual machine named VM1. az vm create --resource-group RG1 --name VM1 --image UbuntuLTS --generate-ssh-keys You need to create VM1 in Subscription1 by using the command. Solution: From the Azure portal, launch Azure Cloud Shell and select PowerShell. Run the command in Cloud Shell. Does this meet the goal?
 Yes.
 No.


Ans - No.
[this is a very interesting question] - check extra-prompts.md for more details.

----

12. Which service provides serverless computing in Azure?
 Azure Virtual Machines.
 Azure Functions. 
 Azure storage account.
 Azure Container Instances.



Ans -> Azure Functions

-----

You have an Azure subscription named Subscription1. You sign in to the Azure portal and create a resource group named RG1. From Azure documentation, you have the following command that creates a virtual machine named VM1. az vm create --resource-group RG1 --name VM1 --image UbuntuLTS --generate-ssh-keys You need to create VM1 in Subscription1 by using the command. Solution: From the Azure portal, launch Azure Cloud Shell and select Bash. Run the command in Cloud Shell. Does this meet the goal?
 Yes.
 No


Ans - Yes

-----

Which Azure service provides a set of version control tools to manage code?
 Azure Repos.
 Azure DevTest Labs.
 Azure Storage.
 Azure Cosmos DB.



Ans - Azure Repos

-----

Your company plans to automate the deployment of servers to Azure. Your manager is concerned that you may expose administrative credentials during the deployment. You need to recommend an Azure solution that encrypts the administrative credentials during the deployment. What should you include in the recommendation?
 Azure Key Vault.
 Azure Information Protection.
 Azure Security Center.
 Azure Multi-Factor Authentication (MFA).



Ans - Azure Key Vault

-----

You plan to deploy several Azure virtual machines. You need to control the ports that devices on the Internet can use to access the virtual machines. What should you use?
 a Network Security Group (NSG).
 an Azure Active Directory (Azure AD) role.
 an Azure Active Directory group.
 an Azure key vault.



Ans - a Network Security Group (NSG).

------

Azure Germany can be used by legal residents of Germany only.
 No change is needed.
 Only enterprises that are registered in Germany.
 Only enterprises that purchase their azure licenses from a partner based in Germany.
 Any user or enterprise that requires its data to reside in Germany.




Ans - Any user or enterprise that requires its data to reside in Germany.

------

Your Azure environment contains multiple Azure virtual machines. You need to ensure that a virtual machine named VM1 is accessible from the Internet over HTTP. Solution. You modify a Network Security Group (NSG). Does this meet the goal?
 Yes.
 No.


Ans - Yes


------

You need to ensure that when Azure Active Directory (Azure AD) users connect to Azure AD from the Internet by using an anonymous IP address, the users are prompted automatically to change their password. Which Azure service should you use?
 Azure AD Connect Health.
 Azure AD Privileged Identity Management.
 Azure Advanced Threat Protection (ATP).
 Azure AD Identity Protection.



Ans - Azure AD Identity Protection.
[pending tasks - search for these 4 things]

------

To what should an application connect to retrieve security tokens?
 An Azure Storage account.
 Azure Active Directory (Azure AD).
 A certificate store.
 An Azure key vault.



Ans - Azure Active Directory (Azure AD).
[pending tasks - search for these 4 things]

------

Which Azure service should you use to store certificates?
 Azure Security Center.
 An Azure Storage account.
 Azure Key Vault.
 Azure Information Protection.




Ans - Azure Key Vault.
[pending tasks - search for these 4 things]]

------

You have a resource group named RG1. You plan to create virtual networks and app services in RG1. You need to prevent the creation of virtual machines only in RG1. What should you use?
 A lock.
 An Azure role.
 A tag.
 An Azure policy.




Ans - An Azure policy.

----------

