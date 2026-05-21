# EtherChannel Lab — LACP & PAgP

## Lab Overview
This lab focuses on configuring and verifying EtherChannel using both LACP (Link Aggregation Control Protocol)  and PAgP (Port Aggregation Protocol). You will build two separate topologies to understand the differences between Cisco’s proprietary EtherChannel negotiation protocol and the IEEE standard protocol.

The lab also includes VLAN configuration, trunking, port security, and switch hardening practices.

---

# Lab Objectives

- Configure EtherChannel using LACP
- Configure EtherChannel using PAgP
- Configure VLANs across switches
- Configure trunk links
- Disable DTP on trunk interfaces
- Configure port security on access ports
- Shutdown unused switch ports
---

# Topology 1 — LACP
This topology demonstrates EtherChannel negotiation using **LACP (802.3ad)**.
<img width="782" height="361" alt="image" src="https://github.com/user-attachments/assets/69e84367-b4e1-4379-b6dd-e9d7c8652d1e" />

---

## Tasks
<img width="702" height="557" alt="image" src="https://github.com/user-attachments/assets/08ee3ac2-61d8-4968-bfa3-499705f1feae" />


### Verification
<img width="535" height="412" alt="image" src="https://github.com/user-attachments/assets/9ef92723-1f7e-4448-bb33-8af868419f86" />

---

# Topology 2 — PAgP

## Purpose
This topology demonstrates EtherChannel negotiation using **PAgP**, Cisco’s proprietary aggregation protocol.

---

## Tasks

### Basic Configuration
- [ ] Change hostnames on all switches
- [ ] Configure management IP addresses
- [ ] Configure switch default gateways

---

### VLAN Configuration
- [ ] Create required VLANs
- [ ] Assign VLAN names
- [ ] Configure access ports

---

### Trunk Configuration
- [ ] Configure static trunk links
- [ ] Assign native VLAN
- [ ] Disable DTP negotiation

---

### PAgP EtherChannel
- [ ] Configure EtherChannel using PAgP
- [ ] Bundle physical interfaces into a Port-Channel
- [ ] Configure the Port-Channel as a trunk
- [ ] Verify proper negotiation and operation

---

### Security Tasks
- [ ] Configure port security on designated interfaces
- [ ] Configure violation mode as restrict
- [ ] Shutdown unused switch ports
- [ ] Assign unused ports to an unused VLAN

---

### Verification
- [ ] Verify Port-Channel operation
- [ ] Verify trunking status
- [ ] Verify VLAN communication
- [ ] Ensure full connectivity across devices

---

# Skills Practiced

- EtherChannel Configuration
- LACP Configuration
- PAgP Configuration
- VLAN Configuration
- Trunking
- Port Security
- Switch Hardening
- Layer 2 Troubleshooting
- Connectivity Verification

---

# Troubleshooting Practice

- [ ] Troubleshoot EtherChannel mismatches
- [ ] Identify incorrect negotiation modes
- [ ] Troubleshoot trunking problems
- [ ] Verify native VLAN consistency
- [ ] Resolve port-security violations

---

# Expected Outcome

By the end of this lab:
- Both EtherChannels should be operational
- VLAN traffic should pass successfully across trunks
- Port security should function correctly
- Unused interfaces should be secured
- All devices should have full connectivity

---
