# AWS Elastic Load Balancer (ELB)

A hands-on AWS project demonstrating how to distribute incoming application traffic across multiple EC2 instances using an Application Load Balancer.

## 📌 Project Overview

This project documents the configuration of an AWS Elastic Load Balancer environment, including EC2 instances, security groups, target groups, and load balancer setup.

## 🎯 Objectives

- Understand Elastic Load Balancing in AWS.
- Launch multiple EC2 instances.
- Configure security groups and inbound rules.
- Create and register a target group.
- Configure an Application Load Balancer.
- Verify application access through the load balancer DNS name.
- Clean up AWS resources after testing.

## 🛠️ AWS Services Used

- Amazon EC2
- Elastic Load Balancing (Application Load Balancer)
- Target Groups
- Amazon VPC security groups
- AWS Management Console

## 🏗️ Architecture

```text
                 Users
                   |
                   v
       Application Load Balancer
                   |
             Target Group
             /     |     \
            v      v      v
         EC2-1   EC2-2   EC2-3
```

## ⚙️ Implementation Steps

1. Access the AWS Management Console.
2. Create a security group and configure inbound rules.
3. Launch three EC2 instances.
4. Configure the application using user data.
5. Create a target group and register the instances.
6. Create an Application Load Balancer.
7. Attach the target group and configure network settings.
8. Verify the load balancer using its DNS name.
9. Clean up resources to help avoid unnecessary charges.

## 📄 Project Documentation

The accompanying PDF provides the detailed implementation guide and screenshots.

**Documentation:** `AWS-Elastic-Load-Balancer-Documentation.pdf`

## 🔐 Security Considerations

- Restrict SSH access to trusted IP addresses.
- Allow only the required inbound traffic.
- Use appropriate security groups for the load balancer and backend instances.
- Review AWS resource costs and delete unused resources.

## 📚 Key Learnings

- EC2 instance configuration
- Security group rules
- Target group registration
- Application Load Balancer configuration
- Traffic distribution and availability
- AWS resource cleanup

---

**Project Category:** AWS Cloud Computing  
**Project Type:** Hands-on implementation and documentation
