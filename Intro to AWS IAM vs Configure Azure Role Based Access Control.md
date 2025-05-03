# AWS Intro to IAM / Azure Configure Role-Based Access Control (RBAC)

## AWS: Intro to IAM

### What I did in the lab:
- Used the AWS management console to explore IAM.
- Created IAM groups and attached permissions. 
- Created IAM users, assigned them to groups.
- Logged in as the new users to test and confirm the access based on policies.
- Learned how different users had different access levels based on the group policies I set.

![Lab Results](https://github.com/roopeti/cloudcomputing/blob/main/Image%203.5.2025%20at%2013.34.jpeg?raw=true)

### Core services used
- IAM
- Compute (EC2)
- Storage (S3)
- Database (RDS)


## Azure: Configure Role-Based Access Control

### What I did in the lab: 
- Used Azure Portal to create user accounts and groups.
- Created a group and added users to it. 
- Assigned roles to users or groups using RBAC.
- Verified access by checking the permissions.
- Used Azures (IAM) blades to manage and review role assignments.

I couldn't find where the MSLE grades are saved? So I only have this screenshot that shows I have attempted the lab: 

![Azure Lab attempted](https://github.com/roopeti/cloudcomputing/blob/bc9b08d1f627b4eda377dac991ead4e203106e95/Image%203.5.2025%20at%2013.47.jpeg)

### Services used
- Azure Active Directory
- RBAC
- Compute
- Resource Groups



## Comparison between the two

|Feature|AWS|Azure|
|:------|:--|:----|
|Identity Management|IAM manage users, groups, roles, and policies|Azure AD manages users and groups|
|Access control|Policy-based|Role-based|
|Permissions|Custom policies|Custom roles|
|Experience|AWS management console|Azure Portal|
|Testing access|Login as user|Check access via portal, test user permissions|
|Resource deletion|End lab, resources deleted automatically|Manual clean-up using Cloud Shell (PowerShell)|


# Similarities
- Both provide a centralized IAM.
- Both support grouping users and assigning permissions.
- Both use management portals for config. and verification.
- Created users, groups, and assigned access in both labs.

# Differences
- AWS uses a policy-based model, unlike Azure which uses a role-based model.
- Azure RBAC allows role assignment at multiple levels (resource, group, subscription), AWS IAM works at the resource or account level.
- Azure RBAC is integrated with Azure AD, while AWS IAM is a standalone system.

