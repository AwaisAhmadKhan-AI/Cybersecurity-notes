# What is the OSI Model?

## Introduction

The **OSI Model (Open Systems Interconnection Model)** is a standardized framework used in networking to explain how devices communicate with each other over a network.

It defines how data is:
- Sent
- Received
- Processed
- Interpreted

between networked devices.

---

## Why is the OSI Model Important?

The OSI Model provides a common set of rules that all network devices can follow.

### Benefits

- Standardizes network communication
- Allows different devices and systems to communicate
- Simplifies network troubleshooting
- Helps understand how data moves across a network

Because devices follow the same model, they can communicate even if they have different hardware, operating systems, or manufacturers.

---

## The 7 Layers of the OSI Model

The OSI Model consists of **7 layers**, organized from **Layer 7 (highest)** to **Layer 1 (lowest)**.

| Layer | Name |
|---------|---------|
| 7 | Application |
| 6 | Presentation |
| 5 | Session |
| 4 | Transport |
| 3 | Network |
| 2 | Data Link |
| 1 | Physical |

---

## How Data Travels Through the OSI Model

When data is sent across a network:

1. Data moves through the OSI layers.
2. Each layer performs a specific task.
3. Additional information is added at each layer.
4. The data is transmitted across the network.
5. The receiving device processes the data through the layers in reverse order.

---

## Encapsulation

### Definition

**Encapsulation** is the process of adding information to data as it passes through each OSI layer before being transmitted.

Each layer adds its own information to help:
- Route data
- Deliver data
- Interpret data correctly

The receiving device removes this information layer by layer until the original data is recovered.

---

## Key Concepts

- OSI stands for **Open Systems Interconnection**.
- The OSI Model is a framework for network communication.
- It consists of **7 layers**.
- Each layer has specific responsibilities.
- Devices can communicate even if they use different technologies.
- Data is processed through a method called **encapsulation**.

---

## Key Takeaway

The **OSI Model** is a seven-layer framework that standardizes how devices communicate over networks. It ensures interoperability between different systems and uses **encapsulation** to prepare data for transmission.