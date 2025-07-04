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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Set Up Roles, Departments, and Teams
- Control User Access and Ticket Creation
- Add Agents and Users
- Define Service Level Agreements (SLAs)
- Create Help Topics for Ticket Submission

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Begin by configuring roles to manage permission groups. Navigate to Admin Panel -> Agents -> Roles and create the necessary roles, such as Supreme Admin. Next, set up departments to control ticket visibility by going to Admin Panel -> Agents -> Departments. You can edit existing departments—such as renaming Support to Help Desk—or create new ones like SysAdmins and Networking. After departments are in place, configure cross-functional teams by visiting Admin Panel -> Agents -> Teams. Here, you can create teams like Online Banking by grouping agents from multiple departments.
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adjust ticket creation settings to control who can submit tickets. Go to Admin Panel -> Settings -> User Settings. Uncheck the option that allows unregistered users to create tickets. This ensures that only registered and logged-in users can create tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add your internal team members as agents by navigating to Admin Panel → Agents → Add New. For example, assign Jane to the SysAdmins department and John to the Help Desk department. After creating their accounts, reset their passwords to set new ones so you can log in as them for testing or configuration purposes.
Next, add your external users (customers) by going to Agent Panel → Users → Add New, and create users such as Karen and Ken.


</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Establish response time expectations by configuring SLAs. Go to Admin Panel -> Manage -> SLA and create SLA plans like Sev-A with a 1-hour grace period and 24/7 availability, Sev-B with a 4-hour grace period and 24/7 coverage, and Sev-C with an 8-hour grace period limited to business hours.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, set up help topics to guide users during ticket creation. Navigate to Admin Panel -> Manage -> Help Topics and define categories such as Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other to streamline ticket classification.
</p>
