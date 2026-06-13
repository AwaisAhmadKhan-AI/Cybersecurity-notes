# DHCP (Dynamic Host Configuration Protocol)

## What is DHCP?

**DHCP (Dynamic Host Configuration Protocol)** is a network protocol used to automatically assign IP addresses to devices on a network.

Instead of manually setting IP addresses, DHCP handles this process automatically.

---

## Why DHCP is Used

Without DHCP:
- IP addresses must be configured manually
- High chance of errors and conflicts
- Difficult to manage large networks

With DHCP:
- Automatic IP assignment
- Easy network management
- Efficient device onboarding

---

## How DHCP Works (DORA Process)

When a device connects to a network, it follows a **4-step process** called DORA:

---

### 1. DHCP Discover
- Device sends a broadcast message
- It asks:
  > "Is there a DHCP server available?"

---

### 2. DHCP Offer
- DHCP server responds
- It offers an available IP address to the device

---

### 3. DHCP Request
- Device responds back
- It accepts the offered IP address

---

### 4. DHCP ACK (Acknowledgement)
- DHCP server confirms the assignment
- Device is now allowed to use the IP address

---

## Step-by-Step Summary

1. Device connects to network
2. Sends DHCP Discover
3. Receives DHCP Offer
4. Sends DHCP Request
5. Receives DHCP ACK
6. Device starts using assigned IP address

---

## Key Takeaway

**DHCP is the system that automatically assigns IP addresses to devices using a structured 4-step process (DORA), making network management simple and efficient.**