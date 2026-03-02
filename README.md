# System-Administration-and-IT-Infrastructure-Services-Project

**Practical Task:** Basic Server Setup 

**Key Concepts:** Servers,virtualization,cloud services (DNS,DHCP) 

# IIS Web Server Deployment – Windows Environment

---

## Project Overview

This project demonstrates the deployment and configuration of a local web server using Microsoft Internet Information Services (IIS) on a Windows machine.  

**Objectives:**
- Install and configure IIS web server  
- Host static HTML content locally  
- Demonstrate client-server HTTP communication  
- Validate directory and service configuration  

---

## About IIS

(IIS) is a Microsoft web server that hosts websites and web applications. It enables Windows systems to process HTTP/HTTPS requests and deliver web content to browsers.

**Key Features:**
- Web content hosting (static and dynamic)  
- Port binding and request handling  
- Website and application management  
- Security configuration and authentication  

---

## System Architecture

```text
Client Browser
      │
      │ HTTP Request (Port 80)
      ▼
Windows Operating System
      │
      ▼
IIS Web Server (W3SVC)
      │
      ▼
C:\inetpub\wwwroot
      │
      ▼
HTML Response → Browser
