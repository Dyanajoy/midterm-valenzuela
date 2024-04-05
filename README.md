# Midterm-valenzuela

by [Diana Joy C. Valenzuela](https://www.facebook.com/dianajoy.valenzuela.5)

## **Information Gathering** 
This category includes tools used for everything from identifying all the devices on a network -- enumerating -- to linking a network interface controller's media access control address with an IP address to identifying open ports on targeted servers. Kali Linux information gathering tools include scanners, such as Nmap and Wireshark, as well as information planning platforms that integrate the leading tools, often with GUIs for more comprehensive functionality.

* ### [**AMASS**](https://www.kali.org/tools/amass/)
  This package contains a tool to help information security professionals perform network mapping of attack surfaces and perform external asset discovery using open source information gathering and active reconnaissance techniques.
  
* [Video Tutorial](https://youtu.be/skoPPyRneCk?si=Gm7MpU99zSPE9i_q)


## COMMAND EXAMPLE: 
```bash
amass enum -d example.com
```

* ### [**Dmitry**](https://www.kali.org/tools/dmitry/)
  is a command-line tool in Kali Linux that is used for passive information gathering. It can be used to find subdomains, email addresses, whois information, and other details about a target. 

* [Video Tutorial](https://youtu.be/-mFMjHNgnuw?si=kO-4UrbMzbzYLBks)


## COMMAND EXAMPLE: 
```bash
dmitry -iwnp -t 7 host.net
```

* ### [**LEGION(ROOT)**](https://www.kali.org/tools/legion/)
  This package contains an open source, easy-to-use, super-extensible and semi-automated network penetration testing tool that aids in discovery, reconnaissance and exploitation of information systems. Legion is a fork of SECFORCE's Sparta.
  
* [Video Tutorial](https://youtu.be/0v2_UFhq6zQ?si=PNMyQkZzn6qTmIim)


* ### [**MALTEGO (INSTALLER)**](https://www.kali.org/tools/maltego/)
   Maltego is an open source intelligence and forensics application. It will offer you timous mining and gathering of information as well as the representation of this information in a easy to understand format.

* [Video Tutorial](https://youtu.be/a2ZvpwF3u-M?si=DSzByzkDZeCnGIkp)


* ### [**NET DISCOVER**](https://www.kali.org/tools/netdiscover/)
  Netdiscover is an active/passive address reconnaissance tool, mainly developed for those wireless networks without dhcp server, when you are wardriving. It can be also used on hub/switched networks.

* [Video Tutorial](https://youtu.be/8zP7A07x3tg?si=Zv527eUzARr_VXrA)


* ### [**NMAP**](https://www.kali.org/tools/nmap/)
  Nmap is a utility for network exploration or security auditing. It supports ping scanning (determine which hosts are up), many port scanning techniques, version detection (determine service protocols and application versions listening behind ports), and TCP/IP fingerprinting (remote host OS or device identification).
 
* [Video Tutorial](https://youtu.be/LTMucsu35dk?si=X5N5cKk2Rg3vRqIo)


* ### [**RECON-NG**](https://kali.org/tools/recon-ng/)
  Recon-ng is a web-based open-source reconnaissance tool (OSINT) written in Python, often paired with the Kali Linux penetration distribution. The tool reduces time spent harvesting information from open resources and consists of an extensive range of modules and database interaction.
 
* [Video Tutorial](]https://youtu.be/68rRliy5DBw?si=6owv-Qb45oZCo1VA)


* ### [**SPIDER FOOT**](https://www.kali.org/tools/spiderfoot/)
  SpiderFoot can be used offensively, i.e. as part of a black-box penetration test to gather information about the target, or defensively to identify what information you or your organisation are freely providing for attackers to use against you.
  
* [Video Tutorial](https://youtu.be/sSYuTD7wDhE?si=85XxN9jCkr3Djncz)
  
## **Vulnerability Analysis**
It is a tool to exploit SQL injection vulnerabilities on a web application. It also provides remote access to the vulnerable DB server.

* ### [**LEGION(ROOT)**](https://www.kali.org/tools/legion/)
  This package contains an open source, easy-to-use, super-extensible and semi-automated network penetration testing tool that aids in discovery, reconnaissance and exploitation of information systems. Legion is a fork of SECFORCE's Sparta.
  
* [Video Tutorial](https://youtu.be/0v2_UFhq6zQ?si=PNMyQkZzn6qTmIim)

* ### [**NIKTO**](https://www.kali.org/tools/nikto/)
  Nikto is a web server vulnerability scanner that automates the process of scanning web servers for out-of-date and unpatched software as well as searching for dangerous files that may reside on web servers.

 * [Video Tutorial](https://youtu.be/GH9qn_DBzCk?si=rhShy_X52LfPNDuS)
  
* ### [**NMAP**](https://www.kali.org/tools/nmap/)
  Nmap is a utility for network exploration or security auditing. It supports ping scanning (determine which hosts are up), many port scanning techniques, version detection (determine service protocols and application versions listening behind ports), and TCP/IP fingerprinting (remote host OS or device identification).
 
* [Video Tutorial](https://youtu.be/LTMucsu35dk?si=X5N5cKk2Rg3vRqIo)

* ### [**UNIX-PRIVESC-CHECK**](https://www.kali.org/tools/unix-privesc-check/)
  Unix-privesc-checker is a script that runs on Unix systems (tested on Solaris 9, HPUX 11, Various Linuxes, FreeBSD 6.2). It tries to find misconfigurations that could allow local unprivileged users to escalate privileges to other users or to access local apps (e.g. databases).
  
* [Video Tutorial](https://youtu.be/5oo491REt60?si=bA_ze3DYWvC-u4AD)

## Web Application Analysis
The process involves an active analysis of the application for any weaknesses, technical flaws, or vulnerabilities. Any security issues that are found will be presented to the system owner, together with an assessment of the impact, a proposal for mitigation or a technical solution.

* ### [**BURPSUITE**](https://www.kali.org/tools/burpsuite/)
  Burp Suite is an integrated platform for performing security testing of web applications. Its various tools work seamlessly together to support the entire testing process, from initial mapping and analysis of an application's attack surface, through to finding and exploiting security vulnerabilities.
  
* [Video Tutorial](https://youtu.be/o1-0w2-kVgo?si=dtM535k1GU0IIpeD)
  
* ### [**COMMIX**](https://www.kali.org/tools/commix/)
  Commix, short for [comm]and [i]njection e[x]politer, is a tool for finding and exploiting command injection vulnerabilities in a given parameter.
  
* [Video Tutorial](https://youtu.be/7VeZqlVLWdE?si=QERql5HXPKrvALNV)

* ### [**SKIPFISH**](https://www.kali.org/tools/skipfish/)
  Skipfish is an active web application security reconnaissance tool. It prepares an interactive sitemap for the targeted site by carrying out a recursive crawl and dictionary-based probes. The resulting map is then annotated with the output from a number of active (but hopefully non-disruptive) security checks.
  
* [Video Tutorial](https://youtu.be/E3UNn7PTy4c?si=QXhVm5XL6LPzA-rg)

* ### [**SQLMAP**](https://www.kali.org/tools/sqlmap/)
  SQLMap is a good tool when it comes to detecting and exploiting SQL injection vulnerabilities. With so many supported options, switches and ability to create and use the customize script, it stands out from the many open-source tools for testing SQL injection vulnerabili
 
* [Video Tutorial](https://youtu.be/nVj8MUKkzQk?si=sUBjesRqCk-E86FN)

* ### [**WEBSHELLS**](https://www.kali.org/tools/webshells/)
  A web shell is a piece of code, when executed on a web server, gives access to its file system and/or terminal, with the ability to execute commands remotely.

* [Video Tutorial](https://youtu.be/oHrpXR4zSro?si=d9yNf5gEHI-461JG)
  
* ### [**WPSCAN**](https://kali.org/tools/wpscan/)
  WPScan is a very fast WordPress vulnerability scanner written in the Ruby programming language and preinstalled in Kali Linux. The following information can be extracted using WPScan: The plugins list. The name of the theme. Weak passwords and usernames using the brute forcing technique.

* [Video Tutorial](https://youtu.be/9gwyj4frqwc?si=mLnE1ARvmYPeS82D)

## Database Assessment
It evaluates and verifies the security measures and mechanisms already implemented. It identifies security flaws and vulnerabilities in configurations and IT environments that can lead to data breaches, malicious infiltration, etc. It helps organizations to meet legal, regulatory, and compliance requirements such as.

* ### [**SQLite Database Browser**](https://www.kali.org/tools/sqlitebrowser/)
  SQLite Database Browser is a visual tool used to create, design and edit database files compatible with SQLite. Its interface is based on QT, and is meant to be used for users and developers that want to create databases, edit and search data using a familiar spreadsheet-like interface, without the need to learn complicated SQL commands. Controls and wizards are available for users to:

* [Video Tutorial](https://youtu.be/3HnA7s6AKwo?si=fksMQnoPJxG0JbNo)
  
* ### [**SQLMAP**](https://www.kali.org/tools/sqlmap/)
  SQLMap is a good tool when it comes to detecting and exploiting SQL injection vulnerabilities. With so many supported options, switches and ability to create and use the customize script, it stands out from the many open-source tools for testing SQL injection vulnerabili
 
* [Video Tutorial](https://youtu.be/nVj8MUKkzQk?si=sUBjesRqCk-E86FN)
  
## Password Attacks
A password attack is any attempt to exploit a vulnerability in user authorization within a digital system. And just as there are a near-infinite number of possible passwords, there are many different methods that a cybercriminal may employ to maliciously authenticate into a secure account.

* ### [**CEWL**](https://www.kali.org/tools/cewl/)
  CeWL (Custom Word List generator) is a ruby app which spiders a given URL, up to a specified depth, and returns a list of words which can then be used for password crackers such as John the Ripper. Optionally, CeWL can follow external links.

* [Video Tutorial](https://www.youtube.com/watch?v=5VLEemE1LZ8)



* ### [**CRUNCH**](https://www.kali.org/tools/crunch/)

 
* [Video Tutorial](https://youtu.be/7cz9OyhFFps?si=OeR_6vqsypRFqVMl)

* ### [**HASHCAT**](https://www.kali.org/tools/hashcat/)
  CeWL (Custom Word List generator) is a ruby app which spiders a given URL, up to a specified depth, and returns a list of words which can then be used for password crackers such as John the Ripper. Optionally, CeWL can follow external links.

* [Video Tutorial](https://youtu.be/5fy6Lq1vgZk?si=DE1TfIbWp-m-dNSs)

* ### [**HYDRA**](https://www.kali.org/tools/hydra/)
  Hydra is a parallelized login cracker which supports numerous protocols to attack. It is very fast and flexible, and new modules are easy to add.

* [Video Tutorial](https://youtu.be/7lsx0-HFCFo?si=xtHKbRNXzmeAnzK0)

* ### [**JOHN**](https://www.kali.org/tools/john/)
  john, better known as John the Ripper, is a tool to find weak passwords of users in a server. The unique tool finds and removes duplicate entries from a wordlist (read from stdin), without changing the order. This is important to in- crease the performance of john when using the wordlist method.

* [Video Tutorial](https://youtu.be/nV2HEU7HIdY?si=Fv2NYAxyfivv55gk)

* ### [**MEDUSA**](https://www.kali.org/tools/medusa/)
Medusa is intended to be a speedy, massively parallel, modular, login brute-forcer. The goal is to support as many services which allow remote authentication as possible. The author considers following items as some of the key features of this application: * Thread-based parallel testing. Brute-force testing can be performed against multiple hosts, users or passwords concurrently. * Flexible user input. Target information (host/user/password) can be specified in a variety of ways. For example, each item can be either a single entry or a file containing multiple entries. Additionally, a combination file format allows the user to refine their target listing. * Modular design. Each service module exists as an independent .mod file. This means that no modifications are necessary to the core application in order to extend the supported list of services for brute-forcing.

* [Video Tutorial](https://youtu.be/ANE5qhZsm7U?si=yZRXoAW3K2-tkQsB)

* ### [**NCRACK**](https://www.kali.org/tools/ncrack/)
  Ncrack is a high-speed network authentication cracking tool. It was built to help companies secure their networks by proactively testing all their hosts and networking devices for poor passwords. Security professionals also rely on Ncrack when auditing their clients.

* [Video Tutorial](https://youtu.be/xlUOJGDC0aw?si=v71xPLyRqdxuLmjA)

* ### [**OPHCRACK**](https://www.kali.org/tools/ophcrack/)
  Ophcrack is a tool that can be used for breaking Windows passwords. This is a free, open-source tool that can recover all the hashes of the SAM (security accounts manager) registry key in older versions and LM Hashes in more recent ones.

* [Video Tutorial](https://youtu.be/pa_a2cr6AlM?si=QKn_fdkr1R5AKCtp)

* ### [**WORDLISTS**](https://www.kali.org/tools/wordlists/)
This package contains the rockyou.txt wordlist and has an installation size of 134 MB.

* [Video Tutorial](https://youtu.be/nhqHkXJsTew?si=-qUITQdNskqayMQK)

## Wireless Attacks
Wireless network attacks are deliberate and malicious actions aimed at exploiting vulnerabilities in wireless communication systems to gain unauthorized access, intercept sensitive data, disrupt network operations, or compromise the security of devices and users connected to the network.

* ### [**AIRCRACK-NG**](https://www.kali.org/tools/aircrack-ng/)
  aircrack-ng is an 802.11a/b/g WEP/WPA cracking program that can recover a 40-bit, 104-bit, 256-bit or 512-bit WEP key once enough encrypted packets have been gathered. Also it can attack WPA1/2 networks with some advanced methods or simply by brute force.

* [Video Tutorial](https://youtu.be/TreIFFNGMGU?si=oC7HbEzIDFFKZOi9)

* ### [**FERN WIFI CRACKER (ROOT)**](https://www.kali.org/tools/fern-wifi-cracker/)
This package contains a Wireless security auditing and attack software program written using the Python Programming Language and the Python Qt GUI library, the program is able to crack and recover WEP/WPA/WPS keys and also run other network based attacks on wireless or ethernet based networks.

* [Video Tutorial](https://youtu.be/1e3hmGZZ_8U?si=a-8J55fqxBzzdeCZ)

* ### [**KISMET**](https://www.kali.org/tools/kismet/)
  Kismet is a wireless network and device detector, sniffer, wardriving tool, and WIDS (wireless intrusion detection) framework. Kismet works with Wi-Fi interfaces, Bluetooth interfaces, some SDR (software defined radio) hardware like the RTLSDR, and other specialized capture hardware.

* [Video Tutorial](https://youtu.be/3v_bwtHIToQ?si=tobJiV7X8c4WN4Mz)

* ### [**PIXIEWPS**](https://www.kali.org/tools/pixiewps/)
  Pixiewps is a tool written in C used to bruteforce offline the WPS pin exploiting the low or non-existing entropy of some APs (pixie dust attack). It is meant for educational purposes only.

* [Video Tutorial](https://youtu.be/Wc66PEZUpJ4?si=fC1LQhxkk1OMnlhp)

* ### [**REAVER**](https://www.kali.org/tools/reaver/)
  Reaver performs a brute force attack against an access point’s Wi-Fi Protected Setup pin number. Once the WPS pin is found, the WPA PSK can be recovered and alternately the AP’s wireless settings can be reconfigured. This package also provides the Wash executable, an utility for identifying WPS enabled access points. See documentation in /usr/share/doc/reaver/README.WASH.

* [Video Tutorial](https://youtu.be/jJqTpTK6ydA?si=aK8w1VfXiFU1x1ps)

* ### [**WIFITE**](https://www.kali.org/tools/wifite/)
  Wifite is a tool to audit WEP or WPA encrypted wireless networks. It uses aircrack-ng, pyrit, reaver, tshark tools to perform the audit. This tool is customizable to be automated with only a few arguments and can be trusted to run without supervision.

* [Video Tutorial](https://youtu.be/TDVM-BUChpY?si=jNZsvnJTwU5qtfjx)

## Reverse Engineering
Reverse engineering is a useful skill set for both offensive and defensive cybersecurity. On the attack side, the ability to analyze and understand how programs work is valuable for identifying new exploitable vulnerabilities.

* ### [**NASM SHELL**](https://www.kali.org/tools/nasm/)
  Netwide Assembler. NASM will currently output flat-form binary files, a.out, COFF and ELF Unix object files, and Microsoft 16-bit DOS and Win32 object files.

* [Video Tutorial](https://youtu.be/bXCeFPNWjsM?si=kdvM_no_lHOHJJIc)

* ### [**CLANG**](https://www.kali.org/tools/llvm-defaults/)
  The Clang tool is a front end compiler that is used to compile programming languages such as C++, C, Objective C++ and Objective C into machine code.

* [Video Tutorial](https://youtu.be/Co43zXzy4jc?si=XAB0kfFxXBjkeOKP)

* ### [**CLANG++**](https://www.kali.org/tools/llvm-defaults/)
  The Clang tool is a front end compiler that is used to compile programming languages such as C++, C, Objective C++ and Objective C into machine code.

* [Video Tutorial](https://youtu.be/NZZndHgfYAI?si=8eokh3GbLK82x-Fl)

* ### [**RADARE2**](https://www.kali.org/tools/radare2/)
  Radare2 is an open-source framework that can perform disassembly, debugging, analysis, comparing data and manipulation of binary files. This framework works on Windows, Linux and many other platforms and architectures

* [Video Tutorial](https://youtu.be/9fLfD2fZWiA?si=pE4jHuSc6lPEdfVu)

## Exploitation Tools
Exploitation involves using tools including the hundreds found within Kali Linux and code to take advantage of discovered vulnerabilities across different software, systems or applications. The tools involved are numerous, simple to advanced and are normally deployed to attack specific vulnerable services.

* ### [**CRACKMAPEXEC**](https://www.kali.org/tools/crackmapexec/)
  This package is a swiss army knife for pentesting Windows/Active Directory environments.
  From enumerating logged on users and spidering SMB shares to executing psexec style attacks, auto-injecting Mimikatz/Shellcode/DLL’s into memory using Powershell, dumping the NTDS.dit and more.
  The biggest improvements over the above tools are:
    * Pure Python script, no external tools required
    * Fully concurrent threading
    * Uses ONLY native WinAPI calls for discovering sessions, users, dumping SAM hashes etc…
    * Opsec safe (no binaries are uploaded to dump clear-text credentials, inject shellcode etc…

* [Video Tutorial](https://www.youtube.com/watch?v=haBvIG5jHYw)

* ### [**METASPLOIT FRAMEWORK**](https://www.kali.org/tools/metasploit-framework/)
  One of the best sources of information on using the Metasploit Framework is Metasploit Unleashed, a free online course created by OffSec. Metasploit Unleashed guides you from the absolute basics of Metasploit all the way through to advanced topics.

* [Video Tutorial](https://www.youtube.com/watch?v=QynUOJanNqo)

* ### [**MSF PAYLOAD CREATOR**](https://www.kali.org/tools/msfpc/)
  A quick way to generate various “basic” Meterpreter payloads using msfvenom which is part of the Metasploit framework.

* [Video Tutorial](https://www.youtube.com/watch?v=D_XuiU3T-GI)

* ### [**SEARCHSPLOIT**](https://www.kali.org/tools/exploitdb/)
  Searchable archive from The Exploit Database. (https://www.exploit-db.com/)

* [Video Tutorial](https://www.youtube.com/watch?v=nx3Uz9zNrWQ)

* ### [**SOCIAL ENGINEERING TOOLKIT (ROOT)**](https://www.kali.org/tools/set/)
  The Social-Engineer Toolkit (SET) is an open-source Python-driven tool aimed at penetration testing around Social-Engineering.

* [Video Tutorial](https://www.youtube.com/watch?v=NekjERW5PsM)

* ### [**SQLMAP**](https://www.kali.org/tools/sqlmap/)
  sqlmap goal is to detect and take advantage of SQL injection vulnerabilities in web applications. Once it detects one or more SQL injections on the target host, the user can choose among a variety of options to perform an extensive back-end database management system fingerprint, retrieve DBMS session user and database, enumerate users, password hashes, privileges, databases, dump entire or user’s specific DBMS tables/columns, run his own SQL statement, read specific files on the file system and more.

* [Video Tutorial](https://www.youtube.com/watch?v=o3zUnihOHcM&t=16s)

## Sniffing & Spoofing
Sniffing network traffic can provide access to valuable intelligence, and spoofing traffic can enable a penetration tester to identify and exploit potential attack vectors. Kali Linux is an operating system built for penetration testers and includes a large library of built-in tools.

* ### [**ETTERCAP-GRAPHICAL**](https://www.kali.org/tools/ettercap/)
  Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.

* [Video Tutorial](https://www.youtube.com/watch?v=o3zUnihOHcM)

* ### [**MACCHANGER**](https://www.kali.org/tools/macchanger/)
  GNU MAC Changer is an utility that makes the maniputation of MAC addresses of network interfaces easier. MAC addresses are unique identifiers on networks, they only need to be unique, they can be changed on most network hardware. MAC addresses have started to be abused by unscrupulous marketing firms, government agencies, and others to provide an easy way to track a computer across multiple networks. By changing the MAC address regularly, this kind of tracking can be thwarted, or at least made a lot more difficult.

* [Video Tutorial](https://www.youtube.com/watch?v=bshXz5r-CQA)

* ### [**MINICOM**](https://www.kali.org/tools/minicom/)
  Minicom is a clone of the MS-DOS “Telix” communication program. It emulates ANSI and VT102 terminals, has a dialing directory and auto zmodem download.

* [Video Tutorial](https://www.youtube.com/watch?v=o8FtaxJ_E2s)

* ### [**MITMPROXY**](https://www.kali.org/tools/mitmproxy/)
  mitmproxy is an interactive man-in-the-middle proxy for HTTP and HTTPS. It provides a console interface that allows traffic flows to be inspected and edited on the fly.

* [Video Tutorial](https://www.youtube.com/watch?v=ervVOeBHIok)

* ### [**NETSNIFF-NG**](https://www.kali.org/tools/netsniff-ng/)
  netsniff-ng is a high performance Linux network sniffer for packet inspection. It can be used for protocol analysis, reverse engineering or network debugging. The gain of performance is reached by ‘zero-copy’ mechanisms, so that the kernel does not need to copy packets from kernelspace to userspace.

* [Video Tutorial](https://www.youtube.com/watch?v=Nut5yBmmMOY)

* ### [**RESPONDER**](https://www.kali.org/tools/responder/)
  This package contains Responder/MultiRelay, an LLMNR, NBT-NS and MDNS poisoner. It will answer to specific NBT-NS (NetBIOS Name Service) queries based on their name suffix (see: http://support.microsoft.com/kb/163409). By default, the tool will only answer to File Server Service request, which is for SMB.

* [Video Tutorial](https://www.youtube.com/watch?v=wq-najIgsRU)

* ### [**SCAPY**](https://www.kali.org/tools/scapy/)
  Scapy is a powerful interactive packet manipulation tool, packet generator, network scanner, network discovery, packet sniffer, etc. It can for the moment replace hping, 85% of nmap, arpspoof, arp-sk, arping, tcpdump, tethereal, p0f.

* [Video Tutorial](https://www.youtube.com/watch?v=emHt0JvXDUY)

* ### [**TCPDUMP**](https://www.kali.org/tools/tcpdump/)
  This program allows you to dump the traffic on a network. tcpdump is able to examine IPv4, ICMPv4, IPv6, ICMPv6, UDP, TCP, SNMP, AFS BGP, RIP, PIM, DVMRP, IGMP, SMB, OSPF, NFS and many other packet types.

* [Video Tutorial](https://www.youtube.com/watch?v=1lDfCRM6dWk)

* ### [**WIRESHARK**](https://www.kali.org/tools/wireshark/)
  Wireshark is a network “sniffer” - a tool that captures and analyzes packets off the wire.

* [Video Tutorial](https://www.youtube.com/watch?v=2Wi6-cCexXA)

## Post Exploitation
Post-exploitation refers to any actions taken after a session is opened. A session is an open shell from a successful exploit or bruteforce attack. A shell can be a standard shell or Meterpreter. To learn more about the difference between each, see Manage Meterpreter and Shell Sessions.

* ### [**EVIL-WINRM**](https://www.kali.org/tools/evil-winrm/)
  WinRM (Windows Remote Management) is the Microsoft implementation of WS-Management Protocol. A standard SOAP based protocol that allows hardware and operating systems from different vendors to interoperate. Microsoft included it in their Operating Systems in order to make life easier to system administrators.

* [Video Tutorial](https://www.youtube.com/watch?v=tVgJ-9FJKxE)

* ### [**EXE2HEX**](https://www.kali.org/tools/exe2hexbat/)
  A Python script to convert a Windows PE executable file to a batch file and vice versa.

* [Video Tutorial](https://www.youtube.com/watch?v=EhWeQ7vkIg4)

* ### [**IMPACKET**](https://www.kali.org/tools/impacket/)
  Impacket is a collection of Python3 classes focused on providing access to network packets. Impacket allows Python3 developers to craft and decode network packets in simple and consistent manner. It includes support for low-level protocols such as IP, UDP and TCP, as well as higher-level protocols such as NMB and SMB.

* [Video Tutorial](https://www.youtube.com/watch?v=_LbyLBHebcs)

* ### [**MIMIKATZ**](https://www.kali.org/tools/mimikatz/)
  Mimikatz uses admin rights on Windows to display passwords of currently logged in users in plaintext.

* [Video Tutorial](https://www.youtube.com/watch?v=AZirvtZNIEw)

* ### [**NETCAT**](https://www.kali.org/tools/netcat/)
  A simple Unix utility which reads and writes data across network connections using TCP or UDP protocol. It is designed to be a reliable “back-end” tool that can be used directly or easily driven by other programs and scripts. At the same time it is a feature-rich network debugging and exploration tool, since it can create almost any kind of connection you would need and has several interesting built-in capabilities.

* [Video Tutorial](https://www.youtube.com/watch?v=ERZNMZZ2Uy0)

* ### [**POWERSHELL EMPIRE**](https://www.kali.org/tools/powershell-empire/)
  This package contains a post-exploitation framework that includes a pure-PowerShell2.0 Windows agent, and a pure Python Linux/OS X agent. It is the merge of the previous PowerShell Empire and Python EmPyre projects. The framework offers cryptologically-secure communications and a flexible architecture. On the PowerShell side, Empire implements the ability to run PowerShell agents without needing powershell.exe, rapidly deployable post-exploitation modules ranging from key loggers to Mimikatz, and adaptable communications to evade network detection, all wrapped up in a usability-focused framework.

* [Video Tutorial](https://www.youtube.com/watch?v=t6Lhp5ult1Q)

* ### [**POWERSPLOIT**](https://www.kali.org/tools/powersploit/)
  PowerSploit is a series of Microsoft PowerShell scripts that can be used in post-exploitation scenarios during authorized penetration tests.

* [Video Tutorial](https://www.youtube.com/watch?v=4b5c25x7Esw)

* ### [**PROXYCHAINS4**](https://dranolia.medium.com/understanding-proxychains4-conf-anonsurf-in-kali-linux-46471260e499)
  Proxychains is a powerful tool that enables users to run any application through a proxy server. It is particularly useful for maintaining anonymity and bypassing network restrictions. In Kali Linux, a popular penetration testing distribution, Proxychains is commonly used for concealing the identity of the user during security assessments.

* [Video Tutorial](https://www.youtube.com/watch?v=KWwOU1z5E8E)

* ### [**STARKILLER**](https://www.kali.org/tools/starkiller/)
  This package contains a Frontend for Powershell Empire. It is an Electron application written in VueJS.

* [Video Tutorial](https://www.youtube.com/watch?v=eGFBkeqPKK4)

* ### [**WEEVELY**](https://www.kali.org/tools/weevely/)
  Weevely is a stealth PHP web shell that simulate telnet-like connection. It is an essential tool for web application post exploitation, and can be used as stealth backdoor or as a web shell to manage legit web accounts, even free hosted ones.

* [Video Tutorial](https://www.youtube.com/watch?v=d54VN6oP9Y8)

## Forensics
Kali Linux is equipped with various forensic tools that facilitate digital forensics and incident response. These tools help investigators analyse digital evidence, recover lost data, and reconstruct digital incidents. The distribution supports various file systems and includes tools like The Sleuth Kit and Autopsy.

* ### [**AUTOPSY (ROOT)**](https://www.kali.org/tools/autopsy/)
  The Autopsy Forensic Browser is a graphical interface to the command line digital forensic analysis tools in The Sleuth Kit. Together, The Sleuth Kit and Autopsy provide many of the same features as commercial digital forensics tools for the analysis of Windows and UNIX file systems (NTFS, FAT, FFS, EXT2FS, and EXT3FS).

* [Video Tutorial](https://www.youtube.com/watch?v=HNJuQyWJhwg)

* ### [**BINWALK**](https://www.kali.org/tools/binwalk/)
  Binwalk is a tool for searching a given binary image for embedded files and executable code. Specifically, it is designed for identifying files and code embedded inside of firmware images. Binwalk uses the libmagic library, so it is compatible with magic signatures created for the Unix file utility.

* [Video Tutorial](https://www.youtube.com/watch?v=kVeAXSS-H8U)

* ### [**BULK_EXTRACTOR**](https://www.kali.org/tools/bulk-extractor/)
  bulk_extractor is a C++ program that scans a disk image, a file, or a directory of files and extracts useful information without parsing the file system or file system structures. The results are stored in feature files that can be easily inspected, parsed, or processed with automated tools. bulk_extractor also creates histograms of features that it finds, as features that are more common tend to be more important.

* [Video Tutorial](https://www.youtube.com/watch?v=5MTzP7THNKQ)
  
* ### [**HASHDEEP**](https://www.kali.org/tools/hashdeep/)
  hashdeep is a set of tools to compute MD5, SHA1, SHA256, tiger and whirlpool hashsums of arbitrary number of files recursively.

* [Video Tutorial](https://www.youtube.com/watch?v=IsA-ZLFqEfw)
  
## Repairing ToolS


* ### [**CHERRYTREE**](https://www.kali.org/tools/cherrytree/)
  CherryTree is a hierarchical note taking application, featuring rich text, syntax highlighting, images handling, hyperlinks, import/export with support for multiple formats, support for multiple languages, and more.

* [Video Tutorial](https://www.youtube.com/watch?v=vlmlb2kqbfo)

* ### [**CUTYCAPT**](https://www.kali.org/tools/cutycapt/)
  CutyCapt is a small cross-platform command-line utility to capture WebKit’s rendering of a web page into a variety of vector and bitmap formats, including SVG, PDF, PS, PNG, JPEG, TIFF, GIF, and BMP.

* [Video Tutorial](https://www.youtube.com/watch?v=AHioY5982z0)

* ### [**FARADAY START**](https://www.kali.org/tools/python-faraday/)
  Faraday introduces a new concept (IPE) Integrated Penetration-Test Environment a multiuser Penetration test IDE. Designed for distribution, indexation and analysis of the generated data during the process of a security audit.
  The main purpose of Faraday is to re-use the available tools in the community to take advantage of them in a multiuser way.

* [Video Tutorial](https://www.youtube.com/watch?v=QJUYEmhOUbA)

* ### [**MALTEGO INSTALLER**](https://www.kali.org/tools/maltego/)
  Maltego is an open source intelligence and forensics application. It will offer you timous mining and gathering of information as well as the representation of this information in a easy to understand format.

* [Video Tutorial](https://www.youtube.com/watch?v=JgSI-hlX870)

* ### [**PIPAL**](https://www.kali.org/tools/pipal/)
  All this tool does is to give you the stats and the information to help you analyse the passwords. The real work is done by you in interpreting the results.

* [Video Tutorial](https://www.youtube.com/watch?v=aU90UD0VAAM)

* ### [**RECORDMYDESKTOP**](https://www.kali.org/tools/recordmydesktop/)
  The application produces an ogg-encapsulated theora-vorbis file. recordMyDesktop tries to be as unobstrusive as possible by proccessing only regions of the screen that have changed

* [Video Tutorial](https://www.youtube.com/watch?v=m6BWgetTvPo)

## Social Engineering Tools
The Social-Engineer Toolkit (SET) is an open-source penetration testing framework designed for social engineering. SET has a number of custom attack vectors that allow you to make a believable attack in a fraction of time. These kind of tools use human behaviors to trick them to the attack vectors.

* ### [**MALTEGO (INSTALLER)**](https://www.kali.org/tools/maltego/)
  Maltego is an open source intelligence and forensics application. It will offer you timous mining and gathering of information as well as the representation of this information in a easy to understand format.

* [Video Tutorial](https://www.youtube.com/watch?v=JgSI-hlX870)

* ### [**MSF PAYLOAD CREATOR**](https://www.kali.org/tools/msfpc/)
  A quick way to generate various “basic” Meterpreter payloads using msfvenom which is part of the Metasploit framework.

* [Video Tutorial](https://www.youtube.com/watch?v=QyseHxzYDi4)

* ### [**SOCIAL ENGINEERING TOOLKIT (ROOT)**](https://www.kali.org/tools/set/)
  The Social-Engineer Toolkit (SET) is an open-source Python-driven tool aimed at penetration testing around Social-Engineering.

* [Video Tutorial](https://www.youtube.com/watch?v=NekjERW5PsM&t=20s)
