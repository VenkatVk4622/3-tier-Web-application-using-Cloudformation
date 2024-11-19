I have created a Clouformation Template to deploy a 3 Tier web application in AWS Console...
Services Includes-VPC,Subnet,EC2,RDS,Loadbalancer,Internet Gateway & Security Groups

# 3-Tier Web Application Using CloudFormation

This repository contains an AWS CloudFormation template for deploying a three-tier web application.

## Architecture
- **Web Tier**: EC2 instance with an Application Load Balancer.
- **App Tier**: Private EC2 instance running application logic.
- **Data Tier**: RDS MySQL database in a private subnet.

## Prerequisites
- AWS CLI installed and configured.
- An existing key pair in your AWS region.
- Valid AMI IDs for your region.

## Deployment
1. Clone the repository:
   ```bash
   git clone https://github.com/Venkat/3-Tier-Web-Application-CloudFormation.git
