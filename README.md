# Cisco Catalyst vs. Nexus Switches Overview Guide

**Description/Overview:** Cisco Catalyst and Nexus Switches are two of the most popular choices in networking switch solutions, but they serve two different overall use cases: Catalyst switches are traditionally used for corporate networks, while Nexus switches are a popular choice for data centers (and similar) with complex configuration needs. This guide will dive into the purposes, similarities, differences, and other implications of these two product lines. 

#### Table of Contents

1. [Cisco Catalyst Overview](#catalyst)
2. [Cisco Catalyst Models](#catamodels)
3. [Cisco Nexus Overview](#nexus)
4. [Cisco Nexus Models](#nexusmodels)
5. [Comparison and Contrast Table](#compare)
6. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="catalyst">Cisco Catalyst Overview</a>

Cisco Catalyst switches are commonly implemented in corporate networks in which users and host devices may rapidly scale throughout a large network. While Small Office Home Office (SOHO) networks are unlikely to require or benefit from the power of Catalyst switches, higher education and company campuses and office buildings are common users. Catalyst switches run on Cisco's IOS operating system, which has a moderate learning curve and can be studied and simulated using free Cisco network mapping and simulation tools such as [Packet Tracer](https://www.netacad.com/cisco-packet-tracer).

Catalyst switches are flexible in how link aggregation (which dynamically manages Ethernet channels) can be employed: they support both the open-source Link Aggregation Control Protocol (LACP) and the proprietary Port Aggregation Control Protocol (PAgP).

<hr />

## 2. <a name="catamodels">Cisco Catalyst Models</a>

(TODO)

<hr />

## 3. <a name="nexus">Cisco Nexus Overview</a>

Cisco Nexus switches are intended for implementation in data centers, as well as other data-heavy and mission-critical professional networks with advanced configuration and sustainability requirements. Nexus switches run on the Linux kernel based Cisco Nexus Operating System (NX-OS), which can optimize process automation, network security, availability, scalability, and performance. While this OS empowers networking professionals by providing complex and nuanced features, it also has a potentially steep learning curve.

Nexus switches are limited in how they employ link aggregation (which dynamically manages Ethernet channels): they commonly only support the open-source Link Aggregation Control Protocol (LACP) as their protocol for conducting this task. However, they do support a variety of media for connections, such as Ethernet, fiber, and Fiber Channel over Ethernet (FCoE) cabling. 

<hr />

## 4. <a name="nexusmodels">Cisco Nexus Models</a>

(TODO)

<hr />

## 5. <a name="compare">Comparison and Contrast Table</a>

*Note: Catalyst and Nexus switches are compatible, and can be provisioned onto the same network environment and as components of the same server racks and aggregations.*

| *Feature* | *Cisco Catalyst Switches* | *Cisco Nexus Switches* |
| :---: | :---: | :----: |
| Automation | Cisco Catalyst Center (UI) allows for automated configurations, auto-discovery, and zero-touch provisions. | NX-OS Supports APIs, Python, and related integrations. |
| Convergence | Generalized recovery and broacast storm prevention via Spanning Tree Protocol (STP). | Intended for data centers. STP with Rapid PVST+, Virtual Port Channels (vPC) |
| Performance & Scalability | Versatile/intended for customizations. | Can be updated while in production while maintaining high performance, but more complex to configure. |
| Power over Ethernet (PoE) | Utilizes PoE+, increasing range of switch-plugged devices and Ethernet power without introducing additional cables. | Not included with all Nexus switches. |
| Security | Authorization controls via port security, Access Control Lists (ACLs), Dynamic Host Configuration Protocol (DHCP) Snooping. | Strong security policy enforcement and network segmentation. |
| Virtualization | Some deployment and resource sharing possibilities. Fewer virtualization options than Nexus switches. | NetFlow, Virtual Device Context (VDC), and virtual machine connectivity capabilities. More virtualization options than Catalyst switches. |
| Cost | Less expensive up-front costs. | More expensive up-front costs, for advanced features and longer-term stability. |

<hr />

## 6. <a name="supplemental">Supplemental Resources</a>

* *[Ubiquiti and Cisco Meraki Overview Guide](https://github.com/chaseofthejungle/unifi-vs-cisco-meraki)*
* *[Intro to Load Balancing Overview Guide](https://github.com/chaseofthejungle/intro-to-load-balancing)*
* *[Intro to Data Center Virtualization](https://github.com/chaseofthejungle/intro-to-data-center-virtualization/)*
