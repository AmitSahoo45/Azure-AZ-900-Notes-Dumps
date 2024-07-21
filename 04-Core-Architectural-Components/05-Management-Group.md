# Management Groups in Azure

## Hierarchy
- **Resources** belong to **resource groups**
- **Resource groups** belong to **subscriptions**
- **Subscriptions** can be organized into **management groups**

## Definition
- Management groups are optional and allow for organizing one or more subscriptions
- Facilitate management of subscriptions as a group

## Structure
- Management groups can contain multiple subscriptions
- Groups can also belong to other groups, forming a hierarchy
- At the top of the hierarchy is the root management group

## Example Structure
- Hypothetical company with four subscriptions:
  - **Dev Test Subscription**: Belongs to the marketing team
  - **Two Enterprise Agreement Subscriptions**: Belong to the IT team
  - **Pay as You Go Subscription**: Belongs to the application team
- Subscriptions are organized into management groups
- Management groups can be nested within other groups

## Purpose and Benefits
- Centralized control over multiple subscriptions
- Allows different administrators to manage specific subscriptions while enforcing overall policies

## Policies and Blueprints
- **Azure Policy**: Enforce rules and effects over resources
- **Blueprints**: Package of resource groups, ARM templates, policies, etc.
- Policies and blueprints can be assigned at the management group level to manage subscriptions effectively

## Security and Management
- Enhances security by enforcing consistent policies across multiple subscriptions
- Provides a structured way to manage large organizations with multiple subscriptions and varied administrative needs

## Key Points
- Management groups provide an organized, hierarchical structure for managing subscriptions
- Enable centralized policy enforcement and security management
- Facilitate easier administration of subscriptions by grouping and nesting them within management groups