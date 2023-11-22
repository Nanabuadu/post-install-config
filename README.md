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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/jAyRHYJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles: For the purpose of this project, we will add a new Supreme Admin role. Login to osTicket as an Admin. In the admin panel, click on Agents -> roles -> Add new Role -> type in Supreme Admin -> click on Add role. Supreme Admin will be added successfully.
</p>
<br />

<p>
<img src="https://i.imgur.com/V1MWGFn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments: For the purpose of this project, we will add a new System Administrators department with default settings. Login to osTicket as an Admin. In the admin panel, click on Agents -> Departments -> Add new Department -> type in System Administrators -> click on Add department. System Administrators will be added successfully.
</p>
<br />

<p>
<img src="https://i.imgur.com/mup1XUC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams: From the Admin panel, click on Agents -> Teams -> Add new Team -> Add level II Support -> click on Add team. Level II Support will be created successfully
</p>
<br />

<p>
<img src="https://i.imgur.com/rgkfH8E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets: Admin Panel -> click on Settings -> User settings -> Uncheck the "Require registration and login to create tickets" box
</p>
<br />

<p>
<img src="https://i.imgur.com/QtTQXTG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents: Admin Panel -> Agents -> Add New Agent -> Enter the Name, Email address, Username and set a new password. Move to the next tab (Access) and assign a department to the Agent. Click on Create after assigning the department
</p>
<br />

<p>
<img src="https://i.imgur.com/1rufplL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users: Go to the Agents Panel -> Users ->Add User -> Type in the name and Email address of the new user and click on Add User
</p>
<br />

<p>
<img src="https://i.imgur.com/Hx5Np3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Service Level Agreement (SLA): In the Admin Panel, go to Manage -> SLA -> CLick on Add New SLA Plan -> Set three different severity levels; SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), SEV-C (8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/tjlyK7h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics: Admin Panel -> Manage -> Help topics -> Add New Help Topic -> Type in the help topic (eg. Business Critical Outage) -> Add Help Topic.
</p>
<br />
