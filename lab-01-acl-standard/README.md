# Lab 01: Standard ACL Configuration

## Objective
Restrict traffic from the 172.10.10.0/24 network (PC0's subnet) so it cannot reach the 172.10.13.0/24 network (PC2's subnet), while allowing all other traffic to pass normally.

## Topology
![topology](screenshots/topology.png)

**Devices:**
- Router0 (2811) — connects Switch0 (Net1), Switch1 (Net2), and Router1 (Net4)
- Router1 (2811) — connects to Router0 and Switch2 (Net3)
- PC0 — 172.10.10.2/16, gateway 172.10.10.1
- PC1 — 172.10.11.2/16, gateway 172.10.11.1
- PC2 — 172.10.13.2/16, gateway 172.10.13.1

## Key Configuration
