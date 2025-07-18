# Personal-Homelab-Environment-
This is my personal homelab! It is currently a work-in-progress (WIP) as I will continually upgrade it. 

# Utilities 
- **Rackmate T1 (8U)** (Server Rack) 
- **Dell Optiplex 3060** (Will run Proxmox VE, a free hypervisor installed from a bootable USB. Used to create virtual machines (VMs) and LXC containers for sandboxed environments like malware testing or OS/application experimentation. Managed via a browser-based web UI over your local network.)
- **Dell Optiplex 3070** (Also running Proxmox VE. This node will host Docker contaienrs or VMs for services like a media server (Jellyfin), game servers (TBD), or self-hosted tools (e.g., Bookstack, Portainer). Network services and RDP access will be enabled for remote access from other devices on LAN.)
- **KVM Switch** (Enables local control of both Optiplexes using one monitor, keyboard, and mouse. You'll physically connect the KVM to each Optiplex via HDMI/DisplayPort and USB, allowing you to toggle between machines during OS installations and maintenance.)
- Managed PoE 8-Port Switch
(Used as your primary network switch, connecting all devices via Cat6 Ethernet cables. It supports VLAN configuration, port isolation, and traffic monitoring via its web interface. Although PoE is not needed yet, it prepares myself for future PoE-capable devices like IP cameras or Raspberry Pi with PoE HATs.)

[Image IMG_9765](https://github.com/user-attachments/assets/9d9d35b0-088c-46b1-b04b-df4b2ac576e2)]) 
