# Network Reconaissance

## Ping and ICMP Requests:
Kali Linux

<img width="669" height="200" alt="Ping" src="https://github.com/user-attachments/assets/26097189-7524-4f8e-8caa-fcf587d4ae8a" />

WireShark:
ip.addr == 192.168.10.250 && icmp.type == 8 (for ICMP replies)
<img width="970" height="289" alt="ICMP Requests" src="https://github.com/user-attachments/assets/20c3d28b-fc74-4d05-bd07-81946eb3d248" />

## Nmap scan 
nMap -Pn -sT --top-ports 20 192.168.10.100 (Very noisy scan but I wanted it to show up in wireshark)
<img width="644" height="506" alt="nmap - top ports" src="https://github.com/user-attachments/assets/3643450e-416a-4f0f-837c-ff4d3b504026" />

WireShark:

A bunch of tcp retransmissions.
<img width="958" height="564" alt="Wireshark tcp noisy retransmissions" src="https://github.com/user-attachments/assets/a2245b84-10f9-43d1-988f-5b3d4eb81b8d" />
