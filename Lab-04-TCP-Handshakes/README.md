Lab 04: TCP Handshake Analysis

Objective
To understand how TCP connections are established using the three-way handshake.

Tool Used
- Wireshark

Steps Performed
- Captured TCP traffic
- Identified SYN, SYN-ACK, and ACK packets
- Analyzed connection establishment process

Filters Used
- tcp
- tcp.flags.syn == 1

Observations
- TCP uses a three-way handshake to establish connections.
- SYN initiates connection request.
- SYN-ACK acknowledges request.
- ACK completes connection setup.

Key Learnings
- TCP connection lifecycle
- Reliable communication setup
- Importance of handshake mechanism
