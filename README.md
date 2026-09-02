# Azure Enterprise Network Lab

A hands-on Microsoft Azure networking lab designed to demonstrate practical experience in enterprise cloud networking, infrastructure deployment, network security, load balancing, and VPN connectivity.

## Project Overview

This project implements an enterprise-style network infrastructure in Microsoft Azure using Azure Virtual Network, multiple subnets, Network Security Groups, Windows Server virtual machines, Azure Load Balancer, VM Scale Set, and VPN Gateway.

The lab focuses on building and testing a secure and scalable Azure network environment.

## Architecture

The lab includes:

- Azure Resource Group
- Azure Virtual Network (VNet)
- Multiple Subnets
- Network Security Groups (NSG)
- Windows Server Virtual Machines
- Virtual Machine Scale Set (VMSS)
- Azure Load Balancer
- Azure VPN Gateway
- Point-to-Site (P2S) VPN
- IIS Web Server

## Key Components

### Azure Virtual Network

Created an Azure Virtual Network with multiple subnets to provide network segmentation and connectivity between Azure resources.

### Network Security Groups

Configured NSG inbound rules to control access to the deployed resources, including:

- RDP
- HTTP
- Load Balancer traffic

### Windows Server Virtual Machines

Deployed Windows Server virtual machines with private and public IP addressing.

IIS was configured to provide a web service for testing load balancing and connectivity.

### Azure Load Balancer

Configured an Azure Load Balancer with:

- Backend Pool
- HTTP Health Probe
- Load-Balancing Rule

The Load Balancer distributes incoming HTTP traffic across backend resources.

### Virtual Machine Scale Set

Configured a Virtual Machine Scale Set to provide scalable compute resources within the Azure environment.

### VPN Gateway

Configured Azure VPN Gateway with Point-to-Site (P2S) VPN connectivity to provide secure remote access to the Azure virtual network.

## Skills Demonstrated

- Azure Virtual Network Design
- Subnetting and Network Segmentation
- Network Security Groups
- Azure Load Balancing
- VM and VMSS Deployment
- Windows Server Administration
- IIS Configuration
- VPN Gateway Configuration
- Point-to-Site VPN
- Azure Network Troubleshooting
- Cloud Networking

## Documentation

Detailed project documentation, configuration steps, and implementation screenshots are available in the project PDF:

**[Azure Enterprise Lab Documentation](./Azure_Enterprise_Lab_GitHub_Ordered.pdf)**

## Technologies

- Microsoft Azure
- Azure Virtual Network
- Azure Load Balancer
- Azure VPN Gateway
- Virtual Machine Scale Set
- Network Security Groups
- Windows Server
- IIS
