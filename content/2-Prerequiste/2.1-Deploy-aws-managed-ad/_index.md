---
title : "Deploy AWS Managed Directory Service"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---
### Deploy AWS Managed Directory Service (AWS Managed Microsoft AD)
1. AWS Management Console => Search for Directory Service
2. At AWS Directory Service management console => Set up directory
  ![setup directory](/images/setup-ad-1.jpg)
3. Choose AWS Managed Microsoft AD => Next
   ![setup directory](/images/setup-ad-2.jpg)
4. Depends on your business needs. Manually choose the right Directory Service. For this lab purpose, choose Standard Edition
5. Then, fill in all of required information: Fully Qualified Domain Name (FQDN), NetBios Name, Description (optional), password
   - By default, the AWS Managed AD account is Admin (case sensitive)
   - Do not worry about the price, the lab last long 2~4hrs. Do not cost too much. However, remember to delete the resources included this Directory Service after completed the lab
  ![setup directory](/images/setup-ad-3.jpg)
  ![setup directory](/images/setup-ad-3-a.jpg)
6. Then click Next
7. Choose the right VPC and Subnet. Remember, at least 2 subnet in 2 different availability zone (az).
8. Must be private subnet for security best practices. Then click NEXT
  ![setup directory](/images/setup-ad-4.jpg)
9. Double check all of the required information => Create Directory
  ![setup directory](/images/setup-ad-5.jpg)
10. The directory creation might take a bit long, roundly 40 minutes. 
11. After finished, we will see our directory has been created
  ![setup directory](/images/setup-ad-6.jpg)
12. We are done for setting up AWS Managed AD 
