---
title: Hardware
date: 2021-05-24 11:23:46
tags: hardware, enterprise servers, networking
---

## Servers
  
| Manufacturer | Model - Description | CPU | RAM | Location |
| ------------ | ------------ | ------------ | ------------ | ------------ |
| DELL | R7910 - Precision Rack 7910 2U | 2x E5-2667v3 3.2GHz | DDR4 192GB (12x16GB) | Primary Site |
| DELL | R630 - PowerEdge R630 13th Generation 1U | 2x E5-2643v3 3.4GHz | DDR4 256GB (8x32GB) | Primary Site |
| DELL | R330 - PowerEdge R330 13th Generation 1U | E3-1220v5 3.0GHz |DDR4 16GB (xGB) | Primary Site |
| DELL | R210ii - PowerEdge R210ii 11th Generation 1U | E3-1280v2 3.6GHz | DDR3 32GB (4x8GB) | Secondary Site |

## Networking - Primary Site
  
| Manufacturer | Model - Description |
| ------------ | ------------ |
| RPi Foundation | Raspberry Pi 4 2GB (as a primary Pi-hole) |
| RPi Foundation | Raspberry Pi 4 2GB (as a secondary Pi-hole) |
| Ubiquiti | USG-3P - UniFi Security Gateway |
| Ruckus | H510 - In Wall Access Point |
| Ruckus | H510 - In Wall Access Point |
| Ruckus | R610 - Access Point |
| Ruckus | R610 - Access Point |
| TP-LINK | TL-T1600G-28TS - JetStream 24-Port Managed Gigabit Switch |
| TP-LINK | TL-SG3424P - JetStream 24-Port Managed PoE Gigabit Switch |
| TP-LINK | TL-SG3424P - JetStream 24-Port Managed PoE Gigabit Switch |

## Networking - Secondary Site
| Manufacturer | Model - Description |
| ------------ | ------------ |
| RPi Foundation | Raspberry Pi 4 2GB (as a edge device) |
| ZYXEL | ES-2024PWR - 24-Port Managed PoE Switch |

## R7910 (Host Name: KLSESXI01)
- Operating System:  VMware vSphere 7
- Status: Operational, Hypervisor with GPU Provisioning Capabilities
- Procured: 2019
- Network: 1x1GB Ethernet (IPMI), 4x1GB Ethernet (General Network Connectivity), 2x10GB SFP+ (Fiber Connectivity)  
- Data Stores, 8x2.5" Bays
    - OS Data: 256GB NVMe SSD via PCIe, Standalone, 256GB Usable Space, 256GB Raw Space
    - Default Data: 6x1.92TB Enterprise SSD, RAID6, 7.68TB Usable Space, 11.52TB Raw Space

![Dell Precision Rack 7910 2U Workstation](../../../../images/kls-fsc-r7910-sm.jpg "Dell Precision Rack 7910 2U Workstation")

## R630 (Host Name: HYPERMAN03)
- Operating System:  Windows Server 2019
- Status: Operational, Hypervisor
- Procured: 2020
- Network: 1x1GB Ethernet (IPMI), 4x1GB Ethernet (General Network Connectivity), 2x10GB SFP+ (Fiber Connectivity) 
- Data Stores, 8x2.5" Bays
    - OS Data: 2x1TB SSD, RAID1, 1TB Usable Space, 2TB Raw Space
    - Default Data: 6x4TB HDD, RAID6, 16TB Usable Space, 24TB Raw Space 

![Dell PowerEdge R630 1U Server](../../../../images/kls-fsc-r630-sm.jpg "Dell PowerEdge R630 1U Server")

## R330 (Host Name: KLSNAS01)
- Operating System:  Windows Server 2022
- Status: Operational, Data Store, iSCSI, NAS
- Procured: 2021
- Network: 1x1GB Ethernet (IPMI), 2x1GB Ethernet (General Network Connectivity), 4x10GB SFP+ (Fiber Connectivity) 
- Data Stores, 4x3.5" Bays
    - OS Data: 512GB NVMe SSD via PCIe, 512GB Usable Space, 512GB Raw Space
    - Default Data: 4x10TB HDD, RAID6, 20TB Usable Space, 40TB Raw Space

![Dell PowerEdge R330 1U Server](../../../../images/kls-fsc-r330-sm.jpg "Dell PowerEdge R330 1U Server")

## Iterations
[View past iterations of the lab](/lab/Iterations)