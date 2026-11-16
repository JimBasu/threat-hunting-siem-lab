# threat-hunting-siem-lab
📌 Project Overview

This project is a localized, isolated virtual cyber range designed to simulate cyber attacks and analyze the resulting endpoint telemetry. By building a controlled environment, I am bridging theoretical cybersecurity concepts with hands-on practice in log generation, threat detection, and incident response.

🏗️ Architecture & Tech Stack

Host Hardware: Dell Laptop (Intel Core i5, 10th Gen) / Windows OS

Hypervisor: VMware Workstation

Attacker Machine: Kali Linux (amd64)

Victim Machine: Windows 11 (x64)

Network Configuration: Private, isolated Host-Only network (VMnet2) to ensure safe, localized attack simulations without exposing the physical host.
🚀 Current Progress

[x] Hypervisor installation and configuration.

[x] Windows 11 VM deployment (baseline established).

[x] Kali Linux VM deployment and package updates.

[x] Network isolation configured (Host-Only VMnet2).

[ ] Install and configure Microsoft Sysinternals (Sysmon) on Windows 11 for verbose logging.

[ ] Connect endpoint telemetry to a SIEM (e.g., Microsoft Sentinel).

[ ] Execute initial attack simulations (e.g., Nmap scanning, brute-force attempts).

[ ] Document resulting Windows Event IDs and create detection playbooks.

💡 Key Learnings

(I will update this section as the project progresses, documenting challenges overcome, such as troubleshooting UEFI network boot sequences and managing ISO architecture compatibility.)

<img width="602" height="310" alt="Kali linux VM screenshot" src="https://github.com/user-attachments/assets/33a05ec7-344d-44e8-bc9c-99101c5b45a4" />
