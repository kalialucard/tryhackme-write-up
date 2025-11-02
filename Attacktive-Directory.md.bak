
Target - 10.201.92.91

```
PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
80/tcp    open  http          Microsoft IIS httpd 10.0
|_http-dombased-xss: Couldn't find any DOM based XSS.
|_http-title: IIS Windows Server
| http-methods: 
|_  Potentially risky methods: TRACE
|_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
|_http-csrf: Couldn't find any CSRF vulnerabilities.
|_http-server-header: Microsoft-IIS/10.0
88/tcp    open  kerberos-sec  Microsoft Windows Kerberos (server time: 2025-10-12 21:46:53Z)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP (Domain: spookysec.local0., Site: Default-First-Site-Name)
445/tcp   open  microsoft-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn_http    Microsoft Windows RPC over HTTP 1.0
636/tcp   open  tcpwrapped
|_ssl-ccs-injection: No reply from server (TIMEOUT)
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP (Domain: spookysec.local0., Site: Default-First-Site-Name)
3269/tcp  open  tcpwrapped
|_ssl-ccs-injection: No reply from server (TIMEOUT)
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
| ssl-cert: Subject: commonName=AttacktiveDirectory.spookysec.local
| Not valid before: 2025-10-11T21:07:32
|_Not valid after:  2026-04-12T21:07:32
|_ssl-date: 2025-10-12T22:30:13+00:00; -1s from scanner time.
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-csrf: Couldn't find any CSRF vulnerabilities.
|_http-dombased-xss: Couldn't find any DOM based XSS.
9389/tcp  open  mc-nmf        .NET Message Framing
47001/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-csrf: Couldn't find any CSRF vulnerabilities.
|_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
|_http-dombased-xss: Couldn't find any DOM based XSS.
|_http-title: Not Found
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
49670/tcp open  ncacn_http    Microsoft Windows RPC over HTTP 1.0
49671/tcp open  msrpc         Microsoft Windows RPC
49673/tcp open  msrpc         Microsoft Windows RPC
49677/tcp open  msrpc         Microsoft Windows RPC
49688/tcp open  msrpc         Microsoft Windows RPC
49698/tcp open  msrpc         Microsoft Windows RPC
49806/tcp open  msrpc         Microsoft Windows RPC
No exact OS matches for host (If you know what OS is running on it, see https://nmap.org/submit/ ).
TCP/IP fingerprint:
OS:SCAN(V=7.95%E=4%D=10/12%OT=53%CT=1%CU=41898%PV=Y%DS=4%DC=T%G=Y%TM=68EC2C
OS:03%P=x86_64-pc-linux-gnu)SEQ(SP=100%GCD=2%ISR=10D%TI=RD%CI=I%II=I%TS=U)S
OS:EQ(SP=104%GCD=2%ISR=10A%TI=I%CI=I%II=I%SS=S%TS=U)SEQ(SP=106%GCD=1%ISR=10
OS:9%TI=I%CI=I%II=I%SS=O%TS=U)SEQ(SP=106%GCD=2%ISR=108%TI=I%CI=I%II=I%SS=S%
OS:TS=U)SEQ(SP=FD%GCD=1%ISR=109%TI=I%CI=I%II=I%SS=S%TS=U)OPS(O1=M509NW8NNS%
OS:O2=M509NW8NNS%O3=M509NW8%O4=M509NW8NNS%O5=M509NW8NNS%O6=M509NNS)WIN(W1=F
OS:FFF%W2=FFFF%W3=FFFF%W4=FFFF%W5=FFFF%W6=FF70)ECN(R=Y%DF=Y%T=80%W=FFFF%O=M
OS:509NW8NNS%CC=Y%Q=)T1(R=Y%DF=Y%T=80%S=O%A=S+%F=AS%RD=0%Q=)T2(R=Y%DF=Y%T=8
OS:0%W=0%S=Z%A=S%F=AR%O=%RD=0%Q=)T3(R=Y%DF=Y%T=80%W=0%S=Z%A=O%F=AR%O=%RD=0%
OS:Q=)T4(R=Y%DF=Y%T=80%W=0%S=A%A=O%F=R%O=%RD=0%Q=)T5(R=Y%DF=Y%T=80%W=0%S=Z%
OS:A=S+%F=AR%O=%RD=0%Q=)T6(R=Y%DF=Y%T=80%W=0%S=A%A=O%F=R%O=%RD=0%Q=)T7(R=Y%
OS:DF=Y%T=80%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)U1(R=Y%DF=N%T=80%IPL=164%UN=0%RIP
OS:L=G%RID=G%RIPCK=G%RUCK=G%RUD=G)IE(R=Y%DFI=N%T=80%CD=Z)

Network Distance: 4 hops
Service Info: Host: ATTACKTIVEDIREC; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
|_smb-vuln-ms10-054: false
|_smb2-time: Protocol negotiation failed (SMB2)
| smb2-security-mode: 
|   3:1:1: 
|_    Message signing enabled and required
|_smb-vuln-ms10-061: Could not negotiate a connection:SMB: Failed to receive bytes: ERROR
|_samba-vuln-cve-2012-1182: Could not negotiate a connection:SMB: Failed to receive bytes: ERROR
|_clock-skew: -1s

TRACEROUTE (using port 21/tcp)
HOP RTT       ADDRESS
1   357.72 ms 10.21.0.1
2   ... 3
4   357.92 ms 10.201.92.91


```

