# LAN Topologies

## What is a Network Topology?

A **network topology** refers to the design or layout of a network and describes how devices are connected and communicate with one another.

### Common LAN Topologies

- Star Topology
- Bus Topology
- Ring Topology

---

# Star Topology

## Overview

In a Star Topology, all devices connect to a central networking device such as a:

- Switch
- Hub

All communication between devices passes through the central device.

### Structure

```text
        PC
         |
PC ---- Switch ---- PC
         |
      Printer
```

## Advantages

### Scalability
- Easy to add new devices.
- Suitable for growing networks.

### Reliability
- Failure of one device usually does not affect the rest of the network.

### Easy Management
- Centralized control through the switch or hub.

## Disadvantages

### Higher Cost
- Requires more cabling.
- Requires dedicated networking hardware.

### Increased Maintenance
- Larger networks require more monitoring and maintenance.

### Central Point of Failure
- If the switch or hub fails, all connected devices lose communication.

---

# Bus Topology

## Overview

A Bus Topology uses a single cable known as a **backbone cable**.

All devices share this cable for communication.

### Structure

```text
PC ---- PC ---- PC ---- PC
        |
   Backbone Cable
```

## Advantages

### Cost-Effective
- Requires less cabling.
- Minimal networking hardware required.

### Easy Setup
- Simple design and installation.

## Disadvantages

### Bottlenecks
- All network traffic travels through one cable.
- Performance decreases as traffic increases.

### Difficult Troubleshooting
- Hard to determine which device is causing network issues.

### Single Point of Failure
- If the backbone cable breaks, the entire network becomes unavailable.

---

# Ring Topology

## Overview

A Ring Topology connects devices in a circular loop.

Each device is connected directly to the next device in the ring.

### Structure

```text
PC ---- PC
|        |
|        |
PC ---- PC
```

## How It Works

- Data travels around the ring until it reaches the destination device.
- Devices forward data to the next device in the loop.
- If a device has its own data to send, it sends that data before forwarding received data.

## Advantages

### Less Cabling
- Requires less infrastructure than a star topology.

### Easier Troubleshooting
- Data follows a predictable path.

### Reduced Bottlenecks
- Traffic is distributed around the ring.

## Disadvantages

### Slower Communication
- Data may pass through multiple devices before reaching its destination.

### Network-Wide Failure Risk
- A broken cable or failed device can disrupt the entire network.

---

# What is a Switch?

## Definition

A **Switch** is a networking device that connects multiple devices within a Local Area Network (LAN).

Examples of connected devices:

- Computers
- Printers
- Servers
- IP Phones

## Common Port Configurations

- 4 Ports
- 8 Ports
- 16 Ports
- 24 Ports
- 32 Ports
- 64 Ports

## How a Switch Works

A switch keeps track of which device is connected to each port.

When a packet is received:

- The switch identifies the destination device.
- The packet is forwarded only to the correct port.

### Switch vs Hub

| Switch | Hub |
|----------|----------|
| Sends data only to the target device | Sends data to every connected device |
| More efficient | Less efficient |
| Reduces network traffic | Creates unnecessary traffic |

## Benefits of Switches

- Improved performance
- Reduced network congestion
- Efficient packet delivery
- Better scalability

---

# Network Redundancy

## What is Redundancy?

Redundancy means creating multiple communication paths within a network.

Switches and routers can be connected together to provide backup routes for data.

### Advantages

- Increased reliability
- Reduced downtime
- Alternative communication paths during failures

### Disadvantage

- Packets may travel longer routes.
- Slight reduction in overall performance.

---

# What is a Router?

## Definition

A **Router** is a networking device that connects different networks and forwards data between them.

## Main Responsibilities

- Connect multiple networks.
- Forward data between networks.
- Determine the best path for data transmission.

### Example

```text
Home Network
      |
    Router
      |
   Internet
      |
Company Network
```

---

# Routing

## Definition

**Routing** is the process of determining the path that data takes between networks.

Routers use routing to ensure data reaches the correct destination efficiently.

### Purpose of Routing

- Connect separate networks.
- Deliver data successfully.
- Determine the most appropriate path for network traffic.

---

# Key Takeaways

- A topology defines how devices are connected in a network.
- Star Topology is the most common due to reliability and scalability.
- Bus Topology is inexpensive but suffers from bottlenecks and single points of failure.
- Ring Topology reduces bottlenecks but can fail if one device or cable breaks.
- Switches connect devices within a LAN and efficiently forward data.
- Routers connect different networks and use routing to move data between them.
- Redundancy improves network reliability by providing multiple communication paths.
