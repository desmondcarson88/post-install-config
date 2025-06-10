<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10</b> 

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h2 align="center">Configure Roles</h2>
<h4>For Grouping Permissions</h4>

<br />

<p>
<h3>Supreme Admin</h3>

</p>
<p>
  <img src="https://i.imgur.com/SXpTf20.png" height="75%" width="100%" alt="Definitions"/>

  - Admin Panel
  - Agent
  - Roles

<p>

<h3>Permissions</h3> 
</p>
   
  <img src="https://i.imgur.com/9fBmrZj.png" height="75%" width="100%" alt="Permissions"/>
  <img src="https://i.imgur.com/1sDBsuZ.png" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://i.imgur.com/2SVt7rt.png" height="75%" width="100%" alt="Even More Permissions"/>

  
- Select everything
- Add role
<img src="https://i.imgur.com/vJl5MPw.png" height="75%" width="100%" alt="Sys Admin Success"/>

</p>
<br />
<h2 align="center">Configure Departments</h2>
<h4>Ticket Visibility, Help Desk vs SysAdmins, vs Networking</h4>

<p>
<h3>System Administrators</h3>
</p>
<p>
  <img src="https://i.imgur.com/83gWQsO.png" height="75%" width="100%" alt="System Administrators"/>

- Admin Panel
- Agents
- Roles
  <img src="https://i.imgur.com/oGLXmQv.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h2 align="center">Configure Teams</h2>
<h4>Pull agent from different departments</h4>
<br />
<p>
<h3>Level II Support</h3>
</p>
<p>
  <img src="https://i.imgur.com/BnPrcDH.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<p>
  
- Admin Panel 
- Agents 
- Teams
</p>
<br />
<br />
<h2 align="center">Allow anyone to create ticket</h2>
<br />

<p>
<h4>Make sure "Require registration and login to create tickets" is not selected:</h4>
</p>
<p>
  <img src="https://i.imgur.com/QsJjOuM.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<p
  
- Admin Panel 
- Settings 
- User Settings
</p>
<br />
<br />
<h2 align="center">Configure Agents (Workers)</h2>
<br />

  <img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="agent one access"/>
  <img src="https://i.imgur.com/NcCP0v9.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/aKTJ01A.png" height="75%" width="100%" alt="agent two access"/>
</p>
<p>
  
- Admin Panel 
- Agents 
- Add New
- Example: Jane Doe, John Doe
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>

</p>
  <img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="user access"/>
<p>
  <p>
    
  - Admin Panel 
  - Users
  - Add New.
</p>
<p> - Ex: Ken User
</p>
<p>
  - Repeat the same above for Ex. Karen User.
</p>
<br />
<br />
<h2 align="center">Configure SLA</h2>
<br />

<p>
  <img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/izcD74X.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/xKzdp7w.png" height="75%" width="100%" alt="sev three"/>
</p>
<p>
  
- Admin Panel 
- Manage 
- SLA
- Sev-A (1 hour, 24/7).
- Sev-B (4 hours, 24/7).
- Sev-C (8 hours, business hours):
</p>
<br />
<br />
<h2 align="center">Configure Help Topics</h2>
<br />

<p>
  <img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/3Y7k2o1.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/Z0eIGea.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/ndOdtTZ.png" height="75%" width="100%" alt="password reset"/>
</p>
<p>
  
- Admin Panel 
- Manage 
- Help Topics
</p>
<p>
 - Business Critical Outage.
</p>
<p>
 - Personal Computer Issues.
</p>
<p>
 - Equipment Request.
</p>
<p>
 - Password Reset.
</p>
<br />
<br />
<p>
 Hopefully, this guide helped make things clearer and got you up and running without too much hassle. It’s a good idea to spend some time practicing how to triage and handle tickets.
</p>
<p>
 Being able to manage tickets well is super important for any help desk role, since you're often the first person customers talk to when they’re having issues with a product or service.
</p>
