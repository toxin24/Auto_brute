# Auto_brute
this is an automated brute-forcing attack tool edited version of t14m4t https://github.com/MS-WEB-BN/t14m4t, wrapper of [THC-Hydra](https://github.com/vanhauser-thc/thc-hydra) and [Nmap Security Scanner](https://github.com/nmap/nmap).

# what's change;
t14m4t was design to automated brute force given single IP or list of IP Addresses. and auto_brute aim to perform the same technique but instead of scaning list of IPs you could scan list of segment of the IP address eg 10.10.10.0/24 


# Usage:
- Segment of IP target
- Target can also be a file, where each target is separated by return. 
- Optional: Number of threads, from 1 to 64. 16 (default) threads.
```
# ./Auto_brute.sh <target> <number of threads>
```
#Example:
```
# ./Auto_brute.sh 10.10.10.0/24
# ./Auto_brute.sh /targets/targetlist.txt 32
```
# Supported services:

FTP | SSH | Telnet | SMTP | HTTP | POP3 | SMB | SNMP | LDAP | HTTPS | rexec | rlogin | rsh | IMAP | mssql | mysql | postgres | oracle | RDP | VNC | IRC
# collect result
To collect the result use read_output.py here https://github.com/toxin24/others

