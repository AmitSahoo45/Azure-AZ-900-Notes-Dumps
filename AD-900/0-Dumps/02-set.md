1. An Administrator needs to view the list of planned maintenance events that could potentially affect the availability of the resources hosted in an Azure subscription. Which of the following blade in the Azure portal should the administrator consider for this requirement?
 Resource Groups.
 Azure Active Directory.
 Azure Advisor.
 Help + Support.


Ans - Help + Support.


----

2. Your team needs to have an integrated solution in place that can be used for the deployment of code. Which of the following service can be used for this purpose?
 Azure Advisor.
 Azure Cognitive Services.
 Azure Application Insights.
 Azure DevOps.

Ans - Azure DevOps.


----

3. A team currently has several computers in their on-premise environment that runs on Windows 10. They need to share files by enabling mapped drives from the computers. Which of the following would be an ideal storage solution for this requirement?
 Using the Azure storage - BLOB service.
 Using the Azure storage - File service.
 Using the Azure storage - Queue service.
 Using the Azure storage - Table service.


Ans - Using the Azure storage - File service.


----

4. A company wants to have a data store hosted in Azure. Below are the key requirements for the data store: The data store must be able to store JSON documents. The data store must be able to handle data writes from multiple regions. Which of the following would be the ideal data store for this requirement?
 Azure SQL Database.
 Azure Cosmos DB.
 Azure Redis Cache.
 Azure SQL data warehouse.


Ans - Azure Cosmos DB.

-----

5. A team is planning on deploying Azure Virtual Machines to a resource group named demogroup. The group has been created in the US Central region. Do the virtual machines deployed to the resource group also need to be deployed to the US Central region only?
 Yes.
 No.

ANs - No

Just give it a read.

----
6. A team is planning on assigning tags to a resource group. Would the tag be inherited by resources in the resource group?
 Yes.
 No.



Ans - No

explanation: In Azure, when you assign tags to a resource group, those tags are not automatically inherited by the resources within that resource group. Each resource must be tagged individually if you want them to have the same tags as the resource group.

7. A set of IAM permissions have been assigned to a resource group. Would the resources in the resource group automatically inherit the IAM permissions assigned to the resource group?
 Yes.
 No



Ans - Yes

explanation: In Azure, when you assign Identity and Access Management (IAM) permissions to a resource group, those permissions are automatically inherited by all the resources within that resource group. This is because Azure uses a hierarchical structure for resource management, and permissions assigned at a higher level (like a resource group) are propagated down to the resources contained within it. 



----

8. Your team is planning on using the Azure Advisor tool. Would the Azure Advisor tool give recommendations on how to improve the security for Azure Active Directory?
 Yes.
 No.


Answer: No

Explanation:
Azure Advisor primarily provides recommendations on how to optimize resources for cost, performance, availability, and operational excellence within Azure. While it offers security recommendations, these are typically focused on the resources within your Azure subscription, such as virtual machines, storage accounts, and databases.

----

9. Your company has just setup an Azure account and Azure Active Directory. They need to ensure that when users connect to Azure AD from the Internet from an Anonymous IP address, they are prompted to change their password automatically. Which of the following Azure service can help them achieve this requirement?
 Azure AD Connect.
 Azure AD Identity Protection.
 Azure AD Privileged Identity Management.
 Azure Advanced Threat Protection.



Ans - Azure AD Identity Protection.

-----

10. A company is planning on creating several virtual machines that will be used to host web and database servers. You need to limit the type of connections from the web and database servers. Which of the following can be used to fulfil this requirement?
 Network Security Groups.
 Azure AD Identity Protection.
 Azure VPN.
 Azure Route tables.




Ans - Network Security Groups.

-----
Which of the following can be used to allow an organization to manage the compliance of resources across multiple subscriptions?
 Resource Groups.
 Management Groups.
 Azure Policies.
 Azure Resource Manager templates.

Ans - Azure Policies.
Explanation:
Azure Policies provide a way to enforce rules and compliance requirements across all your resources, making it possible to manage compliance across multiple subscriptions effectively.


