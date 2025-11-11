# Basic Router and LAN Topology

Router:
- LAN: 192.168.10.1/24
- DHCP: 192.168.10.50-192.168.10.200
- DNS: router or upstream resolver

Server:
- 192.168.10.10/24 static
- HTTP service on port 80

Client:
- DHCP from router

Exercises:
- Verify addressing and gateway.
- Validate DNS resolution.
- Trace route from client to server.
