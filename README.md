# M700 setup
- Proxmox VE 9 / version Trixie
- Used ext4
- Hostname: main.pigeon.node
- IP assigned - 192.168.1.10/24
- apt was not working, had to swap the license under /etc/apt/sources.list.d/
- Enabled: false for pve-enterprise.sources and ceph.sources, to force tapt to use pve-no-subscription.sources as the source

# Archer C7
- 192.168.1.1
- DHCP range - Start 100, Limit 100