To answer such questions effectively, it's important to understand the basic principles of Azure's service level agreements (SLAs) and how different strategies can impact service availability and reliability. Here's how you can approach each question:

### 1. SLA for Paid Azure Services

**Question:**
Would they be guaranteed a service level agreement of at least 99.9% for paid Azure services?

**Answer: Yes**

**Explanation:**
- **Azure SLAs:** Most paid Azure services come with a service level agreement (SLA) of at least 99.9%. For example, virtual machines with premium disks typically have a 99.9% or higher SLA.
- **Baseline SLAs:** Ensure you check the specific SLA for each service, as they can vary.

### 2. Increasing SLA by Deploying Across Multiple Regions

**Question:**
Could the company increase the SLA for their resources by deploying resources across multiple regions?

**Answer: Yes**

**Explanation:**
- **Multi-Region Deployment:** By deploying resources across multiple Azure regions, a company can enhance redundancy and fault tolerance, thereby increasing the overall availability and reliability of their services.
- **Higher Availability:** This approach helps mitigate regional failures, as resources in one region can take over if another region experiences an outage.

### 3. Increasing SLA by Purchasing Multiple Subscriptions

**Question:**
Could the company increase the SLA for their resources by purchasing multiple subscriptions?

**Answer: No**

**Explanation:**
- **Subscriptions:** Purchasing multiple subscriptions does not inherently increase the SLA of individual resources. SLAs are tied to the specific services and configurations, not the number of subscriptions.
- **Redundancy and Resilience:** Instead, focus on strategies like deploying resources across multiple regions or using services designed for high availability.

### Summary of Approach:

1. **Understand SLAs:** Familiarize yourself with the SLAs provided for each Azure service.
2. **Redundancy and Resilience:** Recognize that deploying resources across multiple regions can enhance availability.
3. **Subscriptions vs. Regions:** Understand that multiple subscriptions do not affect SLAs; instead, resource deployment and configuration do.

### Tips for Answering:
- Focus on the technical aspects and capabilities of Azure services.
- Consider how deployment strategies affect availability and reliability.
- Remember that SLAs are specific to services, not to the number of subscriptions.

By understanding these principles, you can answer similar questions confidently and accurately.


-----

You plan to migrate a web application to Azure. The web application is accessed by external users. You need to recommend a cloud deployment solution to minimize the amount of administrative effort used to manage the web application. What should you include in the recommendation?
 Software as a Service (SaaS).
 Platform as a Service (PaaS).
 Infrastructure as a Service (laaS).
 Database as a Service (DaaS).

Ans - Platform as a Service (PaaS). 

Explanation:
- **Platform as a Service (PaaS):** PaaS solutions abstract the underlying infrastructure, allowing developers to focus on building and deploying applications without managing the infrastructure. This minimizes administrative effort and simplifies application management.
- **Web Applications:** PaaS offerings like Azure App Service are ideal for hosting web applications, providing scalability, security, and ease of management.
- **External Users:** PaaS solutions can be accessed by external users, making them suitable for public-facing applications.
- **Administrative Effort:** By leveraging PaaS, you can reduce the administrative overhead associated with managing infrastructure, enabling your team to focus on application development and innovation.

-----

You plan to migrate several servers from an on-premises network to Azure. What is an advantage of using a public cloud service for the servers over an on-premises network?
 The public cloud is owned by the public, NOT a private corporation.
 The public cloud is a crowd-sourcing solution that provides corporations with the ability to enhance the cloud.
 All public cloud resources can be freely accessed by every member of the public.
 The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud.



Ans - The public cloud is a shared entity whereby multiple corporations each use a portion of the resources in the cloud.


---- 
You have 1,000 virtual machines hosted on the Hyper-V hosts in a data center. You plan to migrate all the virtual machines to an Azure pay-as-you-go subscription. You need to identify which expenditure model to use for the planned Azure solution. Which expenditure model should you identify?
 Operational.
 Elastic.
 Capital.
 Scalable.


Ans - Operational.