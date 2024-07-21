# Availability Zones in Azure

## Definition
- Data centers or sets of data centers that are physically separate within each region
- Can be a few miles or kilometers apart
- High-speed connections (around 5 milliseconds) between data centers

## Characteristics
- Each availability zone has its own power, cooling, and internet connections
- Infrastructure is independent, ensuring no reliance on each other

## Regional Support
- Not every region supports availability zones
  - Example: Canada Central supports availability zones, but Canada East does not
- Microsoft is gradually converting legacy regions to support availability zones
- Customers need to verify if their required regions support availability zones for deployment

## Global Distribution
- Many regions now support availability zones
  - Americas: Brazil, Canada, six US regions, US government region in Virginia
  - Europe: Various regions including Poland (coming soon)
  - Middle East, South Africa, and Asia Pacific regions

## Service Support
- Not every Azure service supports availability zones
- Types of services:
  - **Zonal Services**: Customer chooses a specific availability zone for deployment
  - **Zone-Redundant Services**: Automatically deployed across multiple availability zones
  - **Always Available Services**: Global services not tied to any specific region

### Zonal Services
- Example: Virtual Machines
  - Customers can deploy VMs to specific availability zones within a region (e.g., Canada Central)
  - Ensures redundancy; if one zone fails, another continues to operate

### Zone-Redundant Services
- Automatically deployed across multiple zones without customer intervention
- Examples: Azure Cosmos DB, Azure SQL Database

### Always Available Services (Non-Regional Services)
- Operate globally, not specific to any region
- Examples:
  - **Azure Portal**: A global service
  - **Active Directory**
  - **Azure Front Door**: Profiles for applications without regional deployment
  - Flexible services: Azure Application Gateway, Azure Load Balancer
    - Can be deployed manually into zones or as zone-redundant

## Key Points
- Availability zones ensure high availability and redundancy
- Customers need to choose the appropriate deployment method based on their redundancy needs
- Azure's infrastructure is designed to minimize downtime and ensure continuous operation across its services and regions