# OSI Layer 4 - Transport Layer

## Overview
The **Transport Layer** is responsible for delivering data between devices reliably or quickly, depending on the protocol used.

It decides **how data should be sent** across the network.

---

## Main Role
- Breaks data into smaller pieces (packets)
- Sends data between devices
- Ensures correct delivery (depending on protocol)
- Chooses between **TCP** or **UDP**

---

# TCP (Transmission Control Protocol)

## What is TCP?
TCP is a **reliable and connection-based protocol**.

It ensures data is:
- Sent correctly
- Received completely
- In the correct order

---

## How TCP Works
- Creates a stable connection between devices
- Keeps the connection active during transmission
- Checks for errors
- Re-sends missing data if needed
- Reassembles data in correct order

---

## Advantages of TCP
- Very reliable
- Ensures data is complete and correct
- Maintains order of packets
- Good for important data transfer

---

## Disadvantages of TCP
- Slower than UDP
- Uses more resources
- Requires continuous connection
- Can cause delays if data is lost

---

## When TCP is Used
- Web browsing
- File downloads/uploads
- Email sending

👉 Used when **accuracy is more important than speed**

---

# UDP (User Datagram Protocol)

## What is UDP?
UDP is a **fast but unreliable protocol**.

It sends data without checking if it arrives correctly.

---

## How UDP Works
- Sends data without establishing a connection
- No error checking
- No confirmation of delivery
- No reordering of packets

---

## Advantages of UDP
- Very fast
- Low overhead
- Good for real-time communication
- Flexible for developers

---

## Disadvantages of UDP
- No guarantee of delivery
- Packets may be lost
- No order control
- Poor performance on unstable networks

---

## When UDP is Used
- Video streaming
- Online gaming
- Voice calls
- Device discovery (ARP, DHCP)

👉 Used when **speed is more important than accuracy**

---

# TCP vs UDP (Simple Comparison)

| TCP | UDP |
|-----|-----|
| Reliable | Unreliable |
| Slower | Faster |
| Connection-based | Connectionless |
| Error checking | No error checking |
| Ordered data | No order guarantee |

---

## Key Takeaway

The **Transport Layer (Layer 4)** controls how data is delivered:

- **TCP** = slow but reliable
- **UDP** = fast but not guaranteed

It chooses the right method depending on the need for speed or accuracy.