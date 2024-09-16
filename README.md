<h1>Windows Server 2019 Deployment on VirtualBox</h1>

 
<h2>Description</h2>
This project demonstrates the setup, installation, and configuration of Windows Server 2019 on VirtualBox. It covers the process from creating a virtual machine to installing the server, followed by basic configurations such as server roles, networking, and updates. The goal is to provide a functional Windows Server 2019 environment for further IT administration tasks or any cybersecurity projects.
<br />


<h2>Utilities Used</h2>

- <b>Virtual Box</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<b>Key steps included:</b>

- Installation and Configuration: Windows Server 2019 was installed from ISO, with VirtualBox providing the virtual environment.<br />
- Active Directory Setup: Configured Active Directory Domain Services (AD DS), enabling centralized user management, group policies, and authentication.<br />
- DNS & DHCP Services: Deployed and configured DNS and DHCP services to manage and automate IP address distribution and domain name resolution within the virtual network.<br />
- User Management & Group Policies: Set up multiple users and configured group policies to enforce security and administrative controls.<br />
- Firewall and Security Settings: Applied security baselines, including Windows Defender Firewall and specific role-based access controls to safeguard the server environment.
<br />


<p align="center">
a brief description of Windows Server 2019 deployment project on VirtualBox <br/>
<img src="https://imgur.com/yPkHuWD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

  <h2>Setup and Installation Steps:</h2>
<b>Install VirtualBox:</b>

- Download and install the latest version of VirtualBox.<br />
- Follow the installation wizard to complete the installation on your host machine.<br />

<b>Create a New Virtual Machine:</b>

- Open VirtualBox, click on New to create a new virtual machine.<br />
- Set the Name (e.g., "Windows Server 2019"), select Type: Microsoft Windows, and choose Version: Windows 2019 (64-bit).<br />
- Allocate at least 4 GB of RAM and 50 GB of storage.<br />

<b>Attach Windows Server 2019 ISO:</b>

- Under Settings, go to Storage and attach the Windows Server 2019 ISO file as a virtual optical disk.<br />

<b>Start the Virtual Machine:</b>

- Boot the virtual machine and begin the Windows Server 2019 installation.<br />
<img src="https://imgur.com/fvo9j7R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<b>Install Windows Server 2019:</b>

- Follow the prompts to select the language, time, and keyboard preferences.<br />
- Choose the edition of Windows Server 2019 (with GUI) and proceed with the installation.<br />

<b>Configure Initial Settings:</b>

- Once installed, set up the administrator password.<br />
- Open Server Manager and configure basic settings like the computer name, IP address, and enabling remote desktop.<br />

<b>Install Roles and Features:</b>

- Use the Server Manager to install necessary roles such as Active Directory Domain Services or DHCP.<br />

<b>Install Windows Updates:</b>

- Ensure that all available updates are installed to keep the server secure.<br />
<img src="https://imgur.com/jlixSy7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
