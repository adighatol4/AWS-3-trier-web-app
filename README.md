#AWS Three-Tier Architecture Project
This project demonstrates the deployment of a scalable and secure web application using a three-tier architecture on AWS. It utilizes the following components:

Application Load Balancer (ALB): Distributes traffic across EC2 instances in the web tier.
Auto Scaling Group (ASG): Manages the application tier to handle traffic spikes.
Amazon RDS: Provides persistent database storage.
The architecture ensures high availability, fault tolerance, and security by:

Distributing resources across multiple availability zones.
Using private subnets for sensitive data.
Applying Security Groups for traffic control.
The setup adheres to AWS best practices, making it resilient and scalable.
