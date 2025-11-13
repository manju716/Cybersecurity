<img width="787" height="693" alt="image" src="https://github.com/user-attachments/assets/085867a9-4f69-43a1-a5ec-a9fed102a5f5" /><img width="801" height="711" alt="image" src="https://github.com/user-attachments/assets/19896193-5811-4f55-b880-414ba55b3704" /># Cybersecurity

19045.6456] rosoft Windows [version 10
(c) Microsoft Corporation. All rights reserved.
C:\Windows\system32>ipconfig
Windows IP Configuration
Ethernet adapter Ethernet:
Media State
: Media disconnected
Connection-specific DNS Suffix
:
Wireless LAN adapter Local Area Connection* 9:
Media State
: Media disconnected
Connection-specific DNS Suffix :
Wireless LAN adapter Local Area Connection* 10:
Media State
: Media disconnected
Connection-specific DNS Suffix :
Wireless LAN adapter Wi-Fi:
Connection-specific DNS Suffix
Link-local IPv6 Address
IPv4 Address.
: 192.168.1.102
Subnet Mask.
: fe80::8ef0:7dc4:d527:5969%13
: 255.255.255.0
Default Gateway : 192.168.1.1
Ethernet adapter Bluetooth Network Connection:
Media State
: Media disconnected
Connection-specific DNS Suffix :
C:\Windows\system32>nmap -sS <Your_Local_IP_Range>
The syntax of the command is incorrect.
C:\Windows\system32>nmpass 192.168.1.102
'nmpa' is not recognized as an internal or external command, operable program or batch file.
C:\Windows\system32>nman -SS 192 1 102

Media State.
Media disconnected
Connection-specific DNS Suffix
C:\Windows\system32>nmap -sS <Your_Local_IP_Range>
The syntax of the command is incorrect.
C:\Windows\system32>nmpass 192.168.1.102
'nmpa' is not recognized as an internal or external command, operable program or batch file.
C:\Windows\system32>nmap ss 192.1.102
Starting Nmap 7.98 (https://nmap.org) at 2025-11-13 22:27 +0530
Failed to resolve "192.1.102".
WARNING: No targets were specified, so o hosts scanned.
Nmap done: 0 IP addresses (0 hosts up) scanned in 1.58 seconds
C:\Windows\system32>nmap ss 192.1.102/24
Starting Nmap 7.98 (https://nmap.org) at 2025-11-13 22:28 +0530
Failed to resolve "192.1.102".
WARNING: No targets were specified, so e hosts scanned.
Nmap done: 0 IP addresses (0 hosts up) scanned in 1.22 seconds
C:\Windows\system32># This command re-runs the scan and saves the output to a file
'#' is not recognized as an internal or external command, operable program or batch file.
C:\Windows\system32>nmap -ss 192.168.1.0/24 -ON scan_results.txt
Starting Nmap 7.98 (https://nmap.org) at 2025-11-13 22:31 +0530
Nmap scan report for 192.168.1.1
Host is up (0.027s latency).
Not shown: 993 closed tcp ports (reset)
PORT
STATE SERVICE
21/tcp open ftp
23/tcp open telnet
53/tcp open domain
80/tcp open http
139/tcp open netbios-ssn
445/tcp open microsoft-ds
1900/tcp open upnp
MAC Address: 14:EB:86:C2:F1:86 (TP-Link Limited)
Nmap scan report for 192.168.1.119
Host is up (0.051s latency).
Not shown: 994 filtered tcp ports (no-response)
Nmap scan report for 192.168.1.102
Host is up (0.0013s latency).
Not shown: 995 closed tcp ports (reset)
PORT STATE SERVICE
135/tcp open msrpc
139/tcp open netbios-ssn
445/tcp open microsoft-ds
3306/tcp open mysql
7070/tcp open realserver
Nmap done: 256 IP addresses (3 hosts up) scanned in 12.60 seconds
C:\Windows\system32>nmap ss 192.168.1.0/24 -oN scan_results.txt
Starting Nmap 7.98 (https://nmap.org) at 2025-11-13 22:33 +0530
Nmap scan report for 192.168.1.1
Host is up (0.0053s latency).
Not shown: 993 closed tcp ports (reset)
PORT STATE SERVICE
21/tcp open ftp
23/tcp open telnet
53/tcp open domain
80/tcp open http
139/tcp open netbios-ssn
445/tcp open microsoft-ds
1900/tcp open upnp
MAC Address: 14:EB:B6:C2:F1:B6 (TP-Link Limited)
Nmap scan report for 192.168.1.102
Host is up (0.00013s latency).
Not shown: 995 closed tcp ports (reset)
PORT STATE SERVICE
135/tcp open msrpc
139/tcp open netbios-ssn
445/tcp open microsoft-ds
3306/tcp open mysql
7070/tcp open realserver
Nmap done: 256 IP addresses (2 hosts up) scanned in 5.62 seconds
C:\Windows\system32>^ZS
