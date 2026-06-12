[Introduction-to-LAN-Topologies.md](https://github.com/user-attachments/files/28874454/Introduction-to-LAN-Topologies.md)

LAN Topologies
What is a Network Topology?

A network topology refers to the physical or logical design/layout of a network and how devices are connected to each other.

Common LAN topologies include:

Star Topology
Bus Topology
Ring Topology
1. Star Topology
Overview

In a Star Topology, all devices connect to a central networking device such as a:

Switch
Hub

All communication passes through the central device.

Structure
        PC
         |
PC ---- Switch ---- PC
         |
       Printer
Advantages
Reliable
Failure of one device does not affect others.
Scalable
Easy to add new devices to the network.
Easier Management
Centralized control through a switch or hub.
Disadvantages
Expensive
Requires more cabling.
Requires dedicated networking equipment.
Maintenance Required
Larger networks require more monitoring and maintenance.
Central Point of Failure
If the switch or hub fails, all connected devices lose communication.
2. Bus Topology
Overview

A Bus Topology uses a single cable called a backbone cable.

All devices connect to this shared cable.

Structure
PC ---- PC ---- PC ---- PC
        |
   Backbone Cable
Advantages
Cost-Effective
Requires less cabling.
Easy Setup
Simple network design.
Minimal Hardware
No need for expensive networking devices.
Disadvantages
Network Bottlenecks
All traffic travels through one cable.
Performance decreases as network traffic increases.
Difficult Troubleshooting
Hard to identify which device is causing issues.
Single Point of Failure
If the backbone cable breaks, the entire network fails.
3. Ring Topology
Overview

In a Ring Topology, devices connect directly to each other in a circular loop.

Data travels around the ring until it reaches its destination.

Structure
PC ---- PC
|        |
|        |
PC ---- PC
How It Works
Devices forward data around the ring.
If a device has its own data to send, it sends that first.
Data travels in one direction around the network.
Advantages
Less Cabling
Requires less infrastructure than a star topology.
Easier Troubleshooting
Data follows a predictable path.
Reduced Bottlenecks
Traffic is distributed around the ring.
Disadvantages
Slower Communication
Data may pass through multiple devices before reaching the destination.
Entire Network Failure Risk
A broken cable or failed device can disrupt the entire network.
What is a Switch?
Definition

A Switch is a networking device that connects multiple devices within a LAN.

Examples of connected devices:

Computers
Printers
Servers
IP Phones
Common Port Sizes
4 Ports
8 Ports
16 Ports
24 Ports
32 Ports
64 Ports
How a Switch Works

A switch keeps track of which device is connected to which port.

When receiving a packet:

Switch
Sends data only to the intended device.
Hub
Sends data to every connected device.
Benefits of Switches
Faster communication
Reduced network traffic
Improved efficiency
Better performance than hubs
Switch Redundancy

Switches and routers can be interconnected to create multiple communication paths.

Benefits
Increased Reliability
Alternative paths exist if one connection fails.
Reduced Downtime
Network remains operational during failures.
Trade-Off
Packets may travel longer routes.
Slight reduction in performance.
What is a Router?
Definition

A Router is a networking device that connects different networks and forwards data between them.

Main Function
Connect networks together.
Direct traffic to its destination.
Routing

Routing is the process of determining the path that data takes between networks.

Example
Home Network
      |
    Router
      |
Internet
      |
Company Network

The router ensures that data travels through the correct path to reach its destination.

Key Takeaways
A topology defines how devices are connected in a network.
Star Topology is the most common due to reliability and scalability.
Bus Topology is inexpensive but suffers from bottlenecks and single points of failure.
Ring Topology reduces bottlenecks but can fail if one device or cable breaks.
Switches connect devices within a LAN and forward data efficiently.
