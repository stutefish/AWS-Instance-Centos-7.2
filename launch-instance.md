# Launching a new CentOS 7.x instance
Creates a free tier CentOS 7 instance for you to start playing with. 
### Prerequisites
* AWS Account
### Procedure
1. Log into your AWS Account
2. Launch the AWS console 
3. Select **Services > EC2**
4. In the EC2 Dashboard, select **Instances**
5. Select **Launch Instance**
6. Select **AWS Marketplace**
7. Search "centos" 
8. Select **CentOS 7 (x86_64) - with Updates HVM**  
     *This should be marked as "Free tier eligible"  
     Sold by Centos.org  
     $0.00/hr for software + AWS usage fees  
     Linux/Unix, CentOS 7 | 64-bit Amazon Machine Image (AMI) | Updated: 2/25/16*  
9. Select **t2.micro**  
     *This should be marked "Free tier eligible"*
10. Select **Review and Launch** *skips to EC2 Launch step 7*
11. Select **Next** *if prompted for SSD boot*
12. Select **Launch**
13. Set up your keypair *if necessary* and select **Launch Instance**
14. Select **View Instances**
---
That's it! Refer to other docs in this repo for more information about this instance. 
