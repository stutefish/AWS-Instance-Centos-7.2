# Installing and configuring Chef 
---
### Goals
A CentOS 7.2 Instance suitable for registering as an AMI, with Chef Server and Client already installed. 
### Prerequisites
* A running CentOS 7.2 Instance
* `ssh` access to the Instance
* `sudo` or `root` permissions on the Instance
---
### Procedure
1. Log into the running Instance
2. Install the Chef DK  
   `curl https://omnitruck.chef.io/install.sh | sudo bash -s -- -P chefdk -c stable -v 0.18.30`
3. Setup the working directory  
   `mkdir ~/chef-repo`  
   `cd ~/chef-repo`
 4. **YOU ARE HERE**
 
