# Metasploitable2 Lab Practice

Safe penetration testing lab using **Metasploitable2** and **Kali Linux** in VirtualBox.

## Setup
- VirtualBox installed
- Two VMs:
  - Kali Linux (attacker)
  - Metasploitable2 (vulnerable target)
- Host-Only Networking (isolated, no internet)

## Steps Performed
1. Checked connectivity with `ping`.
2. Scanned Metasploitable2 using `nmap -sV`.
3. Found open ports: FTP, SSH, Telnet, MySQL, Samba, HTTP, etc.
4. Used Metasploit to exploit **vsftpd 2.3.4 backdoor**.
5. Obtained root shell safely.
6. Exited the session.

## Learning Outcome
- How to scan networks
- Identify vulnerable services
- Exploit known vulnerabilities safely in a lab environment

> ⚠️ This is a lab environment. Never expose Metasploitable2 to the internet.
