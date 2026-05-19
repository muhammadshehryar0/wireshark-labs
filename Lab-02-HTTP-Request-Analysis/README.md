Lab 02: HTTP Request Analysis

Objective
To analyze HTTP GET and POST requests and understand client-server communication.

Tool Used
- Wireshark

Steps Performed
- Captured network traffic
- Filtered HTTP packets
- Observed GET requests during browsing
- Inspected packet details

Filters Used
- http 
- http.request.method == "GET"

Observations
- GET requests are used to request data from a server.
- HTTP headers contain useful information like user-agent and host.
- Each request gets a response from the server.

Key Learnings
- HTTP request structure
- Client-server communication
- Understanding web traffic behavior
