# Azure Enterprise Network Lab

## 📌 Overview

A hands-on **Azure Enterprise Network Lab** demonstrating the configuration of an enterprise-style Azure network infrastructure using Azure Virtual Network, subnets, Network Security Groups, Windows Server virtual machines, IIS web servers, Azure Load Balancer, Public IP, and Azure VPN Gateway.

The lab includes practical configuration and validation of network connectivity, web server availability, load balancing, and VPN connectivity.

---

## 📑 Table of Contents

- [📌 Overview](#-overview)
- [📑 Table of Contents](#-table-of-contents)
- [🎯 Lab Objectives](#-lab-objectives)
- [🏗️ Lab Environment](#️-lab-environment)
- [🛠️ Technologies & Services](#️-technologies--services)
- [🔄 Lab Workflow](#-lab-workflow)
  - [1️⃣ Virtual Network & Subnets](#1️⃣-virtual-network--subnets)
  - [2️⃣ Network Security Group](#2️⃣-network-security-group)
  - [3️⃣ Public IP Configuration](#3️⃣-public-ip-configuration)
  - [4️⃣ Windows Server Virtual Machines](#4️⃣-windows-server-virtual-machines)
  - [5️⃣ IIS Web Servers](#5️⃣-iis-web-servers)
  - [6️⃣ Azure Load Balancer](#6️⃣-azure-load-balancer)
  - [7️⃣ Load Balancer Health Probe](#7️⃣-load-balancer-health-probe)
  - [8️⃣ Load Balancing Rule](#8️⃣-load-balancing-rule)
  - [9️⃣ Azure VPN Gateway](#9️⃣-azure-vpn-gateway)
  - [🔟 VPN Connectivity Validation](#-vpn-connectivity-validation)
- [📊 Validation & Testing](#-validation--testing)
- [🧠 Skills Demonstrated](#-skills-demonstrated)
- [📸 Evidence & Documentation](#-evidence--documentation)
- [📁 Project Structure](#-project-structure)
- [⭐ Project Summary](#-project-summary)

---

## 🎯 Lab Objectives

The main objectives of this lab were to:

- Configure an Azure Virtual Network.
- Create and configure multiple subnets.
- Configure Network Security Group rules.
- Configure a Public IP address.
- Deploy Windows Server virtual machines.
- Configure IIS web servers.
- Configure Azure Load Balancer.
- Configure a frontend IP configuration.
- Configure a backend pool.
- Configure a health probe.
- Configure a load balancing rule.
- Configure Azure VPN Gateway.
- Establish and validate VPN connectivity.

---

## 🏗️ Lab Environment

The lab environment includes:

- ☁️ Microsoft Azure
- 🌐 Azure Virtual Network
- 🧩 Azure Subnets
- 🛡️ Network Security Group
- 🌍 Public IP
- 💻 Windows Server Virtual Machines
- 🌐 IIS Web Servers
- ⚖️ Azure Load Balancer
- 🔍 Load Balancer Health Probe
- 🔗 Load Balancing Rule
- 🔐 Azure VPN Gateway

---

## 🛠️ Technologies & Services

| Technology | Purpose |
|---|---|
| **Azure Virtual Network** | Enterprise network infrastructure |
| **Azure Subnets** | Network segmentation |
| **Network Security Group** | Network traffic control |
| **Public IP** | Public connectivity |
| **Windows Server VMs** | Application/web server infrastructure |
| **IIS** | Web server hosting |
| **Azure Load Balancer** | Load distribution between web servers |
| **Health Probe** | Backend server health monitoring |
| **Load Balancing Rule** | Traffic distribution configuration |
| **Azure VPN Gateway** | VPN connectivity |

---

# 🔄 Lab Workflow

## 1️⃣ Virtual Network & Subnets

Configured an Azure Virtual Network for the enterprise lab environment.

Multiple subnets were created within the virtual network to provide network segmentation for the deployed resources.

---

## 2️⃣ Network Security Group

Configured a Network Security Group and inbound security rules to control network traffic to the environment.

The documentation includes the configured inbound security rules and their associated ports, protocols, sources, destinations, and actions.

---

## 3️⃣ Public IP Configuration

Configured an Azure Public IP address for public connectivity to Azure resources.

The Public IP configuration was associated with the Azure networking environment.

---

## 4️⃣ Windows Server Virtual Machines

Deployed Windows Server virtual machines within the Azure Virtual Network.

The lab includes two web server virtual machines:

- **WEB01**
- **WEB02**

The VM networking configuration was connected to the Azure Virtual Network and associated subnet.

---

## 5️⃣ IIS Web Servers

Configured IIS on the Windows Server virtual machines.

The documentation demonstrates the IIS web server running on:

- **WEB01**
- **WEB02**

This provides the web server endpoints used for the Load Balancer configuration.

---

## 6️⃣ Azure Load Balancer

Configured an Azure Load Balancer to distribute incoming traffic across the backend web servers.

The Load Balancer configuration includes:

- Frontend IP configuration
- Backend pool
- Health probe
- Load balancing rule

---

## 7️⃣ Load Balancer Health Probe

Configured a health probe to monitor the availability of the backend web servers.

The health probe configuration shown in the documentation uses HTTP traffic on port **80**.

---

## 8️⃣ Load Balancing Rule

Configured a Load Balancing Rule to distribute incoming traffic from the frontend configuration to the backend pool.

The rule is associated with the configured health probe and backend pool.

---

## 9️⃣ Azure VPN Gateway

Configured an Azure VPN Gateway as part of the enterprise networking environment.

The VPN Gateway is associated with the Azure Virtual Network and provides VPN connectivity.

---

## 🔟 VPN Connectivity Validation

Validated the VPN connection using the VPN client.

The final documentation screenshot shows an established VPN connection with the status:

**Securely Connected!**

---

# 📊 Validation & Testing

The lab documentation provides visual evidence of the configured Azure networking environment, including:

- Virtual Network configuration
- Subnet configuration
- Network Security Group rules
- Public IP configuration
- Windows Server VM configuration
- IIS web server availability
- Load Balancer frontend configuration
- Load Balancer backend pool
- Health probe configuration
- Load balancing rule
- Azure VPN Gateway
- Successful VPN connectivity

The screenshots provide practical evidence of the configured infrastructure and connectivity. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

---

# 🧠 Skills Demonstrated

### 🌐 Azure Networking

- Azure Virtual Network
- Subnet Configuration
- Network Segmentation
- Network Security Groups
- Public IP Configuration

### 💻 Azure Compute & Web Services

- Windows Server Virtual Machines
- IIS Web Server
- Web Server Configuration

### ⚖️ Load Balancing

- Azure Load Balancer
- Frontend IP Configuration
- Backend Pools
- Health Probes
- Load Balancing Rules

### 🔐 VPN Connectivity

- Azure VPN Gateway
- VPN Configuration
- VPN Connectivity Validation

---

# 📸 Evidence & Documentation

The project documentation contains **27 pages of screenshots** covering the Azure networking configuration and validation performed during the lab.

The documentation includes evidence for:

- Azure Virtual Network
- Subnets
- Network Security Group
- Public IP
- Windows Server VMs
- WEB01
- WEB02
- IIS
- Azure Load Balancer
- Frontend IP
- Backend Pool
- Health Probe
- Load Balancing Rule
- Azure VPN Gateway
- VPN connectivity

---

# 📁 Project Structure

```text
Azure-Enterprise-Network-Lab/
│
├── README.md
│
└── Azure_Enterprise_Lab_GitHub_Ordered.pdf
