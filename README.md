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

- Configure Roles, Departments and Teams
- Configure Agents(workers and customers)
- Configure SLA
- Configure Help Topics

<h2>Configure Roles</h2>

- Supreme Admin
<p> <strong>Roles</strong> are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.

<p> 
<img src="https://i.imgur.com/gmx5RSz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Admin Panel -> Agents -> Roles
<p>
2. Add new Role
<p>
<img src="https://i.imgur.com/Pdmnf9d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name Role as "Supreme Admin"
</p>
<br />

<p>
<img src="https://i.imgur.com/LbkdN29.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under "Permissions" -> "Tickets" Check all boxes
<p>
<br />

<p>
<img src="https://i.imgur.com/nbjboyb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Under the "Tasks" tab check all boxes
<p>
2. Save Changes
</p>
<br />

<h2>Configure Departments</h2>

- System Administrators

<p>
<img src="https://i.imgur.com/GJHnQJp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Admin Panel -> Agents -> Departments
<p>
2. Add new Department

</p>
<br />

<p>
<img src="https://i.imgur.com/9CFvLd5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Gi1dpyZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Name the new Department as "System Administrators"
<p>
2. Leaving all Settings as Default
<p>
3. Create Dept
<p>

<h2>Configure Teams</h2>

- Level I
- Level II
<p> <strong>Teams</strong> allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.

</p>
<br />

<p>
<img src="https://i.imgur.com/juryWLs.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Admin Panel -> Agents -> Teams
<p>
2. Add New Team
</p>
<br />

<p>
<img src="https://i.imgur.com/LD0BEWM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/l2Ge4MX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Name the new Team "Level II Support"
<p>
2. Create Team
</p>
<br />

<h2>Allow Anyone to Create Tickets</h2>

</p>
<br />

<p>
<img src="https://i.imgur.com/7nDHBmO.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Admin Panel -> Settings -> User Settings
<p>
2. Make sure under "Registration Required" Box is unchecked
<p>
3. Save Changes
</p>
<br />

<h2>Configure Agents (workers)</h2>

-Jane
-John

<p> <strong>Agents</strong> are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
</p>
<br />

<p>
<img src="https://i.imgur.com/6yYFjv3.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Add New
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/6OgU7Vx.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  1. Add "Jane Doe" in first and last name
<p>
  2. Email Address can be anything i just put "jane.doe@osticket"
<p>
  3. In Username put as "jane.doe"
<p>
<img src="https://i.imgur.com/zKbQpBi.png" width="80%" alt="Disk Sanitization Steps"/>
<p>
  Here you can set the password for the agents or send the agent a password reset email
</p>
<br />

<p>
<img src="https://i.imgur.com/DW4Q9So.png" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/CO5xu1h.png" width="80%" alt="Disk Sanitization Steps"/>
  <p>
    You can also assign agents different departments and Roles. Such as System Administrator and Supreme Admin.
