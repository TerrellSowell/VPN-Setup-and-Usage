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
  - The initial action in this process is to visit www.whatismyipaddress.com from your home computer. Once there, you'll be required to obtain your IP address. Ensure that you save a copy of your IP address in a separate document for future reference. Copy the IPv4 address specifically
 ![vpn](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/a5b7e0fc-a4ac-4224-8bf0-4da75836538c)

* **Step 2: Log into VM and lookup IP address** 
  - Create a Windows 10 Virtual Machine (not shown in photos)
  - Log into the VM with Remote Desktop (not shown in photos)
  - After logging into the Windows 10 virtual machine browse to https://whatismyipaddress.com/ note in the photo below my geographic loaction as changed bc of the VM. Take note of the IP address in a text file
![vpn2](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/6cc496d4-3635-44d6-8eb1-6e4d1ff66936)

* **Step 3: Sign up for ProtonVPN and test the VPN connection)**
  - On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en
  -  Back within your VM, download the Proton VPN client
![vpn3](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/95f55d72-518c-4de4-80f3-b5215d15a9fd)
![vpn4](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/e29ab00b-074e-4ad0-a5d6-cfba22fded1d)

* **Step 4** 
  
  - Login to the VPN and choose a VPN server in yet another country if it allows for free 
  - Browse to https://whatismyipaddress.com/  and take note of this in a text file
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different
![vpn5](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/ab02d499-d1da-41ab-beb9-5b2bfb376f6f)
![vpn6](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/b570363e-3659-4dc0-8d9c-55cacbac964f)
![vpn7](https://github.com/TerrellSowell/VPN-Setup-and-Usage/assets/161978506/65ebd27a-8121-482f-9267-8ff532e98b26)

