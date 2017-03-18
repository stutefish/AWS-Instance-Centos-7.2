# Modifying Security Groups
The AWS Marketplace CentOS AMI you started with creates a security group that allows public access to Port 22 (SSH) only. If you don't have any other security groups defined, you will need to change this.
---
### Prerequisites
* An AWS account. 
* Console access. 
---
### Procedure
1. Log into your AWS account and launch the Console. 
2. Open the EC2 Service dashboard, and select *Security Groups*
3. Select the group "CentOS 7 -x86_64- - with Updates HVM-1602-AutogenByAWSMP-" *
4. Select the *Inbound* tab for this group, and select *Edit*
5. Select *Add Rule*, and choose *HTTP*. 
6. Select *Save*
---
Your Instances should now be accessible from the Internet over Port 80. 
