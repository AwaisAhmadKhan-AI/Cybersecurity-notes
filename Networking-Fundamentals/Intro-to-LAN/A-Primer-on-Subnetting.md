# A Primer on Subnetting

## What is Subnetting?

Subnetting is the process of **splitting a large network into smaller networks (subnets)**.

Think of a network like a cake:
- The whole cake represents the network
- Each slice represents a subnet
- Subnetting is deciding how to divide those slices

It helps control how network resources are distributed.

---

## Why Subnetting is Needed

In real environments like businesses, different departments exist:

- Accounting
- Finance
- Human Resources

Each department needs its own communication space in the network. Subnetting helps network administrators logically separate and manage these sections.

---

## How Subnetting Works

Subnetting works by dividing the number of available hosts in a network using a **subnet mask**.

---

## IP Addresses and Subnet Masks

An IP address consists of **4 octets (32 bits)**:

```
192.168.1.100
```

A subnet mask is also a 32-bit number in the same format:

```
255.255.255.0
```

Both IP addresses and subnet masks work together to define:
- Network size
- Host range
- Network boundaries

---

## Types of IP Address Roles in Subnetting

Within a subnet, IP addresses serve three main purposes:

### 1. Network Address
- Identifies the **start of the network**
- Represents the network itself

**Example:**
- IP: `192.168.1.100`
- Network: `192.168.1.0`

---

### 2. Host Address
- Identifies **individual devices** in the network
- Assigned to PCs, printers, cameras, etc.

**Example:**
- `192.168.1.100`

---

### 3. Default Gateway
- Special IP address used to send traffic **outside the network**
- Acts as a bridge between local network and other networks (like the Internet)

**Example:**
- `192.168.1.254`

Common usage:
- Usually first or last usable IP in the subnet

---

## Small vs Large Networks

### Home Networks
- Usually only **one subnet**
- Typically supports up to 254 devices
- Simple structure

### Business Networks
- Multiple subnets required
- Thousands of devices may exist:
  - PCs
  - Printers
  - Cameras
  - Sensors

Subnetting becomes essential for organization and control.

---

## Benefits of Subnetting

### 1. Efficiency
- Better use of IP address space

### 2. Security
- Separates sensitive networks from public or less secure ones

### 3. Control
- Administrators can manage traffic and access more effectively

---

## Real-World Example (Cafe Network)

A café may use two separate networks:

### Internal Network
- Employees
- Cash registers
- Business systems

### Public Network
- Customer Wi-Fi hotspot

Subnetting keeps these networks separate while still allowing both to connect to the internet.

---

## Key Takeaway

Subnetting is a way of dividing a large network into smaller, manageable parts to improve **efficiency, security, and control**.