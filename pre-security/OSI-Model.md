# TryHackMe: OSI Model Room

**Date:** 2025-07-24  
**Room Link:** [TryHackMe Room](https://tryhackme.com/room/osimodelzi)

---

## 🧠 What I learned 

In this room, I learned about the OSI (Open Systems Interconnection) Model, which is a "conceptual framework" used to understand and standardize how different networking protocols interact in a layered architecture. It consists of 7 layers, each with specific functions:

    Layer 7 – Application

        Interface for end-user processes (e.g., HTTP, FTP, DNS).

        Deals with network services directly used by applications.

    Layer 6 – Presentation

        Translates, encrypts, or compresses data (e.g., SSL/TLS, JPEG, ASCII).

        Ensures data is in a usable format.

    Layer 5 – Session

        Manages sessions between devices.

        Handles setup, maintenance, and termination of connections.

    Layer 4 – Transport

        Provides reliable or unreliable delivery (e.g., TCP vs. UDP).

        Responsible for flow control and error correction.

    Layer 3 – Network

        Determines routing of data (e.g., IP, ICMP).

        Handles logical addressing and path determination.

    Layer 2 – Data Link

        Transfers data between nodes on the same network (e.g., MAC, ARP).

        Detects and possibly corrects errors that may occur in Layer 1.

    Layer 1 – Physical

        Deals with physical connection (cables, switches, voltage, etc.).

        Transmits raw bit streams over the physical medium.

🛠️ Key Takeaways:

    Each layer serves the one above it and is served by the one below it.

    Protocols operate at specific layers, helping identify where issues might occur.

    Understanding the OSI model helps in troubleshooting network issues, designing networks, and understanding how cyber attacks work at various levels.

🔐 This foundational knowledge is essential for anyone working in networking or cybersecurity, as it clarifies how data travels through a system and where vulnerabilities might exist.
