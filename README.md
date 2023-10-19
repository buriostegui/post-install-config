<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Post-Install Configuration Objectives</h2>

- Creating roles
- Setting up departments and teams
- Ticket permissions
- Setting SLA plans


<h2>Configuration Steps</h2>

Creating a New Role:
- Access the Admin panel in osTicket.
- Navigate to Agents -> Roles.
- Create a new role, such as "Supreme Admin," granting them all permissions.
  
![image](https://github.com/buriostegui/post-install-config/assets/148411510/822e39bd-a1fa-43b3-bd08-0d0cd1f226a8)

Setting Up Departments:
- Click on "Departments" in the agents tab.
- Create a new department, e.g., "System Administrators," where Supreme Admins will be assigned.
- Configure department-specific settings, like SLAs and managers.

![image](https://github.com/buriostegui/post-install-config/assets/148411510/137dbb88-dd36-4def-af40-c3129be49c79)

Creating Teams:
- Visit Agents -> Teams.
- Establish teams that can consist of agents from different departments.
- For example, create a Level II Support Team.

![image](https://github.com/buriostegui/post-install-config/assets/148411510/e3763bf8-8853-47c7-b170-bc87d65f8cf4)

Configuring Ticket Creation Permissions:
- Access Admin Panel -> Settings -> User Settings.
- Set up a new setting that allows anyone to create tickets.

![image](https://github.com/buriostegui/post-install-config/assets/148411510/462d40f0-16d0-49b8-8e91-94478d84f034)

Adding Agents:
- Agents are employees responsible for resolving tickets.
- Assign primary departments and roles to agents.
-  Agents can have access to multiple departments and different roles based on their department.

![image](https://github.com/buriostegui/post-install-config/assets/148411510/0d48107b-ce44-4a9b-af25-b32774fea020)

Creating Users:
- Users are customers who create tickets.
- Create user profiles based on their email addresses.
- Access the Agent Panel -> Users -> User Directory to add new users.

![image](https://github.com/buriostegui/post-install-config/assets/148411510/790a939b-eab6-45e7-bbd5-7c059284960f)

Setting SLA Plans:
- SLA Plans define the expected resolution time for specific ticket categories.
- Go to Admin Panel -> Manage -> SLA Plans.
- Create SLA plans with schedules and grace periods, like SEV-A with a 24/7 schedule and a one-hour grace period.

![image](https://github.com/buriostegui/post-install-config/assets/148411510/ca8d75f2-338c-4980-b12f-a68caeb895e7)

Managing Help Topics:
- Help topics assist users in categorizing their tickets.
- Create help topics to categorize issues, such as "Business Critical Outage."

![image](https://github.com/buriostegui/post-install-config/assets/148411510/ae32de3c-882d-4311-b6f6-88898906c0bc)

These steps guide the post-installation setup and system administration for osTicket, allowing you to configure roles, departments, teams, permissions, agents, users, SLA plans, and help topics for effective helpdesk management.
