<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/4kEQtECcO-U?si=sfIpYmbSVKiyn37p)

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
- Configure Agents (workers)
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics
- Archive Maintenance Department

<h2>Configuration Steps</h2>

<p>
<img width="623" alt="image" src="https://github.com/user-attachments/assets/d55872ea-f538-4579-bfdb-4d8c9cef4e76" />
<img width="425" alt="image" src="https://github.com/user-attachments/assets/178fbc63-b9b9-44e3-abf0-65a8334e4297" />
</p>
<p>
Configure Roles (for grouping permissions)

Admin Panel -> Agents -> Roles

Supreme Admin
</p>
<br />

<p>
<img width="482" alt="image" src="https://github.com/user-attachments/assets/d15a4bf5-d88b-471b-88f2-b87180c5c270" />
</p>
<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)

Admin Panel -> Agents -> Departments

SysAdmins
</p>
<br />

<p>
<img width="461" alt="image" src="https://github.com/user-attachments/assets/2d6e7362-80e0-45a2-85ff-a1f7d454b3b2" />
</p>
<p>
Configure Teams

Admin Panel -> Agents -> Teams (Pull Agents from different Departments)

Online Banking
</p>
<br />

<p>
<img width="499" alt="image" src="https://github.com/user-attachments/assets/925a4bcc-de30-4f90-9215-dc1932038b2b" />
</p>
<p>
Allow anyone to create tickets

Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)

Registration Required: Require registration and login to create tickets 
</p>
<br />

<p>
<img width="496" alt="image" src="https://github.com/user-attachments/assets/e70c0da6-f8d1-43e0-9538-e100c9cc369a" />
<img width="412" alt="image" src="https://github.com/user-attachments/assets/96a83090-78d9-438f-92fb-df69e319be05" />
<img width="391" alt="image" src="https://github.com/user-attachments/assets/52e56575-2451-4390-b87c-1faa41aee15e" />
<img width="428" alt="image" src="https://github.com/user-attachments/assets/f1af26b2-d09a-4388-bd42-1e72af2a0ad8" />
</p>
<p>
Configure Agents (workers)

Admin Panel -> Agents -> Add New

Jane (Dept: SysAdmins)

For the password, just put "password1"
</p>
<br />

<p>
<img width="472" alt="image" src="https://github.com/user-attachments/assets/49ff1347-b60f-4e26-b05e-df8418677395" />
<img width="412" alt="image" src="https://github.com/user-attachments/assets/68dd3988-087b-4272-b017-7d9c38dd60cf" />
<img width="421" alt="image" src="https://github.com/user-attachments/assets/a9f27aad-c3ee-48d8-8278-fdb76e9dc2d7" />
</p>
<p>
Configure Agents (workers)

Admin Panel -> Agents -> Add New

John (Dept: Support)

For the password, just put "password1"
</p>
<br />

<p>
<img width="513" alt="image" src="https://github.com/user-attachments/assets/3f87dce7-9f80-4ab8-9b38-6cca92e88d77" />
</p>
<p>
Configure Users (customers)

Agent Panel -> Users -> Add New

Karen
</p>
<br />

<p>
<img width="518" alt="image" src="https://github.com/user-attachments/assets/4c787638-5a41-4825-af54-b756bf974799" />
<img width="505" alt="image" src="https://github.com/user-attachments/assets/473f3f84-d57f-4dcb-aacd-9b52a7ee179c" />
<img width="496" alt="image" src="https://github.com/user-attachments/assets/56796db4-e815-48fe-959e-b35c097043d6" />
</p>
<p>
Configure SLA

Admin Panel -> Manage -> SLA

Sev-A (Grace Period: 1 hour, Schedule: 24/7)

Sev-B (Grace Period: 4 hours, Schedule: 24/7)

Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />

<p>
<img width="455" alt="image" src="https://github.com/user-attachments/assets/c3030ff7-e83d-4925-830a-8a40afafee5d" />
<img width="429" alt="image" src="https://github.com/user-attachments/assets/7ae314da-19eb-41c1-b249-d4fc78a77ecd" />
<img width="412" alt="image" src="https://github.com/user-attachments/assets/faa8fbe0-d9fa-412b-843d-acd3c209a4c9" />
<img width="434" alt="image" src="https://github.com/user-attachments/assets/e213b6bc-cbfe-4cc1-be5d-9dfc4b0a171a" />
<img width="418" alt="image" src="https://github.com/user-attachments/assets/720bdeb0-2592-4c08-b6ce-e5414eb11650" />
</p>
<p>
Configure Help Topics (For when users create a ticket)

Admin Panel -> Manage -> Help Topics

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

Other
</p>
<br />

<p>
<img width="422" alt="image" src="https://github.com/user-attachments/assets/32012304-7a39-4622-ad55-d036ce7dff16" />
</p>
<p>
Admin Panel -> Agents -> Departments -> Click on Maintenance -> Status: Archived
</p>
<br />
