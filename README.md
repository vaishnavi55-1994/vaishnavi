# vaishnavi
<# Task1-Nmap This is my Nmap work
Official website : - https://nmap.org/download#windows
Stable version:- nmap-7.97-setup.exe
Run .exe file
![Alt text]![inst](https://github.com/user-attachments/assets/81ec2db7-8c8b-4637-9315-f9b980ea08d4)
IP Addresses and Open Ports
1)	Nmap scan report for 192.168.1.1
PORT   STATE SERVICE
23/tcp open  telnet
80/tcp open  http
2)	Nmap scan report for 192.168.1.2
PORT   STATE SERVICE
23/tcp open  telnet
80/tcp open  http
3)	Nmap scan report for 192.168.1.3
PORT    STATE SERVICE
21/tcp  open  ftp
80/tcp  open  http
443/tcp open  https
4)	Nmap scan report for 192.168.1.11
PORT   STATE SERVICE
23/tcp open  telnet
80/tcp open  http
5)	Nmap scan report for 192.168.1.64
PORT     STATE SERVICE
80/tcp   open  http
443/tcp  open  https
554/tcp  open  rtsp
8000/tcp open  http-alt

nmap -sS 192.168.1.0/24
sS Stand for SYN Scan
Nmap done: 256 IP addresses (43 hosts up) scanned in 115.86 seconds
![report](https://github.com/user-attachments/assets/ec7cf8e0-5955-4754-85bc-90a5a7827453)


Here’s a  risk summary for each port:

Telnet (23): Transmits unencrypted credentials, making it vulnerable to interception and brute-force attacks.

HTTP-ALT (8080): Often used for unencrypted web services or admin panels, exposing systems to web-based attacks.

RTSP (554): Can leak audio/video streams and is often unsecured or weakly protected on IP cameras and streaming devices.
