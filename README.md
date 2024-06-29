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

- Item 1: Configure Roles, Departments, and Teams
- Item 2: Allow anyone to create tickets
- Item 3: Configure Agents and Users
- Item 4: Configure SLA
- Item 5: Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we will configure the Roles. From the Admin Panel, go to Agents -> Roles. Add "Supreme Admin" Role. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will configure the Deparments. From the Admin Panel, go to Agents -> Departments. Add "System Administrators" Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will configure the Teams. From the Admin Panel, go to Agents -> Teams. Add the "Level I Support" and "Level II Support" Teams.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, we will allow anyone to create tickets for our help desk. From the Admin Panel, go to Settings -> User Settings. Require registration and login to create tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will add some Agents. From the Admin Panel, go to Agents -> Add New. Add some agents here, and name them as you like (eg. Jane and John).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will add some Users. From the Admin Panel, go to Users -> Add New. Add some users here, and name them as you like (eg. Karen and Ken).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, we will configure SLA. From the Admin Panel, go to Manage -> SLA. Here we will add 3 SLA: 
<p>
- Sev-A (1 hour, 24/7)
</p>
<p>
- Sev-B (4 hours, 24/7)
</p>
<p>
- Sev-C (8 hours, business hours)
</p>
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, we will configure Help Topics. From the Admin Panel, go to Manage -> Help Topics. We will add the following Help Topics: 
<p>
- Business Critical Outage
</p>
<p>
- Personal Computer Issues
</p>
<p>
- Equipment Request
</p>
<p>
- Password Reset
</p>
</p>
<br />

<p>
Now we are ready to begin running our osTicket help desk that we set up!
</p>
<br />
