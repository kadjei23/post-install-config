<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.We are going to be configuring and using osTicket through the eyes of an admin user by defining roles, departments, teams and assiging SLA,s. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Getting Started </h2>

<img src="https://i.imgur.com/TCT6SxR.png" height="80%" width="80%" alt="Get Started"/>

To get started with this we first create a Role, Admin Panel -> Agents -> Roles. Then head to add new role and name it anything.

<img src="https://i.imgur.com/NclXEBK.png" height="80%" width="80%" alt="New Role"/>

After adding and naming the role we are then going to go to permissions and check all the boxes on tasks and let us be in control of everything.

<img src="https://i.imgur.com/ERTwoxb.png" height="80%" width="80%" alt="New Role ext"/>

<img src="https://i.imgur.com/AJPbH2e.png" height="80%" width="80%" alt="New Role task"/>

<img src="https://i.imgur.com/vptLFub.png" height="80%" width="80%" alt="Permissions"/>

Next we are going to configure departments. Admin Panel -> Agents -> Departments -> Add New Departments

<img src="https://i.imgur.com/e4W9Wls.png" height="80%" width="80%" alt="Add Dep"/>

Name the new created department System Administrator. We will be using default settings for now so go ahead and create.

<img src="https://i.imgur.com/IKydyXm.png" height="80%" width="80%" alt="Sys Ad"/>

Move on to create and configure Teams. Admin Panel -> Agents -> Teams -> Create two teams Level 1 and level 2 support or Team A team B.

<img src="https://i.imgur.com/QwRBALq.png" height="80%" width="80%" alt="Teams"/>

You can add yourself as the admin to any team.

<img src="https://i.imgur.com/V46xyHC.png" height="80%" width="80%" alt="Teams 2"/>

Next we are going to enable and allow anyone to create tickets by going to Admin Panel -> Settings -> User -> User Settings.

<img src="https://i.imgur.com/Tgup1tD.png" height="80%" width="80%" alt="User"/>

On this display check the "Registration Required: Require registration and login to create tickets" this allows any person to create a ticket.

After that we are going to create and configure our agents. Admin Panel -> Agents -> Add New for the names of our agents we are going to use Sterling and John.

<img src="https://i.imgur.com/mAvBlmG.png" height="80%" width="80%" alt="Agents"/>

By pressing create agents we can come up with the agents first and last name and their email then makeup a username for them. After that we then set a password for the to use.

<img src="https://i.imgur.com/WrCO62k.png" height="80%" width="80%" alt="Sterling"/>

After we set the password we can go to access tab and assign what level they are at, what team they can be assigned to and what department they belong to. These all determine the level of access they have in osTicket.

<img src="https://i.imgur.com/9EaZ6TG.png" height="80%" width="80%" alt="Access"/>

After creating these agents we can now create and configure the users/customers than can use and create tickets. Agent Panel -> Users -> Add New

<img src="https://i.imgur.com/dotgVHR.png" height="80%" width="80%" alt="User"/>

Fill out the necessary information to create the user like name and email and hit create after completion.

<img src="https://i.imgur.com/yz5UptO.png" height="80%" width="80%" alt="User2"/>

Next we are going to create SLA's. Admin Panel -> Manage -> SLA. We will be creating 3 of them which are sev-a, sev-B, and Sev-C. Each will have different grace periods of when the tickets are supposed to be done.

<img src="https://i.imgur.com/wX9SOUS.png" height="80%" width="80%" alt="SLA"/>

<img src="https://i.imgur.com/kA9S8QP.png" height="80%" width="80%" alt="SEV-C"/>

Lastly we will end with creating help topics. Admin Panel -> Manage -> Help Topics. When the users(customers) are creating a ticket the help topics help identify what kind of problem it is which then allows our agents to see the business impact and level of attention is needed with each topic. Help topic example: Password reset, Broken laptop Etc.


<img src="https://i.imgur.com/gXIoyfL.png" height="80%" width="80%" alt="Help"/>

You can see at the bottom we are able to Create the topics needed for customers to place whatever issue they are having in categories.

<img src="https://i.imgur.com/qfRpUIO.png" height="80%" width="80%" alt="Topics"/>

<img src="https://i.imgur.com/MkJzA9Q.png" height="80%" width="80%" alt="Topic"/>



</p>
<br />
