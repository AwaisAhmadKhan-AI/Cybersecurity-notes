📘 Ping (ICMP)
1. What is Ping?

Ping is a basic network troubleshooting tool used to test communication between two devices on a network.

It helps determine:

Whether a device is reachable
Whether a network connection exists
How reliable the connection is
How long data takes to travel between devices
2. What is ICMP?

ICMP (Internet Control Message Protocol) is a network protocol used for sending error messages and operational information between devices.

Ping uses ICMP to test connectivity.

3. How Ping Works

Ping works using two ICMP messages:

🔹 ICMP Echo Request
Sent from the source device to the target device.
🔹 ICMP Echo Reply
Sent back by the target device to confirm it received the request.
Process:
Source sends an ICMP Echo Request.
Target receives the request.
Target sends an ICMP Echo Reply.
Source measures the time taken for the round trip.
4. Measuring Response Time

Ping measures the time taken for packets to travel to the target and back.

This time is called:

Round-Trip Time (RTT)

Usually measured in:

Milliseconds (ms)

Example:

Time = 4.16 ms

This means the packet travelled to the target device and back in approximately 4.16 milliseconds.

5. Ping Syntax
Ping an IP Address
ping 192.168.1.254