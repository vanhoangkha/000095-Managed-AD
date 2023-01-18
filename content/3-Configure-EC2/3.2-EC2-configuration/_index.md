---
title : "EC2 Configuration"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 3.2 </b> "
---

**EC2 Configuration**
1. Navigate to the AWS Directory Service management console => choose the created Directory Service => save the DNS Address
    ![ec2-config](/images/ec2-confg-2.jpg)
2. Navigate to the EC2 Management Console => save ALL of the both public and private ip address of ALL EC2
    ![ec2-config](/images/ec2-confg-3.jpg)
3. We will have a temporary notepad file like this  
    ![ec2-config](/images/ec2-confg-4.jpg)
4. Edit your hosts file on ALL EC2. Remember, before edit the host file, you need to grand the permission so the that file can be saved. Host file is located at **C:\Windows\System32\drivers\etc**
    ![ec2-config](/images/ec2-confg-4a.jpg)
    ![ec2-config](/images/ec2-confg-4b.jpg)
5. The hosts file of all EC2 should look something like this
    ![ec2-config](/images/ec2-confg-5.jpg)
6. On ALL EC2. CMD => ipconfig /all to check the ip address. Then, configure the IP address so that matched with the what showed in the command line on EACH EC2. Because of we have already joined into the domain at the creating EC2 step. Then, the DNS will be pre-filled so that matched with our created AWS Managed Directory Service
    ![ec2-config](/images/ec2-confg-6.jpg)
    ![ec2-config](/images/ec2-confg-6a.jpg)
    ![ec2-config](/images/ec2-confg-6b.jpg)
    ![ec2-config](/images/ec2-confg-6c.jpg)
    ![ec2-config](/images/ec2-confg-6d.jpg)
7. At AD-Manager EC2 => Server Management => Add Roles and Features. After chose all the neccessary options => NEXT => Install => it might take 2 minutes 
    ![ec2-config](/images/ec2-confg-7.jpg)
    ![ec2-config](/images/ec2-confg-7a.jpg)
    ![ec2-config](/images/ec2-confg-7b.jpg)
    ![ec2-config](/images/ec2-confg-7c.jpg)
8.  Restart ALL EC2 
9.  After restarted, login again and check ping in every server