```
### nmap

Network/port scanner. Finds open ports and services so you know what targets/methods are available (SMB, Kerberos, HTTP, RDP, etc.).  
Example: `nmap -A -T4 target` — service/version detection + common scripts.

### enum4linux

SMB/NetBIOS/Windows enumeration wrapper. Pulls domain names, user lists, share names, policy info from SMB. Good for quickly harvesting usernames and share contents.  
Example: `enum4linux -A target`

### smbclient

SMB client like `ftp` for Windows shares. Browse, download, and upload files from SMB shares. Use it to check for interesting files (backups, creds).  
Example: `smbclient //target/share -U user`

### Kerbrute

Kerberos username enumeration and bruteforce tool. Quickly tells you which usernames exist on the domain (and can test for pre-auth disabled accounts). Useful early for Kerberos attacks.  
Example: `kerbrute userenum --dc domain -d domain userlist.txt`

### Impacket (GetNPUsers.py, secretsdump.py, psexec.py, wmiexec.py, atexec.py, etc.)

A toolkit of Python programs for Windows/AD protocol interactions. Think of it as a multi-tool for AD post-exploitation.

- **GetNPUsers.py** — AS-REP roasting helper: requests AS-REP for accounts without pre-auth and extracts crackable hashes.  
    Example: `python3 GetNPUsers.py domain/username -request`
    
- **secretsdump.py** — Dumps NTLM/LSA secrets and SAM/AD hashes from a machine or DC (using valid creds or RPC). Great for getting Administrator hash.  
    Example: `python3 secretsdump.py user@domain -just-dc`
    
- **psexec.py** — Pass-the-Hash / remote command execution using SMB/RPC. Use when you have an NTLM hash to spawn a remote shell.  
    Example: `python3 psexec.py Administrator@target -hashes LM:NT`
    
- **wmiexec.py / atexec.py / smbexec.py** — alternative remote command execution methods (WMI, scheduled task, SMB exec) when psexec isn’t ideal.
    

### GetNPUsers / AS-REP Roasting (technique, not a tool)

If an account has Kerberos pre-auth disabled, you can request a response that contains an encrypted blob that is crackable offline — this is what GetNPUsers gets for you.

### hashcat

Password cracking tool that uses GPU/CPU to brute/wordlist/rule crack hashes (NTLM, Kerberos AS-REP, etc.). Fast and flexible; pick the correct hash mode for the hash type.  
Example: `hashcat -m 18200 hash.txt wordlist.txt` (18200 = Kerberos 5 AS-REP)

### base64 (coreutils)

Simple encoder/decoder for Base64 data. Useful when you find encoded credential files/backups.  
Example: `base64 -d file > decoded`

### smbclient / mount.cifs / netcat (file access & transfer)

Tools you’ll use to pull files off shares (`smbclient`, `mount -t cifs`) or move shells and files (`nc`).

### winrm / rdesktop / freerdp / xfreerdp (remote access)

If RDP or WinRM is open, these let you connect interactively (not covered deeply in the writeup, but common follow-ups).

---

# Short workflow mapping (why these together)

1. **nmap** → find services.
    
2. **enum4linux / Kerbrute** → harvest usernames, shares, and validate accounts.
    
3. **GetNPUsers.py (Impacket)** → extract AS-REP hashes for users without pre-auth.
    
4. **hashcat** → crack those hashes offline.
    
5. **smbclient** → access SMB shares with cracked creds; find encoded backups.
    
6. **base64** → decode found blobs/files for more creds.
    
7. **secretsdump.py** → dump additional hashes (possibly Administrator).
    
8. **psexec.py** (or wmiexec) → use hash or creds to get an elevated shell.

```