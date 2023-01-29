<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Setup</h1>
</p>
This tutorial demonstrates the post-install setup of the osTicket system.<br/>

<p>

</p>
</p>
<p>
Okay, wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post-installation setup.
First, we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create an "Administrator" role. 
Click on "Add new role" and then enter the name of the new role. You can also modify any specific role permissions. In this case, since we are creating an Administrator they will be given all permissions. Remember that roles are used to determine an agent's permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should look something like this. As you can see we have successfully created the "Administrator" role.
</p>
<img src="https://i.imgur.com/ZIWRhLl.png" height="80%" width="80%" alt="Admin role creation"/>
</p>
<br />
<p>
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case, we will be creating the "System Administrators" department. Other specific settings such as SLAs, managers, and other email settings can be set up in the departments tab. 
</p>
<br />
<p>
<img src="https://i.imgur.com/Wue3eUs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have a team that has top technicians from specific departments. For example, you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example, we will create a Level II Support Team. 
</p>
<br />
<p>
<img src="https://i.imgur.com/wwsOVBf.png" height="80%" width="80%" alt="Teams"/>
</p>
<p>
 Now that we have set up a new team we will create a new setting that will allow anyone to create tickets without being required to register nor login. Admin Panel->Settings->User Settings. See "Registration Required" checkbox.

</p>
<br />
<img src="https://i.imgur.com/Y44gZM1.png" height="80%" width="80%" alt="User registration option"/>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams can be assigned in the Agents tab. 
</p>
<br />
<img src="https://i.imgur.com/UDIK45f.png" height="80%" width="80%" alt="Agents"/>
</p>
<p>
We are now in the Users tab of the Agents panel. The User Directory will reflect the list of users who create tickets for their issues. To create a user you either follow this path Agent Panel->Users->User Directory->Add new or simply submit a ticket from the ticket submission page. 
</p>
<br />
<img src="https://i.imgur.com/jLO5j57.png" height="80%" width="80%" alt="Users"/>
</p>
<p>
Service Level Agreements will generally vary for each company but the purpose of the SLA Plan in this example is to provide a length of time in which the help desk Administrator expects tickets to be closed. SLA Plans can be created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule, there is a grace period.
</p>
<br />
<img src="https://i.imgur.com/KQZSbqj.png" height="80%" width="80%" alt="SLAs"/>
</p>
<p>
Help Topics will help streamline an end-user’s help desk experience to ensure proper assignment and prompt response to the ticket. It will determine what Department the ticket is routed to which will determine which Agents have access to the ticket.
</p>
<br />
<img src="https://i.imgur.com/kbyZ89D.png" height="80%" width="80%" alt="Help topics"/>
</p>
<p>
  

