# TryHackMe: Packets & Frames

**Date:** 2025-07-24  
**Room Link:** [TryHackMe Room](https://tryhackme.com/room/packetsframes)

---

## 🧠 What I Learned
- **Packets vs Frames**
	- **Packet**: Network layer (Layer 3) data unit
		+ contains IP addresses and routing info
	- **Frame** : Data link layer (Layer 2) data unit
		+ contains MAC addresses and error-checking (FCS)
		+ encapsulates packets for delivery on local networks

- **TCP (Transmission Control Protocol)**
	- Reliable, connection-oriented protocol (Layer 4)
	- Uses the **Three-Way Handshake**:
		+ SYN → SYN/ACK → ACK
		+ ensures connection setup before data transfer
	- Uses **checksums** for error detection

- **UDP (User Datagram Protocol)**
	- Unreliable, connectionless protocol (Layer 4)
		+ no handshake, no delivery guarantee
		+ better for real-time applications like gaming or video calls
	- Faster, but more prone to data loss

- **Ports**
	- Identifiers for specific services running on a host
		+ Example: Port 80 = HTTP, Port 443 = HTTPS
	- Netcat used in the room to test port connectivity (e.g. `nc 8.8.8.8 1234`)
	- Practiced establishing a connection to retrieve a flag

## 🛠️ Tools Used
- TryHackMe interactive TCP/UDP simulation
- Netcat for testing port communication
- Basic command-line interface for port probing

## 💡 Key Takeaways
- Packets and frames operate at different OSI layers with different addressing
- TCP is reliable and stateful; UDP is faster but stateless
- Understanding ports is crucial for identifying and communicating with services
- Hands-on practice helped reinforce theory through real-world simulations


