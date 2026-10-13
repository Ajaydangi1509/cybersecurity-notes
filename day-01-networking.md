# Day 1: Networking Basics

## 1. IP Address

**Kya hai:** Har device ka unique number network pe.

**Types:**
- **Public IP:** Internet pe visible. ISP deta hai. (e.g., 43.239.25.154)
- **Private IP:** Sirf local network. Router deta hai. (e.g., 192.168.1.36)

**Analogy:**
- Public IP = Ghar ka address
- Private IP = Room number

**Commands:
ip a                    # Apna IP dekho
curl ifconfig.me        # Public IP dekho
ip route                # Router ka IP dekho


sudo nmap -sS -sV -T4 <IP>

3. ICMP (Internet Control Message Protocol)
Kya hai: Network layer protocol for errors and diagnostics.

Common Types:

Type	Name	Use
0	Echo Reply	Ping reply
3	Destination Unreachable	Packet fail
8	Echo Request	Ping request
11	Time Exceeded	TTL expired

ping -c 4 google.com 


5. Essential Linux Commands
Command	Kya Karta Hai
pwd	Current folder path
ls -la	Saari files (hidden bhi)
file <file>	File type check
head -20 <file>	Top 20 lines
find / -name "*.conf"	Config files dhoondho
du -sh /*	Disk usage
ps aux	Running processes
netstat -  tulpn	Open ports

