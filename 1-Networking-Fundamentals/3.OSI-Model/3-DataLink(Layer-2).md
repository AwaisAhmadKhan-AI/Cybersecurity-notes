# OSI Layer 2 - Data Link Layer

## Overview
The **Data Link Layer** handles **MAC (physical) addressing** and prepares data for transmission on a local network.

---

## Main Role
- Takes data from the Network Layer
- Adds **MAC address (physical address)**
- Ensures data reaches the correct device inside the same network

---

## MAC Address

- A **unique hardware address** of a device
- Stored in the **Network Interface Card (NIC)**
- Assigned by the manufacturer
- Usually permanent (can be spoofed but not easily changed)

Example:
- `00:1A:2B:3C:4D:5E`

---

## How It Works

1. Data comes from Network Layer (IP address included)
2. Data Link Layer adds MAC address
3. Data is sent to the correct device on the local network

---

## Extra Responsibility

- Formats data into **frames** so it can be transmitted properly

---

## Key Takeaway

The **Data Link Layer** uses **MAC addresses** to deliver data to the correct device within a local network and prepares data for transmission.