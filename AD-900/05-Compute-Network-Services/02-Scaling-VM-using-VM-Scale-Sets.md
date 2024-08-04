# Scaling Virtual Machines in Azure

## Scaling Methods
1. **Scaling Up**
   - Increase the size of the VM instance
   - Example: Move from a 4 CPU VM to an 8 CPU VM
   - Can scale up to 120 CPUs in some instance families
   - Limited to maximum instance size

2. **Scaling Out**
   - Increase the quantity of virtual machines
   - Distribute the workload across multiple VMs
   - Preferred method due to flexibility and fewer limitations

## Virtual Machine Scale Sets (VMSS)
- **Definition**: Predefined groups of virtual machines that can scale in or out based on demand
- **Key Features**:
  - Add or reduce VMs based on predefined rules
  - Automatically adjusts the number of VMs to match traffic demands
  - Supports various scaling triggers, including CPU utilization, schedules, and queue lengths

### Scaling Rules
1. **Demand-Based Scaling**:
   - Monitor CPU utilization as a proxy for traffic load
   - Add VMs when CPU usage exceeds a threshold
   - Reduce VMs when CPU usage drops

2. **Schedule-Based Scaling**:
   - Define schedules for adding/removing VMs
   - Example: 5 VMs from 8 AM to 8 PM, 2 VMs from 8 PM to 8 AM

3. **Other Triggers**:
   - Queue lengths
   - Message queues
   - Custom metrics

## Benefits of Scale Sets
- **Elasticity**:
  - Meets the demand requirements of cloud computing
  - Can dynamically adjust the number of VMs based on real-time needs
- **Cost Efficiency**:
  - Save money by reducing the number of VMs during low demand periods
  - Only pay for the resources you need at any given time

### Configuration and Limits
- Typically supports up to 100 VMs in a single scale set
- Can be configured to handle up to 1,000 VMs
- For larger needs, multiple scale sets can be created and managed via load balancers
- Subject to subscription-wide limits on the number of machines and storage in a single region

## Load Balancers
- **Role**: Distribute traffic evenly across multiple VMs in a scale set
- Ensures efficient use of resources and balanced workload distribution

## Summary
- **Scaling Up**: Increase the size of a VM, but with a maximum limit
- **Scaling Out**: Increase the number of VMs, providing greater flexibility and scalability
- **VM Scale Sets**: Enable automated scaling based on demand or schedules, ensuring efficient resource use and cost savings

## Next Steps
- Discussion on other methods to run code in the cloud in upcoming videos