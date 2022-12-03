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

- Creating Roles, Departments, and Teams
- Creating Users (Ananimous and Agents)
- Defining SLA
- Install C++ Redistributable
- Installation of OSTicket and Setting up Permission

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/WFlshZm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Prior to the post installation configuration steps, the IP address of the virtual machine that was previously created was used to connect to remote desktop computer as shown above. Notably, this lab uses microsoft remote desktop however, on a mac computer microsoft remote desktop needed to be downloaded from app store. After logging in as an admin with two views to switch around (admin and agent view), the osTicket admin page was then open as shown above from the admin userface. Note, 'roles, department and users were then created' as first step of the osTicket post-installation configuration process.
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
In configuring a new role/department by syst-admin the configuration steps involves a click on Agent..> Roles..> on the admin panel. These steps were based on osTicket documentation on Azure. Note, roles are permision granted to agents based on department they have access to. In the above figure, a role was created called supreme admin and this agent was granted some permision by syst-admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/oWDckWR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A new role was created named 'supreme admin' with full permision on osTicket platform as shown above.
</p>
<br />

<p>
<img src="https://i.imgur.com/QmsjpvV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A new department was created named 'System Administrator' using default SLA and other in-built settings such as email addresses.
</p>
<br />

<p>
<img src="https://i.imgur.com/Su783jY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Team involves pulling different agents from various department into one single group to solve specific issue. From the above figure level 11 support team was created with no team leader assigned to it.
</p>
<br />

<p>
<img src="https://i.imgur.com/Rc4RjmB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The figure above shows the steps used in granting access to anyone (ananimous user) visiting osTicket website that intend creating a ticket. Meaning, those who are not agent-users of the platform could visit it and raise a ticket regarding any issues. On the admin panel a click on settings -->users and -->settings enables syst-admin to grant access to ananimouse users as shown above. Lastly, the registration required button was checked in completing the process above.
</p>
<br />

<p>
<img src="https://i.imgur.com/inrmJHh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This steps involves creating agents and assigning permission to them. Agents responds and resolve tickets created by users, the figure above shows the steps used in setting up agents in the admin panel.
</p>
<br />


<img src="https://i.imgur.com/kdU7UxO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A new agent was created named Jane Doe with a set user name and password as shown above. Aftr a click on the 'set password' button at the far-right both box were unchecked hence, agents were not required in changing their password when logging-in
</p>
<br />

<p>
<img src="https://i.imgur.com/inrmJHh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This steps involves creating agents and assigning permission to them. Agents responds and resolve tickets created by users, the figure above shows the steps used in setting up agents in the admin panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/inrmJHh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This steps involves creating agents and assigning permission to them. Agents responds and resolve tickets created by users, the figure above shows the steps used in setting up agents in the admin panel.
</p>
<br />
