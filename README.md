# 🐧 Linux for Cyber Security

![Linux](https://img.shields.io/badge/Platform-Linux-black?logo=linux)
![Security](https://img.shields.io/badge/Focus-CyberSecurity-red)
![Shell](https://img.shields.io/badge/Scripting-Bash-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)

A technical guide and reference for using Linux as a professional cyber security environment.  
Focused on terminal mastery, offensive security, defensive security, and automation.

---

## 📌 Overview

Linux is the foundation of modern cyber security operations.  
This repository documents essential Linux knowledge required for:

- penetration testing
- incident response
- system hardening
- network analysis
- privilege escalation
- security automation

The goal is to build **real-world operational Linux skills**.

---

## ⚙️ Core Linux Skills

### 🔐 Permissions & Privilege Model

Understanding Linux permissions is critical for security:

- UID / GID architecture
- rwx permission model
- SUID / SGID / sticky bit
- sudo configuration
- `/etc/passwd` & `/etc/shadow` analysis

---

### 🧠 Process & System Monitoring

Detecting abnormal behavior requires system visibility:

- process tree analysis
- daemon management
- systemd services
- kernel log inspection
- signal handling (SIGTERM / SIGKILL)

---

### 🌐 Networking & Traffic Analysis

Linux networking stack enables deep inspection:

- socket analysis
- routing tables
- firewall rules
- packet capture
- port monitoring

---

### 🤖 Automation & Shell Scripting

Automation is mandatory in security operations:

- Bash scripting
- cron scheduling
- log parsing
- scanning automation
- monitoring scripts

---

## 🔴 Offensive Security Usage

Linux is the standard platform for red team operations:

- exploit development
- payload generation
- lateral movement
- persistence techniques
- privilege escalation

---

## 🔵 Defensive Security Usage

Linux powers defensive infrastructure:

- server hardening
- intrusion detection
- forensic analysis
- log centralization
- SIEM integration

---

## 🧰 Essential Linux Commands

### File & Permission Management

```
ls -la
chmod
chown
stat
getfacl
setfacl
umask
```

### User & Privilege

```
whoami
id
sudo -l
su
passwd
groups
```

### Process Monitoring

```
ps aux
top / htop
pstree
kill / killall
lsof
```

### System & Logs

```
dmesg
journalctl
last
history
```

### Networking

```
ip a
ip route
ss -tulnp
netstat -an
tcpdump
traceroute
```

### File Analysis

```
find
grep
strings
file
hexdump
xxd
```

---

## 🔍 Security Tools

### Recon / Enumeration

```
nmap
enum4linux
whois
dig
theHarvester
```

### Exploitation

```
metasploit-framework
searchsploit
msfvenom
sqlmap
```

### Web Security

```
burpsuite
nikto
wfuzz
gobuster
```

### Network Analysis

```
wireshark
tcpdump
ettercap
```

### Password Attacks

```
hydra
john
hashcat
```

### Forensics / Reverse Engineering

```
binwalk
foremost
volatility
radare2
```

---

## 🎯 Goal

Master Linux → understand systems deeply → operate securely.

Linux proficiency is not optional in cyber security.  
It is the foundation.

---

## 📜 License

MIT License — free to use, modify, and learn.

---

⭐ If this repo helps you, consider starring it.
