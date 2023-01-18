---
title : "EC2 Configuration"
date :  "`r Sys.Date()`" 
weight : 3 
chapter : false
pre : " <b> 3. </b> "
---

- This section will guide us how to configure EC2 so that all of EC2 which joined AWS Managed AD can be connected together. 
- Take note that, EC2(s) joined into AWS Managed AD do not mean they can connect to each other
- AWS VPC is extremely strict about security best practices. Hence, need some setup so that all of EC2(s) can communicate to each other