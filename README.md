# cloud_DevOps
Deployment of trading app

# Introduction  
Every application must be deployed in order to make it accessible to users
What project you will deploy and project GitHub URL (your implementation is preferred)  
Describe your project at a high level (microserver, psql, java)  
  
# Docker Architecture Diagram  
- trading_app docker diagram including:  
 - use [draw.io](http://draw.io/) and AWS icons (it's already in [draw.io](http://draw.io/) library)  
 - images (docker hub and local)  
 - bridge network  
 - containers  
 - label commands  
  
- Two docker files  
  - trading-app  
   - talk about the process (e.g. compile and package jar and run the app)  
  - jrvs-psql  
   - talk about how to create tables (e.g. schema.sql)  
  
# Cloud Architecture Diagram  
- trading app diagram  
  - use [draw.io](http://draw.io/) and aws icons (it's in the [draw.io](http://draw.io/) library)  
  - include ec2, alb, auto scaling, target group, rds  
  - security groups  
  - label all important ports(e.g. ALB HTTP, ec2 tpc:5000, RDS tcp:5432)  
    
# Elastic Beanstalk (TODO)  
# Jenkins CI/CD pipeline (TODO)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY0NTIxOTQ3XX0=
-->