<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams
- Allow anyone to create tickets
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/pE8ritz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Configre Roles
  - Admin Panel -> Agents -> Roles
  - Create a new Role -> Supreme Admin -> Check Permissions -> Add Role

</p>
<br />

<p>
<img src="https://i.imgur.com/pE8ritz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Configure Departments
  - Admin Panel -> Agents -> Departments
  - Add a New Department -> System Administrator -> Create Department
  
</p>
<br />

<p>
<img src="https://i.imgur.com/318VzW3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Configure Teams
  - Admin Panel -> Agents -> Teams
    - Create a New Team -> Level II Support -> Create Team
    
</p>
<br />

<p>
<img src="https://i.imgur.com/XHvOtLG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Allow anyone to create tickets
  - Admin Panel -> Settings -> User Settings
  - Registration Required: Require registration and login to create tickets <- Should be unchecked to allow usage without registration for lab purposes
  
</p>
<br />

<p>
<img src="https://i.imgur.com/8yiKUu0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Configure Agents (workers)
  - Admin Panel -> Agents -> Add New
    - Fill in information for new woker #1 (Jane)
    - Fill in information for new worker #2 (John)

</p>
<br />

<p>
<img src="https://i.imgur.com/6BgOZEa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Configure Users (customers)
  - Agent Panel -> Users -> Add New
    - Fill in information for new user #1 (Karen)
      - Assign one user Admin roles previously configured for lab purposes
    - Fill in information for new user #2 (Ken)
  
</p>
<br />

<p>
<img src="https://i.imgur.com/jGue3Az.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Configure SLA
  - Admin Panel -> Manage -> SLA
    - Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)
  
</p>
<br />

<p>
<img src="https://i.imgur.com/ghYCdAN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
- Configure Help Topics
  - Admin Panel -> Manage -> Help Topics
    - Business Critical Outage
    - Personal Computer Issue
    - Equipment Request
    - Password Reset
