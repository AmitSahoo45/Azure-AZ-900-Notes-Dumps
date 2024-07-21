# Azure Architecture and Services (35-40% of overall score)

## Regions
### Definition
- Azure divides the globe into over 60 regions
- A region is a set of buildings/data centers combined together

### Naming and Distribution
- Sometimes named after the country; not always
- Some countries have multiple regions; most do not have any

### Region Pairs
- Regions are matched to have a paired region
- Fastest connection for backups and massive data transfers
- Rollouts of Azure updates are staggered between pairs to avoid simultaneous failures

### Infrastructure Map
- Interactive map available at infrastructuremap.microsoft.com
- Highlights Azure regions and their connections
- Key regions in North America, Western Europe, Middle East, India, Asia, and Australia

### North America
- USA: Nine regions with one coming soon (US East 3)
- Canada: Two regions (Canada Central and Canada East)
  - Data residency laws ensure data stored in Canada remains in Canada

### South America
- Brazil: One region (Brazil South) paired with South Central US
  - No data residency in Brazil as backups are in the US

### Middle East and Africa
- Developing regions in Saudi Arabia, Qatar, etc.
- Qatar: First region without a pair, no GRS (geo-redundant storage)
- Africa: Limited presence, primarily in South Africa

## Availability Zones
- Not detailed in the transcript but mentioned as a key component

## Sovereign Regions
### Definition
- Connected to a specific country/government
- Separate from the Azure public cloud
- Requires approval to join
- Follows different privacy and compliance standards

### Types of Sovereign Regions
#### United States
- Public Cloud (Azure Commercial): Basic compliance with DoD Impact Level 2, FedRAMP, HIPAA
- Azure Government: For US state/federal government employees and departments
- Secret Cloud: For intelligence services with higher compliance standards
- Top Secret Cloud: Highest level of compliance, minimal public information

#### China
- Operated by a separate company due to government regulations
- Requires a Chinese presence to use Azure services in China

## Conclusion
- Regions are geographical groupings of data centers
- Region pairs facilitate backups and efficient Azure updates
- Sovereign regions cater to specific governmental and regulatory needs

------------------------------------------
------------------------------------------
------------------------------------------
------------------------------------------

### Azure Regions Overview
- **Definition**: Azure regions are geographical areas that contain one or more datacenters. Each region is paired with another region within the same geography to provide disaster recovery and data residency.
Think of Azure regions as specific locations around the world where Microsoft has data centers.
For example, *"East US"* is a region located in Virginia, USA.

A ***DataCenter*** is a facility housing networked computers and storage systems used to store, process, and distribute large amounts of data. It includes power supplies, cooling systems, backup systems, and security measures to ensure reliable and secure operations.

- **Purpose**: Regions enable users to place resources close to their users, ensuring lower latency, data residency, and compliance.
If you have users in the US and Europe, you can deploy your application in "East US" and "West Europe" regions to ensure low latency and compliance with local data laws.

*Latency* is the time it takes for data to travel from its source to its destination. 

- **High Latency**: Long delays, resulting in slower response times.
- **Low Latency**: Short delays, resulting in faster response times.

### Key Concepts
- **Region Pairs**: Each Azure region is paired with another within the same geography, enabling data replication for disaster recovery. Example: West US is paired with East US. If there’s an outage in "East US", services can failover to "West US".
In the context of Azure, **geography** refers to a large-scale region that contains multiple Azure regions and ensures data residency, sovereignty, and compliance. It usually aligns with political boundaries such as countries or continents.

For example, if there are two Azure regions in India, such as East India and West India, these two regions would be paired together within the same geography (India) for disaster recovery purposes. This pairing ensures that data replication and redundancy stay within the country's boundaries, meeting local data residency and compliance requirements.

> the above is pretty important
-----

**Data Residency** refers to the physical location where data is stored and processed. It ensures that data remains within a specific geographical boundary, often to comply with local regulations and laws regarding data privacy and security. This is crucial for organizations needing to meet legal and compliance requirements related to where their data is housed.

----------------------------

- **Geographies**: These are discrete markets containing two or more regions that preserve data residency and compliance boundaries. Examples include North America, Europe, Asia Pacific, etc. For example, the Europe geography includes regions like "North Europe" (Ireland) and "West Europe" (Netherlands).

-----

- **Availability Zones**: Physically separate locations within an Azure region, each with independent power, cooling, and networking. They provide high availability and fault tolerance.
For instance, "East US" has multiple availability zones, each with separate power and networking to ensure high availability.

----

- **Edge Zones**: Extending Azure regions to edge locations closer to users for low-latency scenarios.

### Benefits of Using Multiple Regions
- **Resiliency and High Availability**: Deploying across multiple regions reduces the risk of service interruptions.
-  If you deploy your app in both "East US" and "West Europe", you ensure that even if one region goes down, your app remains accessible.
- **Disaster Recovery**: Region pairs provide built-in disaster recovery support.
- **Compliance and Data Residency**: Ensuring data is stored and processed within specific geographic boundaries.

### Considerations for Choosing a Region
- **Proximity to Users**: Choose regions close to your users to reduce latency.
- **Service Availability**: Not all Azure services are available in every region. Check the Azure products by region page for service availability.
- **Compliance Requirements**: Ensure the region complies with local laws and regulations.
- **Cost**: Pricing can vary between regions, impacting the overall cost of your services.

### Examples of Azure Regions
- **Americas**: East US, West US, Central US, Brazil South
- **Europe**: North Europe, West Europe, UK South, France Central
- **Asia Pacific**: Southeast Asia, East Asia, Australia East, Japan East
- **Middle East and Africa**: UAE North, South Africa North

### Azure Region Connectivity
- **Global Network**: Azure regions are interconnected through a high-speed global network, enhancing performance and reliability.
- **ExpressRoute**: Provides a private connection between on-premises infrastructure and Azure, bypassing the public internet.

### Exam Tips
- **Understand Region Pairs**: Be familiar with the concept of region pairs and their role in disaster recovery.
- **Know the Key Regions**: Have an idea of some key regions across different geographies.
- **Service Availability**: Recognize that not all services are available in every region and know how to check for service availability.