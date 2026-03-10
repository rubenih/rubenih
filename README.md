# Hi there, I'm Ruben 👋

Welcome to my GitHub profile! I am a Systems & Network enthusiast with a strong focus on Networking and and self-hosted environments. 
I use my home lab as a continuous learning ground to design, deploy, and manage enterprise-grade architectures on a smaller scale.

## My Home Lab Architecture

I manage a fully functional, highly available home data center. My approach prioritizes security (VLAN isolation), automation, and robust monitoring.

* **Hypervisor & Storage:** Proxmox VE, TrueNAS (ZFS storage with hardware passthrough).
* **Networking:** Mikrotik routing, Ubiquiti UniFi Access Points, strict VLAN segmentation (IoT, Guest, Trusted, Management).
* **Containerization:** Docker & Docker Compose, securely exposed via Traefik reverse proxy.
* **Monitoring & Power Management:** Network UPS Tools (NUT) for graceful shutdowns, Home Assistant for hardware telemetry and running my smart home.
* **Documentation as Code:** RackPeek (YAML-based infrastructure documentation) and Microsoft Visio for logical network topologies.

## Tech Stack & Tools

* **Systems:** Linux (Debian/Ubuntu).
* **Networking:** TCP/IP, DNS (AdGuard Home), DHCP, Firewall Rules, VLANs, VPN (WireGuard/DuckDNS).
* **DevOps & IaC:** Git, Docker, Traefik, YAML.
* **IoT & Smart Automation:** Home Assistant, Zigbee2MQTT, ESPHome.

## What I'm currently working on

* Migrating my visual network documentation (Visio) into **Documentation-as-Code** using RackPeek.
* Optimizing my Mikrotik firewall rules to eliminate broadcast noise across VLANs.

## How to reach me

* **LinkedIn:** linkedin.com/in/rubenih
* **Email:** ruben.isa@protonmail.com

---
*Fun fact: I treat my home network like a production environment — if it goes down, I have an automated Telegram bot screaming at me!*
