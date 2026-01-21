# Networking and Web Fundamentals - Learning Journey

This document covers my progress in the "Pre-Security" path, focusing on how the web works and the deep mechanics of DNS.

## 🌐 How the Web Works
I explored the fundamental process that occurs when a user requests a website. Key concepts learned:
* **HTTP/HTTPS Protocols:** Understanding the request-response cycle between a client and a web server.
* **Web Components:** The role of web servers and browsers in rendering content.

## 📂 DNS in Detail (Domain Name System)
DNS is the "Phonebook of the Internet." I learned the distinction between the system and the server:
* **DNS System:** The hierarchical naming system built on a distributed database.
* **DNS Server:** The physical or virtual machine that processes queries and translates domain names into IP addresses.

### DNS Query Process
1. **Recursive Resolver:** The first stop for the DNS query.
2. **Root Name Server:** Directs the query to the correct TLD (Top-Level Domain) server.
3. **TLD Name Server:** Provides the IP of the authoritative name server.
4. **Authoritative Name Server:** Gives the final IP address of the requested domain.



## 🐧 Linux Fundamentals
I started my journey into the Linux command line, which is essential for cybersecurity operations. 
* Learned about the **Linux File System** hierarchy.
* Practiced basic terminal commands for navigation and file manipulation.

## 💡 Practical Connection
Today's DNS theory directly explains the **"Access Denied"** and **"Network Error"** issues I encountered in my Active Directory lab yesterday. When a system cannot resolve a hostname through DNS, it falls back to protocols like LLMNR, which creates a security vulnerability for credential harvesting. 