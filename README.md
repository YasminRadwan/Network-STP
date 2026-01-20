# Spanning Tree Protocol (STP) Configuration – Cisco Packet Tracer

## Overview
This project demonstrates the implementation of Spanning Tree Protocol (STP) on Cisco
switches to prevent Layer 2 loops and ensure a loop-free network topology while
maintaining redundancy.

The lab highlights how STP selects the root bridge and blocks redundant paths.

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS
- Spanning Tree Protocol (STP)
- VLANs
- Ethernet Switching
- TCP/IP

---

## Configuration Summary
- STP enabled on switches
- Root Bridge election configured using bridge priority
- Verification of root and non-root ports
- Observation of port states (Forwarding / Blocking)
- Loop prevention validation

---

## Key Concepts Covered
- Layer 2 loop prevention
- Root Bridge election process
- Path cost and bridge priority
- Port roles and states
- Network redundancy and stability

---

## Verification
- Root Bridge successfully elected
- Redundant links placed in blocking state
- No broadcast storms observed
- STP status verified using CLI commands

---

## Files Included
- `STP_Lab.pkt`
- `config.txt`
- `README.md`

---

## How to Use
1. Open the `.pkt` file using Cisco Packet Tracer
2. Access the switch CLI
3. Review STP configuration and status using:
4. Verify root bridge and port states

---

## Author
**Yasmin Radwan**  
Networking & Security Trainee  
CCNA Certified
