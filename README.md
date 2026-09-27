# Centralized Egress Traffic Filtering using Azure Hub-Spoke Architecture

## Team Members
- Jaladi Revanth
- K Surya Dev
- C vinay
- Koleti Kundhana Siri


## Project Description

This project implements centralized outbound traffic filtering
using an Azure Hub-and-Spoke network architecture.

## Architecture Components

- Hub VNet
- Spoke VNet
- Azure Firewall
- Azure Bastion
- VNet Peering
- Route Table
- Workload Subnet
- Virtual Machine

## Traffic Flow

Spoke VM
    ↓
Route Table
    ↓
Azure Firewall
    ↓
Internet

## Management Access

User
 ↓
Azure Bastion
 ↓
VNet Peering
 ↓
Spoke VM

## Objective

To ensure that outbound traffic from workload resources in
the spoke network is centrally inspected and controlled through
Azure Firewall.

## Technologies

- Microsoft Azure
- Azure Virtual Network
- Azure Firewall
- Azure Bastion
- VNet Peering
- Azure Route Tables
- Azure Virtual Machine
- GitHub
