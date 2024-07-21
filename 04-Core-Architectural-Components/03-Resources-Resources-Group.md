# Azure Resources and Resource Groups

## Hierarchy of Resources in Azure
1. **Resources**: Basic units, actual Azure services (e.g., VMs, storage accounts, databases)
2. **Resource Groups**: Containers for organizing resources
3. **Subscriptions**: Associated with resources for billing
4. **Management Groups**: High-level organization of subscriptions

## Azure Resources
### Definition
- Represents any active or instantiated Azure service
- Examples: Virtual machines, storage accounts, databases

### Creation Methods
- Azure Portal
- Command line (including PowerShell)
- ARM templates
- Bicep

### Naming
- Generally, all resources are named
- Recommended to use naming conventions for identification (e.g., owner, purpose, project)
- Naming uniqueness may vary (across Azure, within resource groups, etc.)

### Location
- Resources must be deployed in a specific Azure region
- Region selection affects where the resource runs

### Costs
- Resources incur costs based on subscription
- Free plan or credits may offset some costs initially

### Subscription
- Each resource is associated with one subscription for billing purposes

## Resource Groups
### Definition
- Container structure for organizing resources
- Groups resources that are related or managed together

### Characteristics
- Requires association with a region upon creation
- Can contain resources from different regions
- Resources in a group should have some logical connection (created, managed, or deleted together)

### Permissions
- Permissions (read, write, delete, create) can be assigned at the resource group level
- No security boundary: resources within different groups can interact unless other security measures are applied

### Best Practices
- Avoid grouping unrelated resources
- Use resource groups for organized management and easier administration

## Key Points
- **Resources**: Basic Azure services, named and region-specific
- **Resource Groups**: Organizational containers, region-associated, logical grouping recommended
- Ensure proper naming conventions and logical grouping for efficient resource management and cost tracking.