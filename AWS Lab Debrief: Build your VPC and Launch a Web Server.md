# Build Your VPC and Launch a Web Server

## What I did in the lab

### Networking
- I created a new Virtual Private Cloud (VPC).
- Then I set up two subnets withing the VPC, one was public and one private (in the same AZ).
- After, I attached an internet gateway to the VPC. The gateway allows communication between resources in the public subnet and the internet.
- I configured the route tables making it so that the public subnet's route table directed traffic to the internet gateway, while the private subnet's table didn't.

### Security
- Used IAM for secure access to the console.
- Created a security group: "Web Security Group", to act as a firewall for the EC2 instance, enabling web access.

### Compute
- Launched an EC2 instance withing the newly created VPC.
- Associated the instance with the security group.
- Assigned a public IP address making it accessible from the internet.
- Installed and started a web server on the EC2 instance as a test.


- Then I accessed the web page via a browser to test that it was running and accessible.


![lab](https://github.com/user-attachments/assets/0babcfdf-0f6a-4fe9-97b3-6e8ad3685500)
