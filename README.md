# Highly-Available-Web-Architecture
    An AWS CloudFormation Template For Highly Available Web Architecture

# Description
    This template is used to deploys a VPC, with a pair of public and private subnets spread across two Availability Zones. 
    It deploys an Internet Gateway, with a default route on the public subnets. 
    It deploys a pair of NAT Gateways (one in each AZ) and default routes for them in the private subnets. 
    It also creates an Elastic Load Balancer with Health Check and auto-scaling group with Launch Configure. 
    One Security Group Having Ingress Rule for HTTP and SSH.
