# cloud_DevOps
Deployment of trading app

# Introduction  
Every application must be deployed in order to make it accessible to users. To understand how to deploy an application, trading app is deployed. This documentation will give a clear view of how this deployment is done.  

Describe your project at a high level (microserver, psql, java)  
  
# Docker Architecture Diagram  


 Two docker files  
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
eyJoaXN0b3J5IjpbMTE2ODU5NjY1MSwtMzc5OTE4MTQ3XX0=
-->