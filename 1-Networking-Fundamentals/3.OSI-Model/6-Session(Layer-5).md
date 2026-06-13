# OSI Layer 5 - Session Layer

## Overview
The **Session Layer** is responsible for creating, managing, and ending communication sessions between two devices.

It acts like a **conversation manager** between computers.

---

## Main Role
- Establishes a connection between devices
- Maintains the connection during communication
- Ends the connection when communication is finished or lost

---

## What is a Session?

A **session** is an active connection between two devices.

- When communication starts → session is created
- While communication continues → session stays active
- When communication ends → session is closed

---

## Responsibilities of the Session Layer

### 1. Session Establishment
- Creates a connection between devices before data transfer begins

### 2. Session Maintenance
- Keeps the connection alive during communication

### 3. Session Termination
- Closes the connection when:
  - Communication ends
  - Connection is idle for too long
  - Connection is lost

---

## Checkpoints

The Session Layer can create **checkpoints** during data transfer:

- If connection fails, only the data after the last checkpoint is resent
- This saves time and bandwidth

---

## Key Characteristics

- Each session is **unique**
- Data cannot move across multiple sessions
- Only one session handles a specific communication flow

---

## Key Takeaway

The **Session Layer (Layer 5)** manages connections between devices by creating, maintaining, and closing sessions, and improves efficiency using checkpoints during data transfer.