# Celebral-Summer-Internship

## Project 1 - Secure Hosting of Web App via Azure Application Gateway
### Senerio:
Implement Hub and Spoke topology where Hub contains the centralized components like Azure Firewall, Application Gateway, DNS Forwarding VM, Azure Bastion etc. and one spoke has Web App and another spoke has a Storage account with no public access.
1. Establishes a secure connection between the on-premises data centre and the hub VNet and Spoke VNets.
2. Provides custom DNS on the top of Spoke VNets as DNS Forwarding VM.
3. Resolve all the DNS queries for Azure to On-premises, Azure to Azure and On-premises to Azure.
4. All the traffic should be routed through Azure Firewall.
5. Internet traffic will land on Application Gateway Public Fronted IP.
6. On-Premises traffic will land on Application Gateway Private Fronted IP.
7. SSL Offloading will be implemented on top of Application Gateway.
8. Set up multiple listeners to route traffic to the backend with their respective set of configurations.


## Week 1 Assignment - The OSI Model
### Discuss about OSI Model:
The Seven Layers of the OSI Model.

![OSI Model layer](https://github.com/user-attachments/assets/4c44d509-3841-4410-9f48-30f69476c1c0)

## Week 2 Assignment - IP Addressing
IP (Internet Protocol) addressing is a fundamental aspect of networking and is crucial for the identification and communication between devices on a network. 

![Olaf_Fig-1](https://github.com/user-attachments/assets/e98e46bb-bd29-43ee-995c-35b3c192bbaf)

## VNET(Virtual Network)

1. A VNET in Azure is similar to a traditional on-premises network.
2. It allows secure communication between Azure resources (VMs, databases, containers, etc.).
3. Enables isolation, segmentation, and security.

## Network Security Group

1. NSGs act as a firewall, controlling inbound and outbound traffic.
2. You define rules to allow or deny traffic based on IP, port, and protocol.

## Subneting & Configure Server

1. Subnetting divides a VNET into smaller logical networks.
2. Each subnet can have different access control policies.
3. VMs, databases, and app services can be placed in separate subnets.

## Load Balancer
### Types:

1. Internal Load Balancer
2. External Load Balancer

Azure Load Balancer distributes incoming traffic across multiple VMs.Helps in scalability and high availability.

## Set-up Alert Rule

1. Azure Monitor can trigger alerts based on conditions (CPU usage, memory, etc.).
2. Helps in proactive performance monitoring and security.

## VPN(Virtual Private Network)

#### 1. Azure VPN Gateway allows secure connectivity between:
1. On-premises networks 🌍 ↔ Azure Cloud ☁️
2. Different Azure regions
#### 2. Uses IPsec/IKE encryption.
#### 3. Types of VPN:
1. Site-to-Site (S2S)
2. Point-to-Site (P2S)

