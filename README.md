# Configure Public Access Multi-AZ MySQL-based RDS

In this project, I successfully configured a public access multi-AZ MySQL-based RDS. The objective was to establish a robust and scalable MySQL database infrastructure with public access. The following steps were taken during the implementation:

## Project Overview

The project aimed to configure a Multi-AZ MySQL-based RDS with public accessibility. Key features of the configuration include:

- **MySQL RDS Creation:** Created a t2.micro MySQL instance with version 5.6.

- **VPC Setup:** Created or utilized an existing VPC with a minimum of two public subnets.

- **Multi-AZ and Read Replica:** Implemented Multi-AZ and read replica features to enhance availability and performance.

- **Log Monitoring:** Enabled all four logs for comprehensive monitoring via CloudWatch.

- **Public Subnet Launch:** Launched the RDS instance in a public subnet group to enable internet access.

- **Verification:** Verified the setup using SQL Workbench.

## Technology Stack

- **AWS Services:**
  - Amazon RDS (MySQL)
  - Amazon VPC
  - Amazon CloudWatch

## Deployment Process

The deployment process focused on meticulous configuration steps to ensure optimal performance, scalability, and security of the MySQL-based RDS.

## Features

- **Multi-AZ Configuration:** Ensured high availability through Multi-AZ deployment.

- **Read Replica:** Implemented read replica features for improved performance.

- **Log Monitoring:** Enabled all four logs to facilitate comprehensive monitoring via CloudWatch.

- **Public Subnet Launch:** Launched the RDS instance in a public subnet group, enabling internet access.

## Verification

The setup was verified using SQL Workbench, confirming the successful configuration and accessibility of the MySQL-based RDS.

## Conclusion

This project was executed with meticulous attention to detail, resulting in a robust and scalable MySQL-based RDS with public accessibility. The configured features, including Multi-AZ deployment and read replicas, contribute to optimal performance, scalability, and security of the database infrastructure.

