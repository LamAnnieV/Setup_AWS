# Setup an Amazon Virtual Cloud

September 28, 2023

By:  Annie V Lam - Kura Labs

## A VPC allow yu to control network access to and from your AWS Infrastructure

### Create your VPC
1.  Navigate to https://us-east-1.console.aws.amazon.com/vpc/home?region=us-east-1#Home:
2.  Click "VPCs"
3.  Click "Actions"
4.  Click "Create VPC"
5.  Click the "Name tag - optional" field and name your VPC (e.g. "kura-vpc")
6.  Click the "IPv4 CIDR" field and enter "172.18.0.0/16"
7.  Click "Create VPC"

### Verify your VPC has been created
1.  Click "Your VPCs" on the left panel 
2.  You should see your VPC
