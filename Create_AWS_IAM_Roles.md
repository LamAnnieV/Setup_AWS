# How to Create AWS Identity Access Management (IAM) Role

September 15, 2023

By:  Annie V Lam - Kura Labs

# Purpose
To build and test the URL shortener applicaition using Jenkins and deploy the URL shortener using Elastic Beanstalk.

## Create Elastic Beanstalk Role
1.  Navigate to https://us-east-1.console.aws.amazon.com/iamv2/home?region=us-east-1#/home
2.  Search "IAM"
3.  Click "Roles"
4.  Click "Create role"
5.  Under Trusted entity type Select "AWS Service"
6.  Under Use Case for other AWS services, search "elastic"
7.  Select "Elastic Beanstalk"
8.  Select:  Elastic Beanstalk - Customizable/Next
9.  Next
10. In Role name enter "aws-elasticbeanstalk-service-role"
11.  Click "Create role"
  
## Create EC2 Role
1.  Navigate to https://us-east-1.console.aws.amazon.com/iamv2/home?region=us-east-1#/home
2.  Search "IAM"
3.  Click "Roles"
4.  Click "Create role"
5.  Under Trusted entity type, select "AWS Service"
6.  Under Use Case, select "EC2"
7.  Next
8.  In Permission policies select  "AWSElasticBeanstalkWebTier" & “AWSElasticBeanstalkWorkerTier”
9.  Next
10.  In Role name enter "Elastic-EC2/Create Role"
