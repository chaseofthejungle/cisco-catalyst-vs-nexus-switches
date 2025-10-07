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

**Cisco Catalyst switches are generalized into two different model types:**

* Fixed configuration switches (typically 1-2 rack units high, ranging between two dozen and 80 ports).
* Modular (intended for customization) switches (with individually configurable components, including chassis, line cards, power supplies, and supervisor modules).

**Catalyst model names tend to:**

* Begin with the letter 'C' or the pattern 'WS-C', with a model line indicated afterward (e.g., C6800).
  + A letter following the number indicates a unique feature of the switch.
    - After this letter (should there be one), the switch's port count is noted (typically two or four dozen).
* Include characters indicating extra characteristics of the switch (for example, the 'U' in 'C9300-24U' indicates Universal Power over Ethernet).  
* In the case of Catalyst 9000 switches, note the software subscription license (with 'A' for 'Advantage', 'E' for 'Essentials', or 'P' for 'Premier').

**Roles of switches:**

* *Access Switches:* Serve as entry points, or gateways, for connecting end-user devices to networks.
* *Distribution Switches:* Aggregate access traffic, apply policies, and serve as a bridge to the core level.
* *Core Switches:* Serve as the backbones of networks by providing reliable, high speed connectivity, and route distribution device traffic.

**Fixed configuration Catalyst switch lines include:**

* *Cisco Catalyst 9200 Series:* Stackable (can operate standalone or with other switches) access switches. Layer 2 and 3 devices.
* *Cisco Catalyst 9300 Series:* Stackable access and distribution switches. Layer 2 and 3 devices.
* *Cisco Catalyst 9500 Series:* Stackable core switches. Layer 2 and 3 devices.
* *Cisco Catalyst 1000 Series:* Stackable access switches. Layer 2 devices.
* *Cisco Catalyst 2960-L Series:* Access switches. Layer 2 and 3 devices.
* *Cisco Catalyst 2960-X/XR Series:* Stackable access switches. Layer 2 and 3 devices.
* *Cisco Catalyst 3560CX/2960CX Series:* Smaller, fanless switches. Layer 2 and 3 devices.
* *Cisco Catalyst Digital Building Series:* Smaller, fanless switches. Layer 2 and 3 devices.
* *Cisco Catalyst 3650 Series:* Stackable switches. Layer 2 and 3 devices.
* *Cisco Catalyst 3850 Series:* Stackable access and distribution switches. Layer 2 and 3 devices.

**Modular Catalyst switch lines include:**

* *Cisco Catalyst 4500 Series:* Mid-level modular switches, including a chassis, line cards, service modules, power supplies, and one or more supervisors.
  + The 4500 series includes the 'E-Series' and 'Classic' chassis (which comes in four sizes: three, six, seven, or ten slots).
* *Cisco Catalyst 6500 Series:* Chassis-based switches supporting devices of up to 40 Gigabit Ethernet (in speed and redundant supervisor modules).
* *Cisco Catalyst 6800 Series:* Chassis-based switches supporting devices of up to 40 Gigabit Ethernet (in speed and redundant supervisor modules).
* *Cisco Catalyst 9400 Series:* Chassis-based access and distribution switches supporting devices of up to 40 Gigabit Ethernet (in speed and redundant supervisor modules, fans, and power supplies).
* *Cisco Catalyst 9600 Series:* Chassis-based core switches supporting devices of up to 100 Gigabit Ethernet (in speed and redundant supervisor modules, fans, and power supplies).

<hr />

## 3. <a name="nexus">Cisco Nexus Overview</a>

Cisco Nexus switches are intended for implementation in data centers, as well as other data-heavy and mission-critical professional networks with advanced configuration and sustainability requirements. Nexus switches run on the Linux kernel based Cisco Nexus Operating System (NX-OS), which can optimize process automation, network security, availability, scalability, and performance. While this OS empowers networking professionals by providing complex and nuanced features, it also has a potentially steep learning curve.

Nexus switches are limited in how they employ link aggregation (which dynamically manages Ethernet channels): they commonly only support the open-source Link Aggregation Control Protocol (LACP) as their protocol for conducting this task. However, they do support a variety of media for connections, such as Ethernet, fiber, and Fiber Channel over Ethernet (FCoE) cabling. 

<hr />

## 4. <a name="nexusmodels">Cisco Nexus Models</a>

**Nexus switch lines include:**

* *Cisco Nexus 1000v Virtual Switches:* Supplies a high-security architectural platform for remote/cloud networks (including multi-tenant deployments) and virtualized servers.
* *Cisco Nexus 2000 Fabric Extenders:* Supplies centralized and highly scalable architecture for data center server access/operations and virtualization. 'Extends' parent Nexus switch fabric and, in the process, creates distributed systems that are also modular in nature.
* *Cisco Nexus 3000 Series:* Specializes in low latency for various deployments (such as data centers and cloud environments).
* *Cisco Nexus 4001 IBM (4001I) Blade Center Switches:* Utilized by BladeCenter H and HT chassis, with Fibre Channel over Ethernet (FCoE) capabilities, low latency, high scalability, and support for high performance server virtualization.
* *Cisco Nexus 5000 Series:* Supplies FCoE switching to simplify data center input/output operations.
* *Cisco Nexus 6000 Series:* Highly dense, compact, energy optimizing, and strongly performing. For virtualized servers, remote/cloud, and other deployments (even if space is constrained).
* *Cisco Nexus 7000 Series Catacenter Switches:* Harmonizes well with Cisco NX-OS features, Software-Defined Networking (SDN) utilities, and Unified Fabric solutions for contemporary data centers.
* *Cisco Nexus 9000 Series:* Versatile, whether for entirely automated data centers or traditional data servers, with compatibility for both NX-OS and Application Centric Infrastructure (ACI). Provides low latency, power optimization, compact form factors, and high density and performance.  

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
