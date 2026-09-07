# **01 — SOHO Network**

# Project Overview

This project documents the design and implementation of a Small Office/Home Office (SOHO) network using Cisco Modeling Labs (CML).

The objective is to build a functional network while demonstrating fundamental networking concepts and developing a structured approach to network design, configuration, testing, and troubleshooting.

# Objectives

The network will demonstrate:

IPv4 addressing
Subnetting
Layer 2 switching
Layer 3 routing
DHCP
DNS
NAT
Basic network security
Connectivity testing
Troubleshooting
Network documentation
Topology

The initial topology will contain five active nodes:

                    Internet
                       |
                      R1
                       |
                      SW1
                   /   |   \
                 PC1  PC2  SRV1

Node   | Role              | Platform
-------|-------------------|------------
R1     | Router / Gateway  | Cisco IOS
SW1    | LAN Switch        | Cisco IOS-L2
PC1    | User Workstation  | Windows10
PC2    | User Workstation  | Windows10
SRV1   | Internal Server   | Nginx

# Network Design

The initial network will use a private IPv4 address space.

Detailed addressing information will be documented in:

addressing/

# Configuration

Device configurations will be documented in:

configurations/

# Testing

Connectivity and functionality tests will be documented in:

testing/

# Troubleshooting

Problems encountered during implementation and the troubleshooting process will be documented in:

troubleshooting/

# Screenshots

Topology diagrams, CML screenshots, and relevant test results will be stored in:

screenshots/

Status

🚧 Project currently in progress.
