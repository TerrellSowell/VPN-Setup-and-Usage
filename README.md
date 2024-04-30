# VPN Setup and Usage
<img width="291" alt="PROTON LOGO" src="https://github.com/codeByKelvinn/creating-a-VPN/assets/110644520/2bf76f25-7f66-4893-b7ee-76f565cf42b1">

## Objective

The VPN Lab is aimed establish how VPN's work and to deepen my understanding on how remote desk protocol works. The primary focus was to ingest and analyze IP addresses within my home computer, a virtual machine, and VPN.

### Skills Learned<h2>

- Advanced understanding of VPN concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize VPN IP addresses and remote desk top patterns.

### Tools and Technology Used<h2>

- Proton VPN for log ingestion and analysis.
- Mircosoft Azure (Virtual Machine/Computer)
- Windows 10

### What is a VPN and why do we need it?
A VPN, which stands for virtual private network, establishes a digital connection between your computer and a remote server owned by a VPN provider, creating a point-to-point tunnel that encrypts your personal data, masks your IP address, and lets you sidestep website blocks and firewalls on the internet.

## Steps

* **Step 1**
  The initial action in this process is to visit www.whatismyipaddress.com. Once there, you'll be required to obtain your IP address. Ensure that you save a copy of your IP address in a separate document for future reference. Copy the IPv4 address specifically
  (Create Virtual Machine in Azure)
Browse to https://whatismyipaddress.com/ and take note of this in a text file
Create a Resource Group
Create a Windows 10 Virtual Machine in another geographic location (try a different country)
Log into the VM with Remote Desktop
Browse to https://whatismyipaddress.com/ and take note of this in a text file

(Sign up for ProtonVPN and test the VPN connection)
On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
Back within your VM, download the Proton VPN client
Login to the VPN and choose a VPN server in yet another country (such as Japan)
Browse to https://whatismyipaddress.com/  and take note of this in a text file
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

(Clean up Azure resources)
Delete the resource group you created in Step 2
Ensure the resources/Resource Group has been deleted.

