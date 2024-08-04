# Azure Subscriptions

## Hierarchy
- **Resources** belong to **resource groups**
- **Resource groups** belong to **subscriptions**

## Definition
- A subscription is a billing unit within Azure
- Always associated with a payment method (e.g., credit card, Microsoft billing account)

## User Roles and Associations
- Users can be associated with multiple subscriptions
- Different roles within subscriptions: administrator, low-level user, etc.

## Types of Subscriptions
### Free Plan
- $200 credits for the first 30 days
- Free services for 12 months
- One-time use only

### Pay As You Go
- Ideal for small businesses or individuals
- Billed monthly based on resource usage
- Charges auto-deducted from credit card

### Enterprise and Service Agreements
- Various business relationships with Microsoft or service partners
- Includes enterprise agreements, MSDN subscriptions, business startup plans, and student plans

## Multiple Subscriptions
- Common for large organizations to have multiple subscriptions
- Used to separate different parts of the business that don't need to interact
  - Example: Separate subscriptions for sales, IT operations, and marketing
- Can also be used by business geography
  - Example: North America business vs. Europe business

### Example Use Case
- Company with three Azure subscriptions
- Different services and resources consumed under each subscription
- Helps in separating billing and managing security

## Security and Management
- Multiple subscriptions can provide a hard line for security reasons
  - Example: Prevent marketing team from accessing finance subscription
- Easier to manage access at the subscription level
- Not mandatory to have multiple subscriptions; a large organization can run on a single subscription
  - Utilize role-based access control (RBAC) to manage user permissions and access

## Key Points
- Subscriptions are essential for billing and resource management in Azure
- Users can have varied roles and multiple subscriptions
- Different subscription plans cater to various needs (free, pay as you go, enterprise)
- Subscriptions help in organizing and securing resources, but effective security can also be managed within a single subscription using RBAC