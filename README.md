# OSPF-Dynamic-Routing-Lab
CCNA OSPF Dynamic Routing Lab using Cisco Packet Tracer. Includes step-by-step configuration, ping tests, and network topology.

## Objective
- Learn and implement OSPF dynamic routing across multiple area networks.
- Verify connectivity using ping and troubleshooting techniques.

## Tools
- Cisco Packet Tracer
- Microsoft Word (documentation)
- Screenshots / Images for topology and ping tests

## Commands Used
- router ospf [AS no.]
- network [ip address] [wild card mask] area
- show ip route
- ping

## Testing & Verification
- Ping tests between routers to confirm connectivity.
- Show ip route output confirms correct dynamic routing.

## Files
- OSPF Lab.pkt → Packet Tracer file
- OSPF Lab Documentation.pdf → Step-by-step guide

## Observations 
- All OSPF neighbors were successfully established in each area.
- Area 0 backbone effectively connected all other areas.
- Routes propagated correctly between different OSPF areas.
- Ping tests confirmed full connectivity across the network.
- No packet loss observed during connectivity verification.

## Documentation
- The complete step-by-step configuration and observations are available in the PDF below:
[OSPF Lab Documentation.pdf](https://github.com/user-attachments/files/22921057/OSPF.Lab.Documentation.pdf)

## Topology Image

<img width="1916" height="1008" alt="Image" src="https://github.com/user-attachments/assets/9ab20f46-e8b7-4ea0-bb39-151b3eadf1d0" />

