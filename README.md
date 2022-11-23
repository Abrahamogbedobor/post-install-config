<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Creating Users
- Defining SLA
- Creating Severity Level
- Install C++ Redistributable
- Installation of OSTicket and Setting up Permission

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/WFlshZm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Prior to the post installation configuration steps, the IP address of the virtual machine that was previously created was used to connect to remote desktop computer as shown above. Notably, this lab uses microsoft remote desktop however, on a mac computer microsoft remote desktop needed to be downloaded from app store. After logging in as an admin with two views to switch around (admin and agent view), the osTicket admin page was then open as shown above from the admin userface. Note, 'users were then created' as first step of the osTicket post-installation configuration process.
</p>
<br />

<p>
<img src="https://i.imgur.com/S9Vw3lr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above interface comprises of two users of the osTicket platform such as 'admin and agent'. Admin on one hand is responsible with general administrative duties such as setting up platform, determining SLA/duties, and defining roles while agent on the other hand was the one using the platofrm and working on tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/W48pux7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In configuring a new role to a user(agent) by syst-admin the configuration steps involves a click on Agent..> Roles..> on the admin panel. These steps were based on osTicket documentation on Azure. Note, roles are permision granted to ageents based on department they have access to. In the above figure, a role was created called supreme admin and this agent was granted some permision by syst-admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/W48pux7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In configuring a new role to a user by syst-admin on Open Source Ticketing platform, the configuration steps involves hese navigation steps clickng Agent..> Roles..> on the admin panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In 
</p>
<br />
