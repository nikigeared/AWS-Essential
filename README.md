# AWS-Essentials

PROJECT 1:  
Deploying a web server in Windows instance  
Task 1:Create a windows instance using AMI :Windows 2012 R2 base  
Task 2:Launch the Windows instance using RDP  
Task 3:Install IIS web server using Powershell ISE  
Note:Simply copy the command below and paste in the powershell ISE to install the IIS web server.  
!!!!Powershell is case sensitive.  
Install-WindowsFeature -name Web-Server -IncludeManagementTools  
Task 4:Verify successful installation of IIS Web Server  
Note :You should be able to see the Internet Information Services Web page when you paste the public IP  
into the browser.  


PROJECT 2:  
Deploying a web server in Windows instance  
Task 1:Create a windows instance using AMI :Ubuntu Server 18.04 LTS (HVM)  
Task 2:Download and install MobaXterm Portable Edition  
Task 2:Launch the Ubuntu instance using SSH  
Note:Username is ubuntu  
Task 3:Install ngnix web server using bash  
Note:Simply copy the command below and paste in the bash to install the ngnix web server.  
sudo apt-get -y update  
sudo apt-get -y install nginx  
Task 4:Verify successful installation of ngnix  
Note :You should be able to see the Welcome to ngnix Web page when you paste the public IP into the  
browser.  

Project 3
Step1:Create two linux instances,Use the first free linux AMI  
Step2:Launch both instances using Mobaxterm  
Step4:Host html login webpage on both servers  
NOTE:Make change in the label of the second sever html configuration  
HTML code for login page:  
Step5:Check if the application is deployed on both servers by copy pasting the public ip of the servers into  
the browser.  
Step6:Create a application Load balancer with the above two instances as targets  
Step7:Check the functioning of ELB  

Ref:Letus Upgrade  
    Vinolin Jermiah  
