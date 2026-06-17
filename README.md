# Kali NetHunter Mobile Lab

## Overview

This project demonstrates a Mobile Penetration Testing Lab built using Kali NetHunter on a rooted Android device. The lab is used for learning networking, security assessment, reconnaissance, enumeration, and penetration testing fundamentals in a controlled environment.

## Device Information

| Component | Details |
|------------|------------|
| Device | OnePlus Nord CE 2 Lite (LE2101) |
| Android Version | Android 14 |
| Root Solution | Magisk 30.7 |
| Environment | Kali NetHunter Rooted |
| Architecture | ARM64 |

## Objectives

- Build a mobile penetration testing environment
- Configure Kali NetHunter on Android
- Verify root access and Linux environment
- Perform network reconnaissance
- Conduct host discovery
- Perform DNS enumeration
- Validate security tools installation
- Create a portable cybersecurity lab

## Tools Used

- Kali NetHunter
- Magisk
- Nmap
- Gobuster
- Nikto
- SQLMap
- Hydra
- NetHunter Terminal
- DNS Utilities

---

# Screenshots

## 1. Root Access Verification

Verified successful root access using Root Checker and Magisk.

## 2. Magisk Root Management

Verified Magisk installation and root management configuration.

## 3. Kali NetHunter Home Screen

Kali NetHunter environment successfully installed and configured.

## 4. Kali Chroot Manager

Verified Kali Linux chroot environment is running correctly.

## 5. Root Shell Verification

Verified root privileges using:

```bash
whoami
uname -a
```

## 6. Network Configuration Analysis

Enumerated active interfaces and IP addressing information.

```bash
hostname -I
ip a
```

## 7. Security Tools Verification

Verified installation of essential penetration testing tools.

```bash
nmap --version
gobuster --version
nikto -Version
sqlmap --version
hydra -h
```

## 8. Network Host Discovery

Discovered active hosts on the local network.

```bash
nmap -sn 172.29.57.0/24
```

## 9. Port Scanning Demonstration

Performed TCP port scanning against a target host.

```bash
nmap 172.29.57.43
```

## 10. DNS Lookup Verification

Validated DNS resolution functionality.

```bash
nslookup google.com
```

## 11. Lab Setup

Physical mobile cybersecurity lab setup using Android device running Kali NetHunter.

---

## Skills Demonstrated

- Linux Administration
- Android Rooting
- Kali NetHunter Configuration
- Network Reconnaissance
- Host Discovery
- Port Scanning
- DNS Enumeration
- Cybersecurity Lab Setup
- Penetration Testing Fundamentals

## Disclaimer

This project was created for educational and authorized security testing purposes only. All testing was performed in a controlled environment.

## Author

Manoj 
Cybersecurity Enthusiast
