# Small Office Network with DHCP and Routing

**Project Overview**

This project focuses on designing and implementing a **Small Office Network** that dynamically assigns **IP addresses using DHCP** and ensures efficient routing between different network segments. The network is built using multiple routing protocols: **EIGRP, OSPF, Static routing, and RIP**.

**Objectives**

  **1.**  Implement a **dynamic IP** allocation system using **DHCP**.

  **2.** Configure **multi-protocol routing** (EIGRP, OSPF, RIP, and Static Routing).

  **3.** Ensure **seamless connectivity** and **efficient resource management**.

  **4.** Demonstrate **network scalability** with proper subnetting and routing.

**Technologies Used**

 **1.** **Cisco Packet Tracer** – Network simulation and configuration.

 **2.** **Routing Protocols:**

   **i.** **EIGRP** – Internal dynamic routing.

   **ii.** **OSPF** – Fast convergence and scalability.

   **iii.** **RIP (v2)** – Distance-vector routing with subnetting.

   **iv.** **Static Routing** – Manually configured routes.

**3.** **DHCP** – Dynamic Host Configuration Protocol for IP allocation.

Subnetting – Efficient IP address allocation.

Command-Line Interface (CLI) – Configuring routers and switches.

ACL (Access Control Lists) – Network access restrictions.

Network Design & Implementation

The office is divided into three departments:

Management (16 IPs, using EIGRP internally).

Support (76 IPs, using RIP internally).

Sales (156 IPs, using Static Routing internally).

Each department has a dedicated server for data storage, with the Management department having two servers (one for backups).

Inter-department communication is handled using OSPF.

DHCP ensures automatic IP assignment for ease of network expansion.

ACLs are used to restrict access to servers based on department permissions.

Testing & Results

Ping & Traceroute were used to verify connectivity.

Department-specific routing was tested to ensure internal communication.

Access restrictions were validated through ACL configurations.

Challenges & Learnings

Routing Protocol Compatibility – Initially, connecting different routing protocols was challenging, but route redistribution resolved the issue.

RIP Limitations – RIPv2 was used to support subnetting.

Subnetting Complexity – Careful planning was required to allocate IPs efficiently.

Conclusion & Future Enhancements

The project successfully demonstrated multi-protocol routing and dynamic IP management in a small office network. Future improvements could include:

Implementing OSPF authentication for security.

Exploring QoS (Quality of Service) to optimize traffic flow.

Enhancing network security measures with firewall rules.

Author

Muhammad Omer

Roll Number: 22I-0921

This project was developed as part of NUCES-FAST coursework in Cisco Networking.

