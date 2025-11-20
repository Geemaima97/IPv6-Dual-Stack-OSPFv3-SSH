# IPv6 Dual-Stack + OSPFv3 + SSH

## Network Topology
<img width="472" height="356" alt="IPv6 Dual-Stack + OSPFv3 + SSH" src="https://github.com/user-attachments/assets/cda91c03-83d3-4812-b2e6-a418952172c8" />

## Objective
Configure both IPv4 and IPv6 addresses on routers, enable OSPFv2 and OSPFv3 in area 0, and secure router management using SSH. Verify routing for both protocols.

### Skills Learned
- Configuring dual-stack IPv4/IPv6 addressing.
- OSPFv2 and OSPFv3 configuration and verification.
- Enabling IPv6 unicast routing.
- Secure management using SSH v2 with local authentication.

### Tools Used
- Routers R1 and R2.
- Cisco Packet Tracer / GNS3.
- Commands: `show ip ospf neighbor`, `show ipv6 ospf neighbor`, SSH test.

## Steps
1. Assign IPv4 and IPv6 addresses to all router interfaces.
2. Enable OSPFv2 for IPv4 and OSPFv3 for IPv6.
3. Verify neighbor relationships for both protocols.
4. Enable SSH v2 with local admin credentials.
5. Test SSH login from a connected PC.
6. Confirm IPv6 routing with `ping` and `show ipv6 route`.


