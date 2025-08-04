 Nmap Network Scan Report
🖥️ 1. Environment Setup
Operating System: Your OS here (kali-linux / Windows 11)

Tool Used: Nmap – Network Mapper

Scan Date: Insert date here (August 4 2025)

🌐2. Network Information
Local IP Address: 192.168.1.XXX

Subnet Range Scanned: 192.168.1.0/24

Scan Type: TCP SYN scan (-sS)

⚙️ 3. Nmap Command Used

nmap -sS 192.168.1.0/24 local_scan #i performed stealth scan on my own internal network as a initial recon and found no ports open every thing is filtered and closed.

Analysis (Optional)
1. No open ports were detected. This could mean:
2. Devices have firewalls enabled.
3. Only filtered ports are present (Nmap sees them as "closed" or "filtered").
4. Devices are configured not to respond to scans.

🛡️ 6. Security Consideration
Even though no open ports were found:

It's still important to regularly scan your network.

Verify your firewall and security settings.

Use tools like Wireshark for deep packet inspection if necessary.

