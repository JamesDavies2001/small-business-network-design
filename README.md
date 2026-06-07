# Small Business Network Design

## Overview
This project presents a conceptual network design for a small business environment. The design focuses on infrastructure planning, network segmentation, security controls, redundancy, remote management, backup strategy, and cost estimation.

The goal was to create a secure and scalable network that could support office operations, customer-facing computers, point-of-sale transactions, guest/patron access, file and print sharing, and future business growth.

This was a design and planning project rather than a hands-on deployment.

## Business Scenario
A small business needs a cost-effective technology infrastructure to support:

- Office workstations
- Customer/patron computers
- Point-of-sale transactions
- Guest wireless access
- File and print sharing
- Remote management
- Data backups
- Basic cybersecurity controls

## Objectives
- Design a segmented network using VLANs
- Separate office, patron/customer, and POS traffic
- Select appropriate hardware and software components
- Create firewall rules to limit unnecessary network access
- Recommend backup and redundancy measures
- Estimate hardware and yearly software costs
- Communicate the design through a network diagram

## Proposed Solution Components
This project was a conceptual network design. The components below were selected as part of the proposed solution, but were not physically implemented or configured.

- Workstations for office and patron use
- POS terminal and cloud-based POS system
- Router/security appliance
- Layer 3 PoE switch for VLAN segmentation
- Wireless access points
- Tower server for domain, file, and print services
- Endpoint protection
- Backup software
- Remote management software
- Web hosting and e-commerce platform

## Network Design Summary
The network design uses VLAN segmentation to separate business-critical systems from customer-facing devices.

Planned VLANs include:

- **Management VLAN:** office PCs, server, printer, and administrative systems
- **Patron VLAN:** customer/training PCs and wireless access
- **POS VLAN:** point-of-sale system and transaction-related traffic

Firewall rules are used to restrict traffic between VLANs and only allow necessary communication. This helps protect office resources and POS systems from unnecessary exposure.

## Security Considerations
The design includes several basic security controls:

- Inter-VLAN traffic restrictions
- Segmentation of POS systems from customer-facing devices
- Firewall rules to block unnecessary access between network zones
- Endpoint protection for business devices
- Weekly local and cloud backups
- Remote monitoring and management planning

## Redundancy and Continuity Planning
To reduce downtime and support business continuity, the design includes:

- Cloud-based POS availability
- Manual transaction fallback for extended outages
- UPS devices for critical equipment
- Secondary ISP/failover recommendation
- Weekly external and cloud backups

## Cost Estimate
The project includes both hardware and software cost estimates.

- **Estimated hardware total:** approximately $12,238.82
- **Estimated yearly software cost:** approximately $2,146
- **Estimated first-year total:** approximately $14,384.82

## Deliverables
- Full network design report
- Hardware and software cost breakdown
- VLAN segmentation plan
- Firewall rule recommendations
- Logical network overview
- Redundancy and security plan
- Network diagram

## Skills Demonstrated
- Network planning
- Systems analysis
- VLAN segmentation
- Security-focused design
- Cost estimation
- Business technology planning
- Technical documentation
- Infrastructure requirement analysis

## Why This Matters
This project demonstrates the ability to translate business requirements into a practical technology design. It shows how infrastructure, security, cost, and operational continuity can be considered together when planning technology systems for a small business environment.
