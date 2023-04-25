<p align="center">
<img src="https://www.synaxiom.com/wp-content/uploads/2016/06/osticket.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial/lab we are going to be working on the configuration of osTicket.</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Objectives</h2>

- Configure Roles
- Configure Departments & Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLAs
- Configure Help Topics

<h2>Configuration Visual Walkthrough</h2>


<p>
<img src="https://i.imgur.com/oht2fq0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

To configure Roles, Departments, and Teams, you will need to:

- First make sure when you log in to osTicket, you are in the Admin Panel.
- To configure Roles, you will click on the Agents tab > Roles > Add New Role > Name your new role > Click on the Permissions tab and then choose your applicable permissions within the Tickets, Tasks, and Knowledgebase options > Save Changes.
- To configure Departments, you will click on the Agents tab > Departments > Add New Department > Name your new department > Follow the options and update the Department Information as needed > Click Create Dept.
- To configure Teams, you will click on the Agents tab > Teams > Add New Team > Name your new team > Click Members tab and decide who you want to be part of the team > Create Team.

</p>
<br />

<p>
<img src="https://i.imgur.com/fJdvxtg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I will show you how to create an agent or worker account. 

- Click on the Agents tab > Add new agent > Fill out agent information in Account tab. Access, Permissions, and Teams tabs.
- Click on Access tab and choose the department and role that the new agent will be filling.
- Click on Permissions tab and give appropriate permissions to the new agent.
- Click on Teams and if applicable, select the team that the new agent will be a part of > Click Create.

To configure a user or customer to the platform, follow these simple steps:

- Make sure you are now in the Agent Panel NOT the Admin Panel.
- Click on Users > Click on Add User > Enter the name and email address for the new user account.
That's it!

</p>
<br />

<p>
<img src="https://i.imgur.com/XY9KrS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure SLAs, follow the following steps:

- Make sure you are in the Admin Panel > Click on the Manage tab > SLA > Add New SLA Plan > Name your new SLA, Grace Period, and Schedule.
- Your employer will have a specific set of guidlines and SLA's to follow, so make sure you are using those settings.

To configure new Help Topics asside from the ones currently implemented into osTicket you will need to follow the following steps:
- Make sure you are in the Admin Panel > Click on the Manage tab > Help Topics > Add New Help Topic > Create a relavant topic that can be used such as "Personal Computer Issues" > Add Topic. 

We have finished the post installastion tutorial.
</p>
<br />
