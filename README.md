<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/WkdLqR2.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
  <p>
<img src="https://i.imgur.com/pRRQcLx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  <p>
<img src="https://i.imgur.com/e5x9O7m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With osTicket successfully installed, the next step is to begin configuring it for use as a ticketing system. It's important to note that osTicket features two distinct panels—Admin Panel and Agent Panel—each with its own set of configuration options. To determine which panel you are currently using, check the top-right corner of the osTicket interface. If it says Agent Panel, you are currently in the Admin Panel, and vice versa.

The first configuration task is to create a new role named Supreme Admin. For the purposes of this lab, this role will be granted full permissions to demonstrate complete administrative access. To create the role, navigate to the Admin Panel, then go to the Agents menu. Click on Roles, and from there, create a new role titled Supreme Admin with all available permissions enabled.
</p>
<br />

<p>
<img src="https://i.imgur.com/9xRM1yg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step is to create a new Department for System Administrators. While in the Admin Panel, navigate to the Agents menu and select Departments. From there, create a new department named System Administrators to help organize and assign tickets more effectively within osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/iLUuOp9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next a Level II Support Team will be created to work alongside the existing Level I Support Team. Within the Admin Panel, navigate to the Agents menu and select Teams. From there, create a new team named Level II Support. This allows for better ticket escalation and support organization within osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/KxkwNZA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/siOkOna.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

New agents must be created and assigned to the ticket queue. Within the Admin Panel, go to the Agents menu and click on Add New Agent. Fill in the required account credentials and details for each agent. For this lab, create two new agents: Jane Doe and John Doe. These agents will be responsible for managing and responding to support tickets within the system.
