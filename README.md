# osTicket Post Installation Configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

This tutorial outlines the osTicket: post-installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket (Help Desk Ticketing System)

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
Name the New Role, “Supreme Admin,” then click the the Permissions tab. <img src="https://imgur.com/8gDvdux.png">
</p>
<p>

- Tickets
<p>

<p>
In the Tickets section select all of the options: “Assign…” “Close…” “Create…” “Delete…” “Edit…” “Edit Thread…” “Link…” “Mark as Answered…” “Merge…” “Post Reply…” “Refer…” “Release…” “Transfer…” <img src="https://imgur.com/9WGX254.png">
</p>
<p>
  
- Tasks
<p>

<p>
Click on the Tasks section. Then, select all of the options:  “Assign…” “Close…” “Create…” “Delete…” “Edit…” “Post Reply…” “Transfer…” <img src="https://imgur.com/URo20ZS.png">
</p>
<p>

- Knowledgebase
<p>

<p>
Click on the Knowledgebase section. Then, select the “Premade…” option, followed by the Save Changes button. <img src="https://imgur.com/fBXanap.png">
</p>
<p>
  
- Configure Departments

<p>
In the Admin Panel, within the Agents tab, select Departments, then click the “Add New Department” button. <img src="https://imgur.com/aeO9g3A.png">
</p>
<p>

- System Administrators 

<p> 
Within the Settings tab, name the New Department, “System Administrators." Then, click the Create Department button. <img src="https://imgur.com/PS8t6UQ.png">
</p>
<p>
  
- Configure Teams
  
<p>
In the Admin Panel, within the Agents tab, select Teams, then click on the Add New Department button. <img src="https://imgur.com/jQjYPjM.png">
</p>
<p>

- Level I Support
  
<p>
Notice how Level I Support is a default team within osTicket. <img src="https://imgur.com/2n0dQ2U.png">
</p>
<p>
  
- Level II Support
  
<p>
Click the Add New Team button. Then, name the team “Level II Support.” <img src="https://imgur.com/nU04zbv.png">
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
In the Account tab, add a New Agent.
</p>
<p>
<p>
Name: “Jane Doe,” Email Address: “jane.doe@osticket.com,” Username: “jane.doe”
</p>
<p>
<p>
Click the Set Password button. 
<p>
<img src="https://imgur.com/bQtgYEX.png">
</p>
<p>
  
<p>
Select the password and password settings of your choice. Click the Set button. <img src="https://imgur.com/XCjU8UD.png">
</p>
<p>
  
  - Access
  
<p>
Click the Access tab to select the Agent’s Department, ensuring that the Primary Department, “System Administrators,” and Role, “System Admin” have been selected. <img src=https://imgur.com/gwhIuJT.png">
</p>
<p>
  
 - Support
  
<p>
In the Extended Access section, click the “Select Department” drop down menu, then select “Support.” Afterwards, click the Create button. <img src="https://imgur.com/nLKMn96.png">
</p>
<p>
  
- Agents
  
<p>
In the Account tab, add a New Agent.
</p>
<p>
<p>
Name: “John Doe,” Email Address: “John.Doe@osticket.com,” Username: “john.doe”
<p>
Click the Set Password button. <img src="https://imgur.com/IkcFs05.png">
</p>
<p>
<p>
Select the password and password settings of your choice. Click the Set button. <img src="https://imgur.com/cPRNo1D.png">
</p>
<p>
  
- Access
<p>
Then, click the Access tab. Assign “System Administrators,” “Supreme Admin,” and “Support” as John Doe’s Department, Role, and Extended Access, respectively. Afterwards, click the Create button. <img src="https://imgur.com/dkb74nS.png">
</p>
<p>

- Configure Users (Customers)
  
<p>
Create a new user named, “Karen” by switching to the Agent Panel. Select the Users tab. Then, click the Add User button. <img src="https://imgur.com/f25OtMv.png">
</p>
<p>
  
<p>
Create Karen’s Email Address: “Karen@osticket.com,” Full Name: “Karen Karen” 
</p>
<p>
<p>
Click the Add User button. <img src="https://imgur.com/CCcdwDf.png">
</p>
<p>
  
<p>
Create a new user named, “Ken,” in the Agent Panel. Select the Users tab. Then, click the Add User button. <img src="https://imgur.com/tstVOiS.png">
</p>
<p>
  
<p>
Create Ken’s Email Address: “Ken@osticket.com,” Full Name: “Ken Ken” 
</p>
<p>
<p>
Click the Add User button. <img src="https://imgur.com/lbLWR1M.png">
</p>
<p>
  
- Configure SLA
  
<p>
Switch back to the Admin Panel. Click the Manage tab. Select the SLA option. Then, click on the Add New SLA Plan button. <img src="https://imgur.com/lxNq2Rt.png">
</p>
<p>
  
- SEV-A
  
<p>
Name the SLA “SEV-A,” with a Grace Period of "1 (in hours)," and set the Schedule as, “24/7.” Then, click the Add Plan button. <img src="https://imgur.com/SmCfXWs.png">
</p>
<p>
  
- SEV-B
  
<p>
In the Admin Panel, click the Manage tab. Select the SLA option. Then, click on the Add New SLA Plan button. <img src="https://imgur.com/ETgbU6l.png">
</p>
<p>
  
<p>
Name the SLA “SEV-B,” with a Grace Period of “4 (in hours), and set the Schedule as, “24/7.” Then, click the Add Plan button. <img src="https://imgur.com/BFdGJpm.png">
</p>
<p>
  
- SEV-C
  
<p>
In the Admin Panel, click the Manage tab. Select the SLA option. Then, click on the Add New SLA Plan button. <img src="https://imgur.com/wHniEWB.png">
</p>
<p>
  
<p>
Name the SLA “SEV-C,” with a Grace Period of “8 (in hours)," and set the Schedule as, “Monday - Friday, 8am - 5pm with U.S. Holidays.”  Then, click the Add Plan button. <img src="https://imgur.com/Yyqm7hn.png">
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
Add “Equipment Request” as a Topic, then, click the Add Topic button. <img src="https://imgur.com/u0wL58g.png">
</p>
<p>
  
- Add New Help Topic
  
<p>
Select the Help Topics option, then click the Add New Help Topic button. <img src="https://imgur.com/eNOWgXy.png">
</p>
<p>
  
- Password Reset
  
<p>
Add “Password Reset” as a Topic, then click the Add Topic button. <img src="https://imgur.com/5XgLSDq.png">
</p>
<p>
