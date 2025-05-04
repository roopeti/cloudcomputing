# AWS lab Scale & Load Balance your Architecture

## What I did in the lab
- I built a scalable web architecture using elastic load balancing (ELB), and auto scaling.
- First, I selected an EC2 instance and created an AMI from it. This is a template for launching new instances in the Auto Scaling group.
- Then I set up an application load balancer (ALB), which distributes incoming traffic across multiple instances.
- Created a template from the previously created AMI, and defined and Auto Scaling group. It was configured so that it launches a new EC2 instance within private subnets as needed, based on health checks.
- After I configured CouldWatch alarms to monitor based on CPU utilization, which would then trigger scaling actions to maintain performance.

### Services used
- IAM
- Networking (configured VPC, subnets, and security groups)
- Compute (used EC2 for web servers, AMI for templates, Auto Scaling)
- Storage (the AMI and EC2 instance utilized EBS)


  ![image](https://github.com/user-attachments/assets/00ce8262-b43a-4449-bafa-ad3e717a7aa0)
