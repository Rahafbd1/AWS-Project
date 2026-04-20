Enterprise AWS Infrastructure - Project Two
Overview
This project simulates a real-world enterprise environment, designing and deploying a secure, highly available, and scalable infrastructure on AWS using Infrastructure as Code (CloudFormation).

Project Architecture
The infrastructure is organized with the following naming conventions to ensure resource traceability:

VPC: rahaf-project

Subnets: Public (rahaf-public1, rahaf-public2) and Private (rahaf-private1, rahaf-private2).

Compute Layer: EC2 instances deployed in private subnets for enhanced security.

Load Balancer: Application Load Balancer (rahaf-alb) to distribute incoming traffic.

Monitoring: CloudWatch Alarm (rahaf-alarm) configured to track CPU utilization.

Security: IAM Role (rahaf-ec2-role) implemented with the principle of least privilege.
