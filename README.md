# HTB CWES

## Modules

- [1. Web Requests](#1-web-requests)
- [2. Introduction to Web Applications](#2-introduction-web-applications)
- [3. Using Web Proxies](#3-web-proxies)
- [4. Information Gattering - Web edition](#4-information-gattering)
- [5. Web Fuzzing](#5-fuzzing)
- [6. JavaScript Deobfuscation](#6-javascript-deobfuscation)
- [7. Cross Site Scripting - XSS](#7-xss)
- [8. SQL Injection](#8-sql-injection)
- [9. SQLMap](#9-sqlmap)
- [10. Command Injections](#10-command-injections)
- [11. File Upload Attacks](#11-file-upload)
- [12. Server Side Attacks](#12-server-side)
- [13. Login Brute Forcing](#13-login-brute-forcing)
- [14. Broken Authentication](#14-broken-authentication)
- [15. Web Attacks](#15-web-attacks)
- [16. File Inclusion](#16-file-inclusion)
- [17. Attacking GraphQL](#17-graphql)
- [18. API Attacks](#18-api-attacks)
- [19. Attacking Commnon Applications](#19-attacking-common-applications)
- [20. Bug Bounty](#20-bug-bounty)
_________

## 1. Web Requests

### 1.1 HTTP Fundamentals
**HyperText Transfer Protocol (HTTP)**

HTTP communication consists of a client and a server, where the client requests the server for a resource. The server processes the requests and returns the requested resource. The default port for HTTP communication is port 80, though this can be changed to any other port, depending on the web server configuration.

We enter a Fully Qualified Domain Name (FQDN) as a Uniform Resource Locator (URL) to reach the desired website, like www.hackthebox.com.


**URL**
Resources over HTTP are accessed via a URL, which offers many more specifications than simply specifying a website we want to visit. Let's look at the structure of a URL:

<img width="846" height="180" alt="image" src="https://github.com/user-attachments/assets/e7b3008a-af1d-4c9d-b6a4-4e7e2228a464" />

<img width="846" height="729" alt="image" src="https://github.com/user-attachments/assets/d15f2b88-b548-4895-b35a-f9f63a66eb7f" />

**HTTP Flow**

<img width="846" height="364" alt="image" src="https://github.com/user-attachments/assets/01802c1b-c7a2-408e-877f-2b4e350d5f3a" />

The diagram above presents the anatomy of an HTTP request at a very high level. The first time a user enters the URL (inlanefreight.com) into the browser, it sends a request to a DNS (Domain Name System) server to resolve the domain and get its IP. The DNS server looks up the IP address for inlanefreight.com and returns it. All domain names need to be resolved this way, as a server can't communicate without an IP address.

> [!NOTE]
> Our browsers usually first look up records in the local '/etc/hosts' file, and if the requested domain does not exist within it, then they would contact other DNS servers. We can use the '/etc/hosts' to manually add records to for DNS resolution, by adding the IP followed by the domain name.

### 1.2 HTTP Methods
_________
## 2. Introduction web applications
### 2.1 Introduction
### 2.2 Front End Components
### 2.3 Front End Vulnerabilities
### 2.4 Back End Components
### 2.5 Back End Vulnerabilities
_________
## 3. Web Proxies
### 3.1 Web Proxy
### 3.2 Web Fuzzer
### 3.3 Web Scanner
_________
## 4. Information Gattering
### 4.1 WHOIS
### 4.2 DNS & Subdomains
### 4.3 Fingerprinting
### 4.4 Crawling
### 4.5 Search Engine Discovery
### 4.6 Web Archives
### 4.7 Automating Recon
_________
## 5. Fuzzing
### 5.1 Directory and File Fuzzing
### 5.2 Parameter and Value Fuzzing
### 5.3 Virtual Hosting and Subdomain Fuzzing
### 5.4 Filtering Fuzzing Output
### 5.5 Validating Findings
### 5.6 Web APIs
_________
## 6. Javascript Deobfuscation
### 6.1 Obfuscation
### 6.2 Deobfuscation
_________
## 7. XSS
### 7.1 XSS Basics
### 7.2 XSS Attacks
### 7.3 XSS Prevention
_________
## 8. SQL Injection
### 8.1 Databases
### 8.2 MySQL
### 8.3 SQL Injections
### 8.4 Exploitation
### 8.5 Mitigation
_________
## 9. SQLMap
### 9.1 Building Attacks
### 9.2 Database Enum
### 9.3 Advanced SQLMap
_________
## 10. Command Injections
### 10.1 Exploitation
### 10.2 Filter Evasion
### 10.3 Prevention
_________
## 11. File Upload
### 11.1 Basic Exploitation
### 11.2 Bypasssing Filters
### 11.3 Other Upload Attacks
### 11.4 Prevention

________
## 12. Server Side Attacks
### 12.1 SSRF 
### 12.2 SSTI
### 12.3 SSI Injection
### 12.4 XSLT Injection
_________
## 13. Login Brute Forcing
### 13.1 Brute Force Attacks
### 13.2 Hydra
### 13.3 Medusa
### 13.4 Custom Wordlists
_________
## 14. Broken Authentication
### 14.1 Brute Force Attacks
### 14.2 Password Attacks
### 14.3 Authentication Bypasses
### 14.4 Session Attacks
_________
## 15. Web Attacks
### 15.1 HTTP Verb Tempering
### 15.2 IDOR
### 15.3 XXE
_________
## 16. File Inclusion
### 16.1 File Disclosure
### 16.2 Remote Code Execution (RCE)
### 16.3 Automation and Prevention
_________
## 17. GraphQL
### 17.1 Attacking GraphQL
_________
## 18. API Attacks
### 18.1 OWASP API 
_________
## 19. Attacking Common Application
### 19.1 Content Management Systems (CMS) 
### 19.2 Servelet Containers/Software Development
### 19.3 Infra/Networking Monitoring Tools
### 19.4 Customer Service Mgmt & Configuration 
### 19.5 Common Gateway Interfaces 
### 19.6 Thick Client Applications 
### 19.7 Miscellaneous Applications 
_________
## 20. Bug Bounty
### 20.1 Bug Bounty 101
### 20.2 Professionally Reporting Bugs

