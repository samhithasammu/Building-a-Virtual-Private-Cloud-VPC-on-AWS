<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Virtual Private Cloud

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-networks-vpc)

**Author:** samhithabbb@gmail.com  
**Email:** samhithabbb@gmail.com

---

## Build a Virtual Private Cloud (VPC)

![Image](http://learn.nextwork.org/motivated_cyan_peaceful_tiger/uploads/aws-networks-vpc_2facf927)

---

## Introducing Today's Project!

In this project, I will demonstrate how to create and configure a Amazon VPC from scratch, including a VPC, a public subnet, and an internet gateway, because understanding VPC networking is a foundational skill for building secure and scalable cloud infrastructure in AWS.

### What is Amazon VPC?

### Personal reflection

---

## Virtual Private Clouds (VPCs)

### What I did in this step

n this step, I will create a new Virtual Private Cloud (VPC) because a VPC provides an isolated and secure network environment where AWS resources can be launched and managed.

### How VPCs work

VPCs are logically isolated virtual networks in AWS that allow users to control IP addressing, subnets, routing, and security for their cloud resources.

### Why there is a default VPC in AWS accounts

There was already a default VPC in my account ever since my AWS account was created. This is because AWS automatically creates a default VPC so users can launch resources immediately without needing to configure networking from scratch.

![Image](http://learn.nextwork.org/motivated_cyan_peaceful_tiger/uploads/aws-networks-vpc_2facf927)

### Defining IPv4 CIDR blocks

An IPv4 CIDR block is a defined range of IP addresses that determines how many resources can exist inside a VPC or subnet and how those resources are addressed within the network.

---

## Subnets

### What I did in this step

In this step, I will create a subnet inside my VPC because subnets help organize resources into smaller network segments and control how they communicate and access the internet.

### Creating and configuring subnets

Subnets are smaller network divisions within a VPC that exist in a specific Availability Zone. There are already subnets existing in my account, one for every Availability Zone in the default VPC.

### Public vs private subnets

The difference between public and private subnets is internet access.
For a subnet to be considered public, it has to route traffic to an internet gateway and assign public IP addresses to resources.

![Image](http://learn.nextwork.org/motivated_cyan_peaceful_tiger/uploads/aws-networks-vpc_157c4219)

### Auto-assigning public IPv4 addresses

Once I created my subnet, I enabled auto-assign public IPv4 addresses. This setting makes sure any EC2 instance launched in this subnet automatically receives a public IP so that it can communicate with and be accessed from the internet.

---

## Internet gateways

### What I did in this step

In this step, I will create and attach an internet gateway to my VPC because it allows resources within the VPC to send and receive traffic from the internet.In this step, I will... because...

### Setting up internet gateways

Internet gateways are AWS components that connect a VPC to the public internet, enabling outbound internet access and inbound traffic for resources with public IP addresses.

Attaching an internet gateway to a VPC means resources in the VPC can access the internet. If I missed this step, my public subnet resources would not be able to communicate with external networks.

![Image](http://learn.nextwork.org/motivated_cyan_peaceful_tiger/uploads/aws-networks-vpc_4ae90410)

---

## Using the AWS CLI

### What I'm doing in this extension



### Exploring CloudShell and CLI

### Debugging my setup

### Comparing CloudShell vs AWS Console

---

---
