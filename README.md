# Cloud Infrastructure

## Objective

To design and implement a secure, scalable private cloud infrastructure that centralizes application hosting, optimizes resource management, and enhances data security and compliance through the integration of AWS and FileCloud technologies.

### Skills Learned

- Cloud Infrastructure Design
- Virtualization and Resource Optimization 
- Security and Compliance Implementation
- Network Configuration and Management

### Tools Used

- Amazon Web Services (AWS) – For building and managing the private cloud infrastructure, including virtual machines, networking, and load balancing.
- FileCloud – Used for secure file sharing, storage, and management within the private cloud environment.
- Virtual Machines (EC2 instances) – For hosting internal applications and services in an isolated, scalable environment.
- Load Balancers (AWS Elastic Load Balancing) – To distribute traffic efficiently across multiple compute resources.
- Network Configuration Tools (Subnets, Security Groups) – For setting up network segments, firewalls, and secure communication channels.

## Steps

Provisioned AWS Resources:
 - Launched an EC2 instance using a FileCloud Amazon Machine Image (AMI) from the AWS Marketplace.
 - Selected an appropriate instance type (t3.medium) to balance performance and cost.  

Configured Network and Security Settings:
 - Set up a Virtual Private Cloud (VPC) with necessary subnets.
 - Configured security groups to allow inbound traffic on required ports (80 for HTTP and 443 for HTTPS). 

Installed and Initialized FileCloud:
 - Accessed the FileCloud installation page via the EC2 instance's public DNS to perform system checks.
 - Logged into the FileCloud admin portal using default credentials and updated the admin password.  

Integrated AWS Storage Solutions:
 - Configured Amazon S3 as the primary storage backend for FileCloud to leverage scalable and durable storage.  

Enhanced Security and Compliance:
 - Implemented encryption for data at rest using AWS Key Management Service (KMS).
 - Set up access controls and firewall rules to restrict unauthorized access.
 - Ensured compliance with relevant data protection regulations by configuring appropriate policies. 