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


![OSI Model layer](https://github.com/user-attachments/assets/06905504-00f1-439d-a3b8-bc810bdb316c)


## Week 2 Assignment - IP Addressing
IP (Internet Protocol) addressing is a fundamental aspect of networking and is crucial for the identification and communication between devices on a network. 

![Olaf_Fig-1](https://github.com/user-attachments/assets/e98e46bb-bd29-43ee-995c-35b3c192bbaf)

