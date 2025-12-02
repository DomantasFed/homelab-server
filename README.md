# homelab-server
SFF Proxmox server environment for multi-VM labs, Linux development, and cybersecurity research.

This repository will document the build, configuration, and ongoing development of my personal homelab environment. The goal is to create a environment to learn linux, virtualization, network engineering, automation, cybersecurity, and system administration through a lab setup that mimicks real-world scenarios.

***

**HARDWARE**
- CPU: Ryzen 7 5700G
- RAM: 32GB DDR4 (planned future upgrade to 64GB)
-GPU: GTX 1070 (will be used for GPU passthrough)
- MOBO: ASRock B550 ITX 
- CASE: NR200P V2 
- PSU: Cooler Master V850 SFX
- CPU COOL: ID-Cooling IS-67-XT low-profile
- SSD: 2TB NVMe SSD (potential upgrade to 4 tb with SATA ssd)

**Note**: This is a mini-ITX build which means these components are quite smaller than typical computer builds. The motherboard and power supply are all built to spec so that they all fit in the more smaller case. The Hardware installation page will contain all of the installation steps for all of the specified parts above.

*** 

**GOALS**
1. Learn Linux inside out
2. Utilize tailscale to connect devices for collaboration
3. Create network automation tools
4. Run multipe VMs using Proxmox as the native OS
5. Build an Active Direcotry domain for Windows Server labs
6. Set up pentesting environments using Kali + vulnerable VMs
7. Perform GPU workloads (ML, computer vision, Hashcat)
8. Document everything professionaly

**Note**: This build will be used as a learning and experimentation environmet. I will setup Proxmox as the main native OS and run VMs for different purposes as listed above. Tailscale VPN will allow proxmox and the VMs to reside in the same tailnet. This will allow for collaborators to ssh easily and experiment on the server themselves. The goals themselves could evolve over time as interests deviate as time goes. Though, the core goals will be implemented on the setup.

***

**TECHNOLOGIES**
- Proxmox VE
- Ubuntu Server
- Docker & Containerization
- Windows Server + AD DS
- Kali Linux
- Tailscale remote access
- Python automation
- Github documentation workflows

**Note**: These technologies will grow over time















