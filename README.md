# Building-Highly-Available-Multi-Tier-Architecture-with-Terraform

This project demonstrates the design and implementation of a production-style, highly available, and secure AWS web application infrastructure using Terraform and Infrastructure as Code (IaC).

It showcases hands-on experience with:

Cloud architecture design

Infrastructure automation

High availability and fault tolerance

AWS networking and security best practices

Scalable application deployment patterns

## Infrastructure as Code (Terraform)

Implemented the entire infrastructure using Terraform, enabling repeatable, version-controlled, and automated deployments while reducing configuration drift and human error.

## Application Load Balancer

Deployed an internet-facing Application Load Balancer in public subnets to provide a highly available and scalable entry point for application traffic and distribute load across EC2 instances.

## High Availability (Multi-AZ Design)

Designed a multi-AZ architecture using two public and two private subnets across different Availability Zones to ensure fault tolerance and service continuity in the event of an AZ failure.

## Virtual Private Cloud (VPC)

Built a custom VPC to gain full control over network segmentation, IP addressing, routing, and security boundaries, following AWS best practices.

Route Tables & Traffic Control

Configured route tables to manage traffic flow between public and private tiers and to the internet, enforcing clear network separation and security boundaries.

## Security Groups (Network Security)

Implemented security groups as stateful firewalls to enforce least privilege access between the Load Balancer, application servers, and database layer, significantly reducing the attack surface.

## Secure Database Layer (RDS)

Deployed an RDS MySQL database in private subnets, ensuring the data layer is fully isolated from the internet and only accessible from the application tier.

## Internet Gateway

Configured an Internet Gateway to enable controlled internet access for public facing resources while keeping backend systems private.

## Final Result

Delivered a secure, scalable, and highly available AWS reference architecture featuring:

Load-balanced EC2 application tier

Isolated database tier

Multi-AZ deployment

Full automation via Terraform
