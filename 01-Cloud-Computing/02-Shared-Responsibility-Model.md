# Notes on Shared Responsibility Model

## Overview of Shared Responsibility Model

- The shared responsibility model defines the division of responsibilities between Microsoft (or any cloud provider) and the customer for various aspects, including security.

### On-Premises Model:
- **Customer Responsibility:**
  - Physical security (locking doors, server room security).
  - Network security.
  - Computer security and operating system patches.
  - Application settings, authentication, user accounts.
  - Servers and devices connecting to applications.

### Cloud Models:

#### Infrastructure as a Service (IaaS):
- **Microsoft Responsibility:**
  - Physical security (building security, fences, barbed wire, thumbprint readers).
  - Network security to prevent physical hacking.
- **Customer Responsibility:**
  - Operating system updates (Windows/Linux).
  - Firewall settings.
  - Application settings.
  - Users, devices, data, and applications.

#### Platform as a Service (PaaS):
- **Microsoft Responsibility:**
  - Physical security.
  - Operating system patches.
- **Shared Responsibility:**
  - Network settings.
  - Firewall settings.
  - Authentication.
  - Some application settings.
- **Customer Responsibility:**
  - Users, user IDs, and passwords.
  - Devices connecting to the application.
  - Data and applications.

#### Software as a Service (SaaS):
- **Microsoft Responsibility:**
  - Operating system.
  - Network and firewall settings.
  - Application settings.
  - The application itself.
- **Shared Responsibility:**
  - Authentication (allowing people onto the service).
- **Customer Responsibility:**
  - Keeping user accounts safe.
  - Devices connecting to the network.
  - Data security.

### Abstraction Levels:
- **IaaS (Virtual Machine):**
  - Customer has significant responsibilities.
  - Trust Microsoft for physical aspects.
- **PaaS (App Service):**
  - More responsibilities shared with Microsoft.
  - Less customer burden compared to IaaS.
- **SaaS (e.g., Office 365):**
  - Microsoft takes over most responsibilities.
  - Customer responsible for user accounts, devices, and data.

### Visual Diagram Representation:
- **On-Premises Model:** 
  - All responsibilities are customer-owned (blue).
- **IaaS Model:**
  - Mixed responsibilities, varies by service type.
- **PaaS Model:**
  - Shared responsibilities, some customer-only tasks.
- **SaaS Model:**
  - Majority of responsibilities handled by Microsoft.
  - Minimal customer responsibilities.

### Importance:
- Understanding the shared responsibility model is crucial for security and control.
- The model varies by service type and abstraction level.

---

These notes summarize the key points of the shared responsibility model, highlighting the division of responsibilities between Microsoft Azure and the customer across different cloud service models (IaaS, PaaS, SaaS).