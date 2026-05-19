Lab 06: Full Session Analysis

Objective
To analyze complete network sessions and understand end-to-end communication.

Tool Used
- Wireshark

Steps Performed
- Captured traffic during browsing activity
- Used “Follow TCP Stream”
- Analyzed full request-response communication
- Filtered specific TCP streams

Filters Used
- tcp.stream eq 10

Observations
- A session contains complete communication between client and server.
- TCP streams allow reconstruction of full conversations.
- Data flows in both directions between endpoints.

Key Learnings
- Session-based communication analysis
- TCP stream reconstruction
- Understanding full network conversations
