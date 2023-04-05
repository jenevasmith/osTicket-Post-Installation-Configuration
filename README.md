# osTicket Post Installation Configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

This tutorial outlines the osTicket: post-installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket (help desk ticketing system)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a virtual machine in Microsoft Azure.
- Set up osTicket in the browser.
- Browse to your <a href="http://localhost/osTicket/scp/login.php">help desk login page.
- Browse <a href="http://localhost/osTicket/">End Users osTicket URL.

<h2>Post-Installation Steps</h2>

- Configure Roles
<p>

<p>
In the Admin Panel, within the Agents tab, select Roles, then click Add New Role. <img src="https://imgur.com/VW2TU8x.png">
</p>
<p>
  
- Supreme Admin
 <p>
    
<p> 
Name the New Role, “Supreme Admin,” then click the “Add Role” button. <img src="https://imgur.com/8gDvdux.png">
</p>
<p>

  
- Configure Departments

<p>
In the Admin Panel, within the Agents tab, select Departments, then click the “Add New Department” button. <img src="https://imgur.com/aeO9g3A.png">
</p>
<p>

  
- System Administrators
  
<p>
Add a New Department within the Settings named, “System Administrators,” then click the Create Dept button. <img src="https://imgur.com/XAWStbW.png">
</p>
<p>

- Configure Teams
  
<p>
In the Admin Panel, within the Agents tab, select Teams, then click on the Add New Team button. <img src="https://imgur.com/jQjYPjM.png">
</p>
<p>

- Level I Support
  
<p>
Notice how Level I Support is a default team within osTicket. <img src="https://imgur.com/2n0dQ2U.png">
</p>
<p>
  
- Level II Support
  
<p>
Click the Add New Team button. Then, name the team, “Level II Support.” <img src="https://imgur.com/nU04zbv.png">
</p>
<p>
  
- Allow anyone to create tickets. 
  
<p>
In the Admin Panel, click the Settings tab, and select users. <img src="https://imgur.com/sEALYHY.png">
</p>
<p>
  
- Registration
  
<p>
Do not require registration to create tickets, by unchecking the box next to “Registration Required.” <img src="https://imgur.com/MtVEbBD.png">
</p>
<p>
  
- Configure Agents (Help Desk Professionals)
  
<p>
In the Admin Panel, within the Agents tab, select Agents, then click the Add New Agent button. <img src="https://imgur.com/2b0C19Z.png">
</p>
<p>
  
- Agents
  
<p>
In the Account tab, add a New Agent - Name: “Jane Doe,” Email Address: “jane.doe@osticket.com,” Username: “jane.doe.” Click the set password button. Select the password and password settings of your choice.<img src="https://imgur.com/bQtgYEX.png">
</p>
<p>
  
  - Access
  
<p>
Click the Access tab to select the agent’s Department, ensuring that the Primary Department “System Administrators,” and Role, “System Admin” have been selected. <img src=https://imgur.com/gwhIuJT.png">
</p>
<p>
  
 - Support
  
<p>
In the Extended Access section, click the “Select Department” drop down menu, then select “Support.” <img src="https://imgur.com/nLKMn96.png">
                               
- Supreme Admin
  
<p>
In the Extended Access section, click on the “Select Role” drop down menu and select the “Supreme Admin” option. Afterwards, click the Create button. <https://imgur.com/gwhIuJT.png">
</p>
<p>
  
- Agents
  
<p>
In the Account tab, add a New Agent - Name, “John Doe,” Email Address, “john.doe@osticket.com,” Username, “john.doe” Click the set password button, selecting the password and password settings of your choice. Click the set. Then, click the Access tab to select the agent’s Department, Role, and Extended Access. Afterwards, click the Create button. <img src="https://imgur.com/Q4bFPaq.png">
</p>
<p>
  
- Configure Users (customers)
  
<p>
Create a new user named, “Karen” by switching to the Agent Panel, select the Users tab, then click the Add User button. <img src="https://imgur.com/f25OtMv.png">
</p>
<p>
  
<p>
Create Karen’s Email Address, “Karen@osticket.com,” Full Name, “Karen Karen.” Click Add User. <img src="https://imgur.com/CCcdwDf.png">
</p>
<p>
  
<p>
Create a new user named, “Ken,” in the Agent Panel, select the Users tab, then click the Add User button. <img src="https://imgur.com/tstVOiS.png">
</p>
<p>
  
<p>
Create Ken’s Email Address, “Ken@osticket.com,” Full Name, “Ken Ken.” Click Add User. <img src="https://imgur.com/lbLWR1M.png">
</p>
<p>
  
- Configure SLA
  
<p>
Switch back to the Admin Panel, click the Manage tab, select the SLA option, then click on the Add New SLA Plan button. <img src="https://imgur.com/lxNq2Rt.png">
</p>
<p>
  
- SEV-A
  
<p>
Name the SLA, “SEV-A,” set the Schedule as, “24/7,” Grace Period, “1 (in hours),” then click the Add Plan button. <img src="https://imgur.com/SmCfXWs.png">
</p>
<p>
  
- SEV-B
  
<p>
In the Admin Panel, click the Manage tab, select the SLA option, then click on the Add New SLA Plan button. <img src="https://imgur.com/ETgbU6l.png">
</p>
<p>
  
<p>
Name the SLA, “SEV-B,” set the Schedule as, “24/7,” Grace Period, “4 (in hours),” then click the Add Plan button. <img src="https://imgur.com/BFdGJpm.png">
</p>
<p>
  
- SEV-C
  
<p>
In the Admin Panel, click the Manage tab, select the SLA option, then click on the Add New SLA Plan button. <img src="https://imgur.com/wHniEWB.png">
</p>
<p>
  
<p>
Name the SLA, “SEV-C,” set the Schedule as, “Monday - Friday, 8am - 5pm with U.S. Holidays,” Grace Period, “8 (in hours),” then click the Add Plan button. <img src="https://imgur.com/Yyqm7hn.png">
</p>
<p>

- Configure Help Topics

<p>
In the Admin Panel, click on the Manage tab, select the Help Topics option, then click the Add New Help Topic button. <img src="https://imgur.com/FBF4S98.png">
</p>
<p>
  
- Business Critical Outage
  
<p>
Within the Help Topic Information tab, add “Business Critical Outage” as a Topic, then click the Add Topic button. <img src="https://imgur.com/e5UquAT.png">
</p>
<p>

- Add New Help Topic
  
<p>
Select the Help Topics option, then click the Add New Help Topic button. <img src="https://imgur.com/pjlYZuo.png">
</p>
<p>
  
- Personal Computer Issues
  
<p>
Within the Help Topic Information tab, add “Personal Computer Issues” as a Topic, then click the Add Topic button. <img src="https://imgur.com/5cRel3V.png">
</p>
<p>

- Add New Help Topic
  
<p>
Select the Help Topics option, then click the Add New Help Topic button. <img src="https://imgur.com/pDq4Vw3.png">
</p>
<p>

- Equipment Request
<p>
Within the Help Topic Information tab, add “Equipment Request” as a Topic, then click the Add Topic button. <img src="https://imgur.com/u0wL58g.png">
</p>
<p>
  
- Add New Help Topic
  
<p>
Select the Help Topics option, then click the Add New Help Topic button. <img src="https://imgur.com/eNOWgXy.png">
</p>
<p>
  
- Password Reset
  
<p>
Within the Help Topic Information tab, add “Password Reset” as a Topic, then click the Add Topic button. <img src="https://imgur.com/5XgLSDq.png">
</p>
<p>
