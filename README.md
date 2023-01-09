
<p align="center">
<img src="https://i.imgur.com/1wk3imL.jpg" alt="osTicket logo"/>
</p>

<h1>VPN - Installation and Usage</h1>
This tutorial outlines the install and usage of a Virtual Private Network.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Intallation and Usage Objectives</h2>

- Create Virtual Machine in Azure
- Sign up for ProtonVPN and test the VPN connection

<h2>Steps</h2>

<p>
<img src="https://i.imgur.com/1Tt5XdQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/tHauoaH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/9EhRjco.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Virtual Machine in Azure
  
  - Browse to https://whatismyipaddress.com/ and take note of this in a text file
  - Create a Resource Group
  - Create a Windows 10 Virtual Machine in another geographic location (try a different country)
    
     i. Log into the VM with Remote Desktop
   
    ii. Browse to https://whatismyipaddress.com/ and take note of this in a text file
    
    
    <p>
<img src="https://i.imgur.com/oR1xitf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/17S6nXY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xIfwNf3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vGPxdm2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign up for ProtonVPN and test the VPN connection

- On your actual computer, sign up for the free version of Proton VPN 
- Back within your VM, download the Proton VPN client

  i. Login to the VPN and choose a VPN server in yet another country (such as Japan)
  
  ii. Browse to https://whatismyipaddress.com/  and take note of this in a text file
  
 - Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

