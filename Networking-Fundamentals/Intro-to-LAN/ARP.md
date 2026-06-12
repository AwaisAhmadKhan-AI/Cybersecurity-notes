# ARP (Address Resolution Protocol)

## What is ARP?

**ARP (Address Resolution Protocol)** is a network protocol used to map an **IP address** to a **MAC address**.

It allows devices on a network to identify each other using both logical and physical addresses.

---

## Why ARP is Needed

Devices in a network have two key identifiers:

- **IP Address** → Logical address (used for routing)
- **MAC Address** → Physical address (used for actual device identification)

ARP connects these two identifiers so devices can properly communicate.

---

## How ARP Works

Each device maintains a small memory storage called an **ARP cache**.

### ARP Cache
- Stores IP-to-MAC address mappings
- Helps speed up future communications

---

## ARP Communication Process

ARP uses two main messages:

### 1. ARP Request
- Sent as a **broadcast** to the entire network
- Asks:
  > "Who owns this IP address? What is your MAC address?"

All devices receive this request.

---

### 2. ARP Reply
- Only the device with the matching IP responds
- Sends back its MAC address to the requester

---

## Step-by-Step Process

1. Device wants to communicate with another device
2. It checks its ARP cache
3. If MAC address is not found → sends ARP Request
4. Target device responds with ARP Reply
5. MAC address is stored in ARP cache
6. Communication begins using MAC address

---

## Key Idea

ARP allows devices to:
- Discover MAC addresses using IP addresses
- Store mappings for faster future communication
- Enable communication within a local network

---

## Key Takeaway

**ARP is the protocol that links IP addresses with MAC addresses, enabling devices on the same network to find and communicate with each other efficiently.**