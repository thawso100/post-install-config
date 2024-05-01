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

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure SLAs
- Configure Help Topics

<h2>Configuration Roles </h2>

1. Admin Panel -> Agents -> Roles
2. Supreme Admin

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Configure Departments</h2>

1. Admin Panel -> Agents -> Departments
2. System Administrators
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Configure Teams </h2>

Admin Panel -> Agents -> Teams
1. Level I Support
2. Level II Support
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Allow anyone to create tickets</h2>
  
1. Admin Panel -> Settings -> User Settings
2. Registration Required: Require registration and login to create tickets
  
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Configure Agents</h2>
  
1. Admin Panel -> Agents -> Add New
2. Layla (I set Layla to be a System Admin and role as Supreme Admin)
3. Jamari (I set Jamari as Maintenance)
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Configure Users</h2>
  
1. Agent Panel -> Users -> Add New
2. Dimitri
3. Byleth
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Configure SLA</h2>
  
1. Admin Panel -> Manage -> SLA
2. Sev-A (1 hour, 24/7)
3. Sev-B (4 hours, 24/7)
4. Sev-C (8 hours, business hours)
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

It should look like this when you set up all Sev-Types.
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Configure Help Topics</h2>
  
1. Admin Panel -> Manage -> Help Topics
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
2. Business Critical Outage
3. Personal Computer Issues
4. Equipment Request
5. Password Reset
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

It should look like this 

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Update the New Ticket Options and follow the steps above. 

On the [next tutorial](https://github.com/thawso100/ticket-lifecycle), we will create Tickets and showcase the Ticket Lifecycle.


