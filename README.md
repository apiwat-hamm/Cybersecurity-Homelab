# Virtual Cybersecurity-Homelab
This project documents my virtual cybersecurity homelab built to practice system administration, networking, vulnerability scanning, packet analysis, password auditing, and digital forensics in an isolated lab environment.

The lab was designed to simulate a small enterprise network using Windows Server, Windows client systems, Kali Linux, and security tools commonly used in cybersecurity.

## Lab Environment
- Proxmox VE
- Windows Server 2022
- Windows 10
- Kali Linux
- Cisco Packet Tracer

## Network Services Configured
- Active Directory Domain Services
- DNS
- DHCP
- Users and groups
- Group Policy
- Isolated lab network
- Basic network troubleshooting

## Tools Used
- Nmap
- Wireshark
- OpenVAS
- John the Ripper
- Autopsy
- Volatility
- Metasploit
- Netstat
- Cisco Packet Tracer

## Skills Demonstrated
- Built and managed a virtual enterprise-style lab
- Configured Windows Server roles and services
- Joined Windows client machines to a domain
- Practiced Windows and Linux administration
- Performed vulnerability scanning
- Analyzed network traffic with Wireshark
- Used Nmap for host discovery and port scanning
- Practiced password auditing with John the Ripper
- Practiced basic digital forensics with Autopsy and Volatility
- Simulated networking concepts using Cisco Packet Tracer
- Troubleshot operating system, registry, and network issues

## Screenshots

## Proxmox Dashboard

<img width="1177" height="817" alt="Screenshot 2026-07-06 040711" src="https://github.com/user-attachments/assets/9869ad28-cb61-4ef6-a6e2-adce4e5aa3bb" />

**Description:** 
The Proxmox VE host running multiple virtual machines used in the homelab, including Windows Server 2022, Windows 10, and Kali Linux.

## Virtual Network Configuration

<p align="center">

<img width="1080" height="177" alt="Screenshot 2026-07-06 041131" src="https://github.com/user-attachments/assets/575db1f7-429e-438f-be43-7486cde80bce" />


<img width="548" height="414" alt="Screenshot 2026-07-06 041538" src="https://github.com/user-attachments/assets/c9c0831d-fb52-443a-9f08-024f866df5e9" />


<img width="809" height="464" alt="Screenshot 2026-07-06 041643" src="https://github.com/user-attachments/assets/0e82bf7a-c7c8-440d-95fb-8bac693511c9" />

</P>

 VM | IP Address | Role |
|----|------------|------|
| DC01 | 10.10.10.10 | Domain Controller |
| WIN10 | 10.10.10.20 | Client |
| Kali | 10.10.10.30 | Security Testing |

**Description:** 
Configured virtual bridges to separate the home network from the isolated lab network. This setup allows communication between virtual machines while keeping the lab environment isolated from the production network.

## Active Directory

<p align="center">

<img width="652" height="582" alt="Screenshot 2026-07-06 053803" src="https://github.com/user-attachments/assets/321fd2e6-0e1f-4f3c-9c31-de4972e9660b" />
<img width="673" height="486" alt="Screenshot 2026-07-06 054340" src="https://github.com/user-attachments/assets/a03e2e6d-a0ac-4e44-9f67-83b87c2472d4" />
<img width="847" height="487" alt="Screenshot 2026-07-06 054536" src="https://github.com/user-attachments/assets/4c209dcd-16c2-4a2d-ab40-dc6fd1174b58" />
<img width="622" height="229" alt="Screenshot 2026-07-06 054736" src="https://github.com/user-attachments/assets/87a6e930-4350-4369-bd7e-2caf621b3f4f" />

</p>

**Description:**
Configured Active Directory Domain Services for the `ajlab.local` domain. Created users and groups to simulate a small enterprise environment and centralize authentication and account management.

## DNS Configuration

<p align="center">

<img width="751" height="369" alt="Screenshot 2026-07-07 020256" src="https://github.com/user-attachments/assets/952acf9a-3cb4-411d-980e-06ffdee04520" />
</p>
**Description:** 
Configured DNS on the domain controller to provide name resolution for the `ajlab.local` Active Directory domain. Created and verified DNS records to allow domain-joined clients to locate network resources and services.



