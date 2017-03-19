# Modifying Security Groups
The AWS Marketplace CentOS AMI you started with creates a security group that allows public access to Port 22 (SSH) only. If you don't have any other security groups defined, you will need to change this to allow Public access to your webserver.
---
### Prerequisites
* An AWS account. 
* Console access. 
---
### Create a Webserver Security Group
1. Log into your AWS account and launch the Console. 
2. Open the EC2 Service dashboard, and select **Security Groups**
3. Select **Create Security Group**
4. Select the **Inbound** tab for this group, and select **Edit**
5. Select **Add Rule**, and choose **HTTP**. 
6. Select **Save**
### Add the Webserver Group to your Instance
1. From the EC2 Service dashboard, select **Instances**
2. Right-click/Context-click on your Instance, and select **Networking > Change Security Groups**
3. Select the "Webserver" Group, and select **Assign Security Groups**
---
Your Instance should now be accessible from the Internet over Port 80. 
---
### Bonus
Later on, you may want to update your "Webserver" group to include SSH (port 22) access over the Internet. That way you can assign a single group at launch time, that covers both requirements (SSH for administration, HTTP for the website).
