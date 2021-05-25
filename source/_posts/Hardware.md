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
| DELL | R720 - PowerEdge R720 12th Generation 2U | E5-2620 2.0GHz | DDR3 32GB (2x16GB) | Primary Site |
| DELL | R210ii - PowerEdge R210ii 11th Generation 1U | E3-1280v2 3.6GHz | DDR3 32GB (4x8GB) | Secondary Site |

## Networking - Primary Site
  
| Manufacturer | Model - Description |
| ------------ | ------------ |
| RPi Foundation | Raspberry Pi 4 2GB (as a primary Pi-hole) |
| RPi Foundation | Raspberry Pi 4 2GB (as a secondary Pi-hole) |
| Ubiquiti | USG-3P - UniFi Security Gateway |
| Ubiquiti | Flex - UniFI 5-Port Managed PoE Gigabit Switch |
| Ubiquiti | UAP-AC-IW - UniFi AP AC In-wall |
| Ubiquiti | UAP-AC-IW - UniFi AP AC In-wall |
| Ubiquiti | UAP-AC-M-US - UniFi Mesh AP |
| TP-LINK | TL-T1600G-28TS - JetStream 24-Port Managed Gigabit Switch |
| TP-LINK | TL-SG3424P - JetStream 24-Port Managed PoE Gigabit Switch |

## Networking - Secondary Site
| Manufacturer | Model - Description |
| ------------ | ------------ |
| RPi Foundation | Raspberry Pi 4 2GB (as a edge device) |
| ZYXEL | ES-2024PWR - 24-Port Managed PoE Switch |

## R7910 (Host Name: KLSCOMMANDER01)
- Operating System:  Windows 10 Professional
- Status: Operational / Reprovision Pending
- Procured: 2019
- Network: 1x1GB Ethernet (IPMI), 4x1GB Ethernet (General Network Connectivity), 2x10GB Fiber SFP+ (Fiber Connectivity)  
- Data Stores, 8x2.5" Bays
    - OS Data: 2x512GB SSD, RAID1, 512GB Usable Space, 1TB Raw Space
    - Default Data: 2x2TB SSD, RAID0, 4TB Usable Space, 4TB Raw Space
    - Cold Data: 4x4TB HDD, RAID6, 8TB Usable Space, 16TB Raw Space 

![Dell Precision Rack 7910 2U Workstation](../../../../images/kls-fsc-r7910-sm.jpg "Dell Precision Rack 7910 2U Workstation")

## R630 (Host Name: HYPERMAN03)
- Operating System:  Windows 2019
- Status: Operational
- Procured: 2020
- Network: 1x1GB Ethernet (IPMI), 4x1GB Ethernet (General Network Connectivity), 2x10GB Fiber SFP+ (Fiber Connectivity) 
- Data Stores, 8x2.5" Bays
    - OS Data: 2x1TB SSD, RAID1, 1TB Usable Space, 2TB Raw Space
    - Default Data: 6x4TB HDD, RAID6, 16TB Usable Space, 24TB Raw Space 

![Dell PowerEdge R630 1U Server](../../../../images/kls-fsc-r630-sm.jpg "Dell PowerEdge R630 1U Server")

## R720 (Host Name: FAMILYFILES)
- Operating System:  Windows 2019
- Status: Operational
- Procured: 2017
- Network: 1x1GB Ethernet (IPMI), 4x1GB Ethernet (General Network Connectivity), 4x10GB Fiber SFP+ (Fiber Connectivity) 
- Data Stores, 16x2.5" Bays
    - OS Data: 2x512GB SSD, RAID1, 512GB Usable Space, 1TB Raw Space
    - Default Data: 6x1.92TB Enterprise SSD, RAID6, 7.68TB Usable Space, 11.52TB Raw Space
    - Cold Data: 6x4TB HDD, RAID6, 16TB Usable Space, 24TB Raw Space
    - Hot Data #1: 2x512GB NVMe PCIe, RAID1, 512GB Usable Space, 1TB Raw Space
    - Hot Data #2: 2x512GB NVMe PCIe, RAID1, 512GB Usable Space, 1TB Raw Space

![Dell PowerEdge R720 2U Server](../../../../images/kls-fsc-r720-sm.jpg "Dell PowerEdge R720 2U Server")

## Storage Stats
- Usable Space: ~54TB
- Raw Space: ~85.5TB

## Iterations
[View past iterations of the lab](/lab/Iterations)