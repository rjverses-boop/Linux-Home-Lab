# Linux Home Lab 

## Overview
This project is a hands-on Linux home lab built to practice real-world
system administration, networking, and automation skills with an
interview-focused mindset.

The lab uses two Linux virtual machines to simulate a basic server-client
environment and emphasizes troubleshooting, documentation, and clear
technical explanations.

## Lab Architecture
- Hypervisor: VirtualBox
- Server VM: Ubuntu Server
- Client VM: Rocky Linux / Debian
- Networking: Internal network with static and DHCP configurations

[Diagram available in /diagram]

## What I Practiced
- Linux user and group management
- Permissions and ownership
- Managing services with systemd
- Reading and analyzing logs with journalctl
- Static vs DHCP IP addressing
- DNS and hostname resolution
- Firewall configuration (UFW / firewalld)
- Structured troubleshooting
- Automation with Bash and Ansible

## Automation
- Bash scripts for system monitoring
- Ansible playbooks for:
  - User and group creation
  - Package installation
  - Service management
  - Firewall rules

## Why This Project
This lab was intentionally kept small and practical to mirror real IT
environments and build confidence answering interview questions such as:
- How do you troubleshoot a service that won’t start?
- What do you check when a server can’t reach the internet?
- Have you used automation before?

## Lessons Learned
- Most issues are solved by logs and fundamentals
- Methodical troubleshooting beats guesswork
- Automation improves consistency and reliability
