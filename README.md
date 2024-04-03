<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This outline contains a tutorial of the post-install configuration for the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Role Configuration
- Department Configuration
- Team Configuration
- Ticket Creation Access
- Agent Configuration
- User Configuration
- SLA Configuration
- Help Topic Configuration

<h2>Role Configuration</h2>

<p>
1) Navigate to the Admin Panel

![Screenshot 2024-03-31 233546](https://github.com/kbd060/post-install-config/assets/150099961/8fea7329-1ab9-4764-90e7-bbfb750a836c)
![Screenshot 2024-03-31 234754](https://github.com/kbd060/post-install-config/assets/150099961/e8a277d9-c62a-4406-b682-ff78b3f75a46)


<p>
2) Go to Agents and then Roles.

![Screenshot 2024-03-31 234830](https://github.com/kbd060/post-install-config/assets/150099961/07254358-37bf-48fd-a551-db05cdf68cf8)
![Screenshot 2024-03-31 234841](https://github.com/kbd060/post-install-config/assets/150099961/664fe32a-3972-4728-9ec6-a676e3835049)


<p>
3) Create the "Supreme Admin" role, and enable all accessibilities for "Tickets," "Tasks," and "Knowledgebase."

![Screenshot 2024-03-31 235018](https://github.com/kbd060/post-install-config/assets/150099961/9d12dc38-b00d-4a45-9d03-1475bf942c7b)
![Screenshot 2024-03-31 235108](https://github.com/kbd060/post-install-config/assets/150099961/101026fd-2ef8-4a0a-9bba-3c679fcca0fb)
![Screenshot 2024-03-31 235214](https://github.com/kbd060/post-install-config/assets/150099961/5af39663-8fca-4a0b-b98a-28ce6467ad9c)
![Screenshot 2024-03-31 235230](https://github.com/kbd060/post-install-config/assets/150099961/a65c52c4-4ae0-4344-8c03-af4eac96e764)

<h2>Department Configuration</h2>

<p>
1) In the Admin Panel, select Agents and then Departments.

![Screenshot 2024-04-01 000409](https://github.com/kbd060/post-install-config/assets/150099961/4d181df6-9329-4edc-ab69-66a0b62be18f)


<p>
2) Create a department named "System Administrators", using the default settings.

![Screenshot 2024-04-01 000636](https://github.com/kbd060/post-install-config/assets/150099961/2f574dd3-6567-4b0a-b3ea-5cf80f8ba24a)
![Screenshot 2024-04-01 000704](https://github.com/kbd060/post-install-config/assets/150099961/aab3c648-9335-408b-8837-65bb5f876464)


<h2>Team Configuration</h2>

<p>
1) Access the Admin Panel, then go to Agents and select Teams.

![Screenshot 2024-04-01 001736](https://github.com/kbd060/post-install-config/assets/150099961/c3310e9f-6b57-4f44-be42-f2cab7f6aec0)


<p>
2) Create teams such as "Level I Support" and "Level II Support," and add members as necessary, like "hans leger" to "Level II Support."

![Screenshot 2024-04-01 001736](https://github.com/kbd060/post-install-config/assets/150099961/d5f44b40-f08e-4b3b-b5d1-b56c322de218)
![Screenshot 2024-04-01 001920](https://github.com/kbd060/post-install-config/assets/150099961/c9bd64ad-650e-4c86-b129-6328781faa06)
![Screenshot 2024-04-01 001946](https://github.com/kbd060/post-install-config/assets/150099961/47b337c2-7fb6-47e5-91e1-4fd00165964a)
![Screenshot 2024-04-01 002040](https://github.com/kbd060/post-install-config/assets/150099961/82f18be9-1044-4041-8452-b142bc33c801)


<h2>Ticket Creation Access</h2>

<p>
1) Within the Admin Panel, navigate to Settings and then User Settings.

![Screenshot 2024-04-01 002910](https://github.com/kbd060/post-install-config/assets/150099961/ec583a20-3b84-4cdc-9730-b59263413c57)

<p>
2) Ensure "Registration Required" is disabled to allow anyone to create tickets.


<h2>Agent Configuration</h2>


