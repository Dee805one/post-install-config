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

<p>
<img src="https://i.imgur.com/3eIHubZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

To allow ticket submission, new users must be created within the system. Navigate to the Agent Panel, then open the Users menu and click on Add User. Enter the necessary account credentials for each user. For this lab, create two users: Karen and Ken. These users will be able to submit tickets, which will then be routed to agents for triage and resolution.

<p>
<img src="https://i.imgur.com/07xBCGZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

To effectively prioritize and manage tickets based on their level of impact, Service Level Agreements (SLAs) must be created. Within the Admin Panel, navigate to the Manage menu and select SLA. From there, create the necessary SLA plans. For this lab, three SLAs have been established:

SEV-A – Tickets must be resolved within 1 hour
SEV-B – Tickets must be resolved within 4 hours
SEV-C – Tickets must be resolved within 8 hours

These SLAs help ensure timely responses and resolutions based on the urgency and severity of each request.

<p>
<img src="https://i.imgur.com/jTH04GO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, Help Topics should be created to assist users in categorizing their issues accurately when submitting tickets. This helps agents quickly understand the nature of the problem and assign or respond accordingly. To create a new Help Topic, navigate to the Admin Panel, open the Manage menu, and select Help Topics. Click on Add New Help Topic and enter the relevant categories.

For this lab, the following Help Topics have been created for use when submitting tickets:

Business Critical Outage
Personal Computer Issues
Equipment Reset
Password Request

These topics will streamline the ticket submission process and improve the efficiency of issue resolution.
