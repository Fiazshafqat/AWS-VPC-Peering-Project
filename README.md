# AWS-VPC-Peering-Project
Implementation  AWS VPC Peering architecture designed to enable private communication between multiple VPCs within AWS.

# AWS VPC Peering Architecture Implementation

## Overview

This project demonstrates the implementation of a secure AWS VPC Peering architecture designed to enable private communication between multiple VPCs within AWS.

![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/vpc-peering-diagram.png.jpg?raw=true)

The setup includes:

* Public and Private Subnets
* Route Tables Configuration
* Internet Gateway (IGW)
* NAT Gateway
* EC2 Instances
* Secure Inter-VPC Communication using VPC Peering

This hands-on implementation strengthened my understanding of AWS networking, routing, subnet segmentation, and scalable cloud infrastructure design.

---

## Architecture Components

### AWS Services Used

* Amazon VPC
* EC2 Instances
* VPC Peering Connection
* Route Tables
* Internet Gateway (IGW)
* NAT Gateway
* Public & Private Subnets
* Security Groups

---

## Key Features

✅ Secure communication between VPCs
✅ Public and private subnet architecture
✅ Route table management for peering traffic
✅ Internet access through IGW and NAT Gateway
✅ Scalable and highly available cloud networking design

---

## Project Architecture

* VPC-A and VPC-B connected through VPC Peering
* Public subnets host internet-facing resources
* Private subnets host internal resources
* Route tables configured for private communication between VPCs
* NAT Gateway used for outbound internet access from private subnets

---

## Learning Outcomes

* Improved understanding of AWS networking concepts
* Hands-on experience with VPC Peering configuration
* Better understanding of cloud infrastructure security
* Practical knowledge of routing and subnet segmentation
* Experience with AWS best practices for networking

---

## Technologies Used

| Technology       | Purpose                             |
| ---------------- | ----------------------------------- |
| AWS VPC          | Network Isolation                   |
| EC2              | Compute Resources                   |
| Route Tables     | Traffic Routing                     |
| NAT Gateway      | Internet Access for Private Subnets |
| Internet Gateway | Public Internet Connectivity        |
| VPC Peering      | Private VPC Communication           |

---

---

# Project Screenshots

## 1. AWS VPC Overview
![image alt]([https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/vpc-peering-diagram.png.jpg?raw=true])

## 2. Create 2 VPC 
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/vpc.png.jpg?raw=true)

## 3. Create Public and Private Subnets
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/subnets.png.jpg?raw=true)

## 4. Create Internet Gateway for internet access of resources inside public subnet
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/igw.png.jpg?raw=true)

## 5. Create NAT Gateway for communication of Public and private subnets within vpc
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/nat-gw.png.jpg?raw=true)

## 6. Created EC2 Instances for both VPC1 and VPC2
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/ec2-instances.png.jpg?raw=true)

## 7. Created Route table for both VPC
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/route-table.png.jpg?raw=true)

## 8. Create and Configure Peering Connection b/w vpc
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/peering-created.png.jpg?raw=true)

## 9. Check and verify VPC Peering status is active
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/peering-active.png.jpg?raw=true)

 ## 10. Route table entries for VPC1
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/test-vpc1-rt.png.jpg?raw=true)

 ## 11. Route table entries for VPC2
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/prod-vpc2-rt.png.jpg?raw=true)

## 12. Verify connectivity between instances by pinging eachother IP address
![image alt](https://github.com/Fiazshafqat/AWS-VPC-Peering-Project/blob/main/ec2-connectivity.png.jpg?raw=true)
## Author

**Muhammad Fiaz**
Network Systems Engineer | Cloud & Infrastructure Enthusiast

---

## Tags

`AWS` `VPC` `VPC-Peering` `Cloud-Computing` `AWS-Networking` `DevOps` `EC2` `Infrastructure` `Cloud-Security`
