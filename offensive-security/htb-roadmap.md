# Hack The Box Advanced Roadmap

## 1. HTB Starting Point

### Topics:
- Introduction to Hack The Box Platform
- VPN Connections
- Target Machines
- Attack Methodology
- Basic Enumeration
- Basic Exploitation
- Linux and Windows Targets
- Flag Submission
- Documentation Skills

### Activities:
- Create Hack The Box account
- Configure OpenVPN connection
- Learn HTB interface and machines
- Practice target discovery
- Perform basic port scanning
- Identify running services
- Exploit beginner-level vulnerabilities
- Capture user and root flags
- Take detailed notes for every machine

### Practice Machines:
- Tier 0 Machines
- Tier 1 Machines

### Goals:
- Understand HTB workflow
- Learn basic penetration testing process
- Build hacking methodology
- Complete all Starting Point machines


---

# 2. HTB Academy Fundamentals

## Topics:
- Cyber Security Fundamentals
- Information Security Concepts
- CIA Triad
- Threat Models
- Risk Management
- Security Controls
- Authentication Concepts
- Authorization Models
- Common Attack Methodologies

## Activities:
- Learn penetration testing lifecycle
- Understand defensive and offensive security
- Study real-world attack scenarios
- Create security concept notes
- Learn common security terminology
- Complete HTB Academy Introduction Modules

## Goals:
- Build strong security foundation
- Understand why attacks work
- Learn professional security terminology


---

# 3. Linux Fundamentals

## Topics:
- Linux Operating System Basics
- Linux File System
- Directory Structure
- Users and Groups
- Permissions
- Ownership
- Processes
- Services
- Package Management
- Environment Variables
- SSH
- Bash Basics

## Activities:
- Install Kali Linux
- Practice Linux terminal commands
- Navigate Linux filesystem
- Create and manage users
- Modify permissions
- Manage running processes
- Install security tools
- Configure SSH connections
- Write basic Bash scripts

## Important Commands:

- ls
- cd
- pwd
- cat
- less
- grep
- find
- chmod
- chown
- ps
- systemctl
- netstat
- ssh

## HTB Academy Modules:
- Linux Fundamentals Part 1
- Linux Fundamentals Part 2
- Linux Fundamentals Part 3

## Goals:
- Become comfortable using Linux
- Understand Linux administration
- Prepare for penetration testing tasks


---

# 4. Networking Fundamentals

## Topics:
- Network Models
- OSI Model
- TCP/IP Model
- IPv4 Addressing
- IPv6 Basics
- Subnetting
- MAC Addresses
- ARP
- Routing
- TCP Protocol
- UDP Protocol
- Ports and Services
- DNS
- DHCP
- HTTP/HTTPS
- VPN Concepts
- Firewalls

## Activities:
- Calculate subnet ranges
- Analyze network traffic with Wireshark
- Study packet communication
- Capture TCP handshakes
- Identify protocols
- Scan networks using Nmap
- Create network diagrams
- Analyze DNS requests

## Tools:
- Wireshark
- Tcpdump
- Nmap
- Netcat

## HTB Academy Modules:
- Introduction to Networking
- Networking Fundamentals

## Goals:
- Understand network communication
- Identify services running on systems
- Prepare for enumeration


---

# 5. Web Requests Fundamentals

## Topics:
- How Websites Work
- Client and Server Communication
- HTTP Protocol
- HTTPS Encryption
- HTTP Methods
- Status Codes
- Headers
- Cookies
- Sessions
- Authentication
- APIs
- Web Parameters

## Activities:
- Analyze HTTP requests
- Modify requests using Burp Suite
- Capture browser traffic
- Test parameters
- Understand cookies
- Analyze authentication flows
- Practice API requests
- Learn basic web attacks

## Tools:
- Burp Suite
- Browser Developer Tools
- Curl
- Wget

## Practice:

- Send GET requests
- Send POST requests
- Modify headers
- Test parameters
- Analyze responses

## HTB Academy Modules:
- Web Requests

## Goals:
- Understand web communication
- Prepare for web vulnerability testing
- Learn HTTP attack techniques


---

# 6. Footprinting

## Topics:
- Information Gathering
- Passive Reconnaissance
- Active Reconnaissance
- OSINT Techniques
- Domain Discovery
- DNS Enumeration
- Email Discovery
- Technology Identification
- Website Profiling
- Social Media Intelligence

## Activities:
- Perform domain reconnaissance
- Gather public information
- Identify technologies used by websites
- Analyze DNS records
- Find subdomains
- Collect employee information
- Search leaked information
- Create reconnaissance reports

## Tools:

- Whois
- Dig
- Nslookup
- Google Dorks
- Shodan
- TheHarvester
- SpiderFoot

## HTB Academy Modules:
- Footprinting Fundamentals

## Goals:
- Learn professional reconnaissance
- Gather information before attacks
- Understand target infrastructure


---

# 7. Enumeration

## Topics:
- Enumeration Methodology
- Service Discovery
- Port Scanning
- Banner Grabbing
- SMB Enumeration
- FTP Enumeration
- SSH Enumeration
- DNS Enumeration
- Web Enumeration
- Database Enumeration
- User Enumeration

## Activities:
- Perform Nmap scans
- Identify open ports
- Identify running services
- Enumerate SMB shares
- Enumerate FTP servers
- Discover hidden directories
- Analyze service versions
- Search for vulnerabilities

## Tools:

### Network Enumeration:
- Nmap
- Netcat

### Web Enumeration:
- Gobuster
- Feroxbuster
- Nikto

### Service Enumeration:
- Enum4linux
- SMBclient
- SNMP tools

## Nmap Practice:

Basic Scan:

nmap target-ip

Service Detection:

nmap -sV target-ip

Aggressive Scan:

nmap -A target-ip


## HTB Academy Modules:
- Network Enumeration
- Service Enumeration

## Goals:
- Discover attack surface
- Identify vulnerabilities
- Prepare exploitation strategy


---

# Final HTB Practice Projects


# Project 1: Beginner HTB Machine

Tasks:

- Connect through VPN
- Perform reconnaissance
- Scan ports
- Enumerate services
- Find vulnerabilities
- Exploit target
- Capture flags
- Write notes


---

# Project 2: Complete Penetration Test

Tasks:

## Reconnaissance

- Information gathering
- Domain discovery
- Technology identification

## Scanning

- Port scanning
- Service identification
- Version detection

## Enumeration

- SMB enumeration
- Web enumeration
- User discovery

## Exploitation

- Vulnerability analysis
- Exploit selection
- Initial access

## Privilege Escalation

- Linux privilege escalation
- Windows privilege escalation

## Reporting

- Executive summary
- Technical findings
- Screenshots
- Recommendations


---

# Project 3: HTB Skill Development

Platforms:

- Hack The Box
- HTB Academy
- TryHackMe
- VulnHub


## Goals:

- Complete Starting Point
- Complete Academy Fundamentals
- Solve Easy machines
- Build personal methodology
- Maintain hacking notes
- Create penetration testing reports
- Develop professional pentesting skills


---

# Recommended Learning Order

1. HTB Starting Point
2. Academy Fundamentals
3. Linux Fundamentals
4. Networking Fundamentals
5. Web Requests
6. Footprinting
7. Enumeration
8. Easy HTB Machines
9. Privilege Escalation
10. Active Directory
11. Advanced Penetration Testing