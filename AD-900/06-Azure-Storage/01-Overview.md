### Lecture Notes on Azure Storage Services

#### Overview
- **Third Pillar of Computer Services: Storage**
  - Storage is a significant objective in exams related to computer services.
  - Focus on Azure Storage Services.

#### Types of Azure Storage
1. **Unmanaged Storage (General Purpose v2 - GPV2)**
   - Also known as Standard Storage.
   - Encompasses various types of data storage:
     - Container Data (Blob Storage)
     - File Storage
     - Queue Storage (not covered in the exam)
     - Table Storage (not covered in the exam)
   - Storage capacity: Up to 5 petabytes (5,000 terabytes or 5 million gigabytes).
   - Cost-efficiency: Pay only for the storage used.
     - Costs approximately 2 cents per gigabyte per month, as low as 1.8 cents for certain access tiers (cool, cold, archive).

2. **Disk Storage (Managed Storage)**
   - Used specifically for virtual machine virtual hard disks.
   - High demand workloads (e.g., databases, high-demand web servers) might need other options due to performance requirements.

3. **File Storage**
   - Standard and premium tiers available.
   - Premium tier offers higher performance with solid state flash disks (SSD).

#### Access Tiers
- **General Purpose (GPV2)**
  - Great for most general storage needs.
  - Might not suffice for high-performance workloads.

- **Data Lake Storage**
  - Good for big data.
  - Exceeds 5 petabytes limit, capable of holding multiple petabytes or even exabytes.
  - Uses a different protocol for data storage.
  - Not recommended unless specific knowledge and requirements are met.

- **Premium Storage**
  - Suitable for high-performance requirements.
  - Types of blobs:
    - Block Blobs
    - Page Blobs
  - Premium storage is focused on blob storage, not multipurpose.
  - Premium tier benefits:
    - Uses solid state flash disks (SSD).
    - Supports more operations per second.
    - Lower latency for quicker data retrieval.
  - More expensive than standard storage (above 2 cents per gigabyte).

- **Premium V2 and Ultra Tiers**
  - **Premium V2**: Offers significantly higher performance than standard premium.
  - **Ultra Tier**: Highest performance, specific hardware, and regional requirements.
  - Typically chosen for very high-performance needs.

#### Key Points to Remember
- **Cost and Performance Balance**: Choose storage type and tier based on workload requirements and budget.
- **Scalability**: Azure storage can scale from gigabytes to exabytes depending on the storage type chosen.
- **Pay-as-You-Go Model**: Only pay for the storage you use, making it cost-effective.

#### Unclear Points and Further Research
- Detailed differences between block blobs and page blobs.
- Specific use cases and configurations for Data Lake storage.
- Regional and hardware requirements for Ultra tier storage.

This summary covers the key aspects of Azure Storage Services discussed in the lecture. Further details may be required for in-depth understanding and practical application, particularly in areas noted for further research.