# Kali NetHunter Mobile Lab

## Overview

This project demonstrates a Mobile Penetration Testing Lab built using Kali NetHunter on a rooted Android device. The lab is designed for learning Linux administration, networking, security assessment, reconnaissance, enumeration, and penetration testing fundamentals in a controlled environment.

---

## Device Information

| Component | Details |
|------------|------------|
| Device | OnePlus Nord CE 2 Lite (LE2101) |
| Android Version | Android 14 |
| Root Solution | Magisk 30.7 |
| Environment | Kali NetHunter (Rooted) |
| Architecture | ARM64 |

---

## Objectives

- Build a portable penetration testing environment
- Configure Kali NetHunter on Android
- Verify root access and Linux environment
- Perform network reconnaissance
- Conduct host discovery
- Validate DNS functionality
- Verify security tool installation
- Create a mobile cybersecurity lab

---

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

# Project Demonstration

## 1. Root Access Verification

Verified successful root access using Root Checker.

![Root Access Verification](screenshots/1-root-access-verification.jpg)

---

## 2. Magisk Root Management

Verified Magisk installation and root management configuration.

![Magisk Root Management](screenshots/2-magisk-root-management.jpg)

---

## 3. Kali NetHunter Environment

Successfully installed and configured Kali NetHunter on Android.

![Kali NetHunter Environment](screenshots/3-kali-nethunter-environment.jpg)

---

## 4. Kali Chroot Manager Running

Verified Kali Linux chroot environment is running correctly.

![Kali Chroot Manager Running](screenshots/4-kali-chroot-manager-running.jpg)

---

## 5. Root Shell Verification

Verified root privileges inside Kali NetHunter.

### Commands Used

```bash
whoami
uname -a
```

![Root Shell Verification](screenshots/5-root-shell-verification.jpg)

---

## 6. Network Configuration Analysis

Enumerated active interfaces and IP addressing information.

### Commands Used

```bash
hostname -I
ip a
```

![Network Configuration Analysis](screenshots/6-network-configuration-analysis.jpg)

---

## 7. Installed Security Tools Verification

Verified installation of essential penetration testing tools.

### Commands Used

```bash
nmap --version
gobuster --version
nikto -Version
sqlmap --version
hydra -h
```

![Installed Security Tools](screenshots/7-installed-security-tools.jpg)

---

## 8. Network Host Discovery

Discovered active hosts on the local network.

### Command Used

```bash
nmap -sn 172.29.57.0/24
```

![Network Host Discovery](screenshots/8-network-host-discovery.jpg)

---

## 9. TCP Port Scan Demonstration

Performed TCP port scanning against a target host.

### Command Used

```bash
nmap 172.29.57.43
```

![TCP Port Scan](screenshots/9-tcp-port-scan.jpg)

---

## 10. DNS Lookup Verification

Validated DNS resolution functionality.

### Command Used

```bash
nslookup google.com
```

![DNS Lookup Verification](screenshots/10-dns-lookup-verification.jpg)

---

## 11. Kali NetHunter Lab Environment

Physical mobile cybersecurity lab setup using Android device running Kali NetHunter.

![Kali NetHunter Lab Environment](screenshots/11-kali-nethunter-lab-environment.jpg)

---

# Skills Demonstrated

- Linux Administration
- Android Rooting
- Kali NetHunter Configuration
- Mobile Security Lab Deployment
- Network Reconnaissance
- Host Discovery
- Port Scanning
- DNS Enumeration
- Security Tool Validation
- Penetration Testing Fundamentals

---

# Key Learning Outcomes

- Successfully deployed Kali NetHunter on a rooted Android device.
- Established a portable penetration testing environment.
- Verified root access and Linux subsystem functionality.
- Performed network reconnaissance and host discovery.
- Conducted TCP port scanning exercises.
- Validated DNS resolution capabilities.
- Demonstrated usage of common penetration testing tools.

---

## Project Structure

```text
Kali-NetHunter-Mobile-Lab/
│
├── README.md
│
└── screenshots/
    ├── 1-root-access-verification.jpg
    ├── 2-magisk-root-management.jpg
    ├── 3-kali-nethunter-environment.jpg
    ├── 4-kali-chroot-manager-running.jpg
    ├── 5-root-shell-verification.jpg
    ├── 6-network-configuration-analysis.jpg
    ├── 7-installed-security-tools.jpg
    ├── 8-network-host-discovery.jpg
    ├── 9-tcp-port-scan.jpg
    ├── 10-dns-lookup-verification.jpg
    └── 11-kali-nethunter-lab-environment.jpg
```

---

## Disclaimer

This project was created strictly for educational purposes and authorized security testing in a controlled environment. All activities were conducted on owned devices and networks.

---

## Author

**Manoj**

Cybersecurity Enthusiast | SOC Analyst | Penetration Testing Learner

LinkedIn: www.linkedin.com/in/manoj-arya7/

GitHub: Add Your GitHub Profile Here
