# Cisco Catalyst vs. Nexus Switches Overview Guide

**Description/Overview:** Cisco Catalyst and Nexus Switches are two of the most popular choices in networking switch solutions, but they serve two different overall use cases: Catalyst switches are traditionally used for corporate networks, while Nexus switches are a popular choice for data centers (and similar) with complex configuration needs. This guide will dive into the purposes, similarities, differences, and other implications of these two product lines. 

#### Table of Contents

1. [Cisco Catalyst Overview](#catalyst)
2. [Cisco Nexus Overview](#nexus)
3. [Comparison and Contrast Table](#compare)
4. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="catalyst">Cisco Catalyst Overview</a>

Cisco Catalyst switches are commonly implemented in corporate networks in which users and host devices may rapidly scale throughout a large network. While Small Office Home Office (SOHO) networks are unlikely to require or benefit from the power of Catalyst switches, higher education and company campuses and office buildings are common users. Catalyst switches run on Cisco's IOS operating system, which has a moderate learning curve and can be studied and simulated using free Cisco network mapping and simulation tools such as [Packet Tracer](https://www.netacad.com/cisco-packet-tracer).

Catalyst switches are flexible in how link aggregation (which dynamically manages Ethernet channels) can be employed: they support both the open-source Link Aggregation Control Protocol (LACP) and the proprietary Port Aggregation Control Protocol (PAgP).

<hr />

## 2. <a name="nexus">Cisco Nexus Overview</a>

Cisco Nexus switches are intended for implementation in data centers, as well as other data-heavy and mission-critical professional networks with advanced configuration and sustainability requirements. Nexus switches run on the Linux-based Cisco Nexus Operating System (NX-OS), which can optimize process automation, network security, availability, scalability, and performance. While this OS empowers networking professionals by providing complex and nuanced features, it also has a potentially steep learning curve.

Nexus switches are limited in how they employ link aggregation (which dynamically manages Ethernet channels): they commonly only support the open-source Link Aggregation Control Protocol (LACP) as their protocol for conducting this task. However, they do support a variety of media for connections, such as Ethernet, fiber, and Fiber Channel over Ethernet (FCoE) cabling. 

<hr />

## 3. <a name="compare">Comparison and Contrast Table</a>

(TODO)

<hr />

## 4. <a name="supplemental">Supplemental Resources</a>

* *[Ubiquiti and Cisco Meraki Overview Guide](https://github.com/chaseofthejungle/unifi-vs-cisco-meraki)*
* *[Intro to Load Balancing Overview Guide](https://github.com/chaseofthejungle/intro-to-load-balancing)*
* *[Intro to Data Center Virtualization](https://github.com/chaseofthejungle/intro-to-data-center-virtualization/)*
