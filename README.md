# System-Administration-and-IT-Infrastructure-Services-Project

# Practical Task: Basic Server Setup – Windows IIS

**Key Concepts:** Servers,virtualization,cloud services (DNS,DHCP)  

## Project Overview

This project demonstrates the setup of a local **Windows IIS (Internet Information Services)** web server. The purpose is to gain practical experience with server configuration, directory management, and HTTP services. The server hosts a simple test website and includes configuration for logging and optional directory browsing.

---

### Step 1: Windows IIS Installation

During installation, I selected the following components:

- **Web Management Tools**  
- **World Wide Web Services → Application Development Features** (ASP.NET optional)  

The installation completed successfully, making the server ready for configuration.

**Screenshot 1: IIS Installation Window**  
<img width="674" height="486" alt="IIS 3" src="https://github.com/user-attachments/assets/1ff8f08e-4b27-4fa4-9c8b-425cafda5414" />

---

### Step 2: Verify Windows IIS Installation

To verify the installation, I opened a browser and navigated to:http://localhost

The IIS default welcome page appeared, confirming successful installation.

**Screenshot 2: IIS Welcome Page**  
<img width="1427" height="699" alt="IIS - Localhost" src="https://github.com/user-attachments/assets/c4b9ffa3-87b9-4585-9906-7462cc72f8eb" />


---

### Step 3: Server Configuration

Using **IIS Manager**, I configured the server as follows:

- **Default Website Path:** `C:\inetpub\wwwroot`  
- Created a simple test HTML file (`index.html`) with “Hello World” content  
- Enabled **Directory Browsing** (optional) to allow viewing folder contents  
- Configured **Logging** to monitor HTTP requests  

**Screenshot 3: IIS Manager Interface**  
<img width="1292" height="618" alt="configure logging" src="https://github.com/user-attachments/assets/cb2b49f7-0e38-46a0-8f2b-c12c14cc0910" />

**Screenshot 4: Website Folder Structure**  
<img width="764" height="188" alt="Website folder structure" src="https://github.com/user-attachments/assets/a1d93438-3b61-4d91-b22d-67a8c5619d7c" />
---

### Step 4: Verify Server Functionality

I tested the server by opening a browser and navigating to:http://localhost/index.html


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
