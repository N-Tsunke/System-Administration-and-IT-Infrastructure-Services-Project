# System-Administration-and-IT-Infrastructure-Services-Project

# Practical Task: Basic Server Setup – Windows IIS

**Key Concepts:** Servers,virtualization,cloud services (DNS,DHCP)  

## Project Overview

This project demonstrates the setup of a local **Windows IIS (Internet Information Services)** web server. The purpose is to gain practical experience with server configuration, directory management, and HTTP services. The server hosts a simple test website and includes configuration for logging and optional directory browsing.

---

## IIS Installation

I installed IIS on my Windows machine via: Control Panel → Programs → Turn Windows features on or off → Internet Information Services

During installation, I selected the following components:

- **Web Management Tools**  
- **World Wide Web Services → Application Development Features** (ASP.NET optional)  

The installation completed successfully, making the server ready for configuration.

**Screenshot 1: IIS Installation Window**  
![IIS Installation](screenshots/iis-installation.png)  
*(Insert screenshot of Windows Features with IIS selected here)*

---

## Verify IIS Installation

To verify the installation, I opened a browser and navigated to:Http://localhost


The IIS default welcome page appeared, confirming successful installation.

**Screenshot 2: IIS Welcome Page**  
![IIS Welcome Page](screenshots/iis-welcome.png)  
*(Insert screenshot of default IIS page here)*

---

## Server Configuration

Using **IIS Manager**, I configured the server as follows:

- **Default Website Path:** `C:\inetpub\wwwroot`  
- Created a simple test HTML file (`index.html`) with “Hello World” content  
- Enabled **Directory Browsing** (optional) to allow viewing folder contents  
- Configured **Logging** to monitor HTTP requests  

**Screenshot 3: IIS Manager Interface**  
![IIS Manager](screenshots/iis-manager.png)  
*(Insert screenshot showing Default Website in IIS Manager here)*

**Screenshot 4: Website Folder Structure**  
![Folder Structure](screenshots/folder-structure.png)  
*(Insert screenshot of `C:\inetpub\wwwroot` showing `index.html` file here)*

---

## Verify Server Functionality

I tested the server by opening a browser and navigating to:Http://localhost/index.html


The test page loaded correctly, confirming that the server is functional.

**Screenshot 5: Test HTML Page**  
![Test Page](screenshots/test-page.png)  
*(Insert screenshot of your test HTML page here)*

---

## Services Explanation

The following services were configured on the server:

| Service | Purpose |
|---------|---------|
| **HTTP Service** | Handles incoming web requests and serves content to clients |
| **Directory Browsing (Optional)** | Allows users to view files in the website folder |
| **Logging** | Tracks requests for auditing and troubleshooting |
| **Default Website** | Serves as the main web root for hosting files |

---

## Summary

I successfully set up a local IIS web server on Windows. IIS handles HTTP requests and serves files from `C:\inetpub\wwwroot`. The server is capable of hosting web content locally and monitoring traffic through logging. Optional features like directory browsing can be enabled for easier management. This exercise provides hands-on experience with fundamental server configuration and system administration tasks.  
