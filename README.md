# Networking for DevOps

## Module 1: Introduction to Networking Basics

##### [1.1 Overview of Computer Networks](./Module-1/1.1-Overview-Computer-Networks.md)

- Definition and importance of computer networks
- Types of networks: LAN, WAN, MAN

##### [1.2 OSI Model and TCP/IP Model](./Module-1/1.2-OSI-Model-TCP-IP-Model.md)

- Understanding the layers and their functions
- Comparison of OSI and TCP/IP models

##### [1.3 Networking Protocols & Ports](./Module-1/1.3-Networking-Protocols.md)

- Common protocols (e.g., HTTP, HTTPS, TCP, UDP, DNS)
- Common Ports

### Module 2: IP Addressing and Subnetting

##### [2.1 IPv4 Addressing](./Module-2/2.1-IPv4-Addressing.md)

- Binary representation
- Classes of IP addresses (A, B, C)
- Private vs. Public IP addresses

##### [2.2 Subnetting](./Module-2/2.2-Subnetting.md)

- Subnetting basics and importance
- Subnet masks and CIDR notation

### Module 3: Routing and Switching

##### [3.1 Routing Concepts](./Module-3/3.1-Routing-Concepts.md)

- Basics of routing
- Routing tables and how they work
- Static vs. Dynamic Routing

##### [3.2 Switching](./Module-3/3.2-Switching.md)

- Understanding switches and their role
- VLANs and their importance in modern networks

### Module 4: Network Services

##### [4.1 Domain Name System (DNS)](./Module-4/4.1-Domain-Name-System.md)

- DNS resolution process
- Configuring DNS settings

##### [4.2 Dynamic Host Configuration Protocol (DHCP)](./Module-4/4.2-Dynamic-Host-Configuration.md)

- DHCP basics
- DHCP server configuration

### Module 5: Network Security

##### [5.1 Firewalls and Security Devices](./Module-5/5.1-Firewalls-Security.md)

- Introduction to firewalls
- Network security best practices

##### [5.2 Virtual Private Networks (VPNs)](./Module-5/5.2-VPN.md)

- Basics of VPNs
- Implementing VPNs for secure communication

### Module 6: Infrastructure as Code (IaC) for Networking

##### [6.1 Using Automation Tools](./Module-6/6.1-Using-Automation-Tools.md)

- Ansible, Puppet, or Chef for network automation
- Writing playbooks for network configuration

### Module 7: Docker Networking

##### [7.1 Introduction and Basics of Docker Networking](./Module-7/7.1-Introduction-Docker-Networking.md)

- Overview of Docker as a containerization platform.
- Importance of networking in containerized environments.
- Basics of container communication within a host.
- Understanding the default bridge network.

##### [7.2 Custom Networks in Docker](./Module-7/7.2-Custom-Networks-Docker.md)

- Creating and utilizing custom bridge networks.
- Communication between containers in user-defined bridge networks.
- Use of container names for intra-network communication.

##### [7.3 Advanced Networking Concepts and Connectivity](./Module-7/7.3-Advanced-Networking-Concepts-Connectivity.md)

- Introduction to overlay networks in Docker.
- Container DNS resolution and service discovery.
- Port mapping and configuring external connectivity.
- Utilizing the host network mode for direct host stack access.

##### [7.4 Advanced Topics, Security, and Commands](./Module-7/7.4-Advanced-Topics-Security-Commands.md)

- Docker Compose for defining multi-container applications.
- Third-party network plugins and their applications.
- Security considerations in Docker networking.
- Essential Docker networking commands (`docker network ls`, `docker network create`, etc.).

### Module 8: Cloud Networking

##### [8.1 Cloud Service Models](./Module-8/8.1-Cloud-Service-Models.md)

- IaaS, PaaS, SaaS
- Networking in the cloud

##### [8.2 Cloud Providers (Choose one: AWS, Azure, GCP)](./Module-8/8.2-Cloud-Providers-AWS.md)

**Chosen AWS**

- Basics of cloud networking
- Virtual Private Cloud (VPC), Subnetting, Security Groups

### Module 9: Monitoring and Logging

##### [9.1 Network Monitoring Tools](./Module-9/9.1-Network-Monitoring-Tools.md)

- Introduction to monitoring tools (e.g., Nagios, Prometheus)
- Monitoring network performance

##### [9.2 Log Aggregation](./Module-9/9.2-Log-Aggregation.md)

- Using ELK stack for log aggregation

### Module 10: Version Control for Network Configurations

##### [10.1 Using Git for Network Configuration Version Control](./Module-10/10.1-Using-Git-Network-Configuration.md)

- Best practices for managing network changes

### Module 11: Continuous Integration/Continuous Deployment (CI/CD) for Networking

##### [11.1 Integrating Network Changes into CI/CD Pipelines](./Module-11/11.1-Integrating-Network-into-CI-CD-Pipelines.md)

- Automated testing for network configurations
