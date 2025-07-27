# TryHackMe: Extending Your Network

**Date:** 2025‑07‑27  
**Room Link:** [TryHackMe Room](https://tryhackme.com/room/extendingyournetwork)

---

## 🧠 What I Learned
- **Port Forwarding**
	- Opens specific ports on a **router** to expose internal services (e.g. web server) to the internet
	- Allows external devices to access services running behind NAT/firewalls

- **Firewalls 101**
	- Operate at OSI **Layer 3 (Network)** and **Layer 4 (Transport)**
	- **Stateful firewall**: inspects full connections
	- **Stateless firewall**: inspects individual packets only

- **Practical Firewall Configuration**
	- Lab scenario: block attacker IP from accessing web server port 80
	- Result: flag earned once the firewall rule is correctly applied
	- Flag: `THM{FIREWALLS_RULE}`

- **VPN Basics**
	- Understanding VPN technologies:
		+ **PPP** – encrypts and authenticates data only  
		+ **PPTP** – uses PPP but provides weaker encryption  
		+ **IPSec** – uses IP framework for encryption and authentication
	- Q&A:
		+ PPP encrypts/authenticates data  
		+ IPSec leverages IP-based architecture

- **LAN Networking Devices**
	- **Router** — performs **routing**
	- **Switches** — operate at **Layer 2 and Layer 3**
	- Q&A:
		+ Router’s verb = *routing*  
		+ Switch layers = Layer 2, Layer 3

- **Network Simulator – Practical**
	- Simulated packet journey from computer 1 to computer 3
	- log shows handshake steps (5 entries) and final delivery
	- Flag from simulator: `THM{YOU’VE_GOT_DATA}`
	- Handshake count: **5**

## 🛠️ Tools Used
- TryHackMe interactive simulation environment (web-based)
- Internal firewall configuration UI
- Network simulation GUI showing packet logs

## 💡 Key Takeaways
- Port forwarding is essential for exposing internal services to external networks
- Firewalls and their behavior (stateful vs stateless) impact how traffic is filtered
- VPN technologies offer varying levels of encryption and authentication
- Understanding core LAN devices and their OSI operation layers helps clarify network architecture
- Visual packet logs reinforce understanding of routing, ARP, and TCP handshake mechanics


