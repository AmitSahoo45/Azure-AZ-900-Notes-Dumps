# Azure Architecture and Services (35-40% of overall score)

## Introduction
- Second major objective of the course: Describe Azure Architecture and Services
- Focus shifts from generalized cloud computing concepts to Azure-specific architecture and services

## Core Architectural Components
- Regions and region pairs
- Availability zones
- Data centers
- Key for creating solutions in Azure

## Topics to be Covered
- Compute
- Networking
- Storage
- Azure Active Directory
- Security and identity-related services

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