## configuration

- eth0 (wan0): myrepublic (direct dhcp)
- eth1 (no vlan): 10.0.0.0/24 (to wan1)
- eth1 (vlan 100): 10.2.0.0/24 (to wan0)
- eth1 (vlan 200): 10.3.0.0/24 (to wan1)
- eth2 (wan1): biznet (from router)
