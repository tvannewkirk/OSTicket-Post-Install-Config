<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Post-Install Configuration</h1>
This tutorial demonstrates the post-install configuration of the open-source help desk ticketing system osTicket.


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>
Inside of the osTicket admin panel, click on agents at the top right. Click on roles. Click on add new role. Name the role Supreme Admin.
</br>
<p>
<img width="640" height="520" alt="Screenshot 2026-01-12 005822" src="https://github.com/user-attachments/assets/65a162fe-365b-48fb-a338-7e8a6e6d58ce" />
</p>
Click on permissions. Check the boxes for all permissions under tickets, tasks and knowledgebase. Click on add role.
</br>
<p>
<img width="610" height="515" alt="Screenshot 2026-01-12 010120" src="https://github.com/user-attachments/assets/f3add00a-638e-4fec-8324-886f9512f9f2" />
</p>
Click on the departments tab within the agents tab. Click on add new department. Choose top-level department. Make the name SysAdmins. Click create dept.
</br>
<p>
<img width="735" height="830" alt="Screenshot 2026-01-12 010641" src="https://github.com/user-attachments/assets/7612bf94-56e2-4264-af89-6a31140b1a1d" />
</p>
Click on the teams tab within the agents tab. Click add new team. Make the name Online Banking. Click create team.
</br>
<p>
<img width="775" height="521" alt="Screenshot 2026-01-12 010929" src="https://github.com/user-attachments/assets/0bbd4c5c-7775-44f2-8f5a-fa838682742d" />
</p>
Click on the settings tab. Click on users. Verify that the registration required box is unchecked.
</br>
<p>
<img width="780" height="497" alt="Screenshot 2026-01-12 011316" src="https://github.com/user-attachments/assets/810f1958-6340-4b7b-9a90-4b55043e662b" />
</p>
Click on the agents tab. Click add new agent. Make the name Jane Doe. Assign an email address. Make the username jane. Click on the access tab. Assign the SysAdmins department and Supreme Admin role. Click on teams. Assign the account to the Online Banking team. Click on create.
</br>
<p>
<img width="768" height="298" alt="Screenshot 2026-01-12 011916" src="https://github.com/user-attachments/assets/14f32160-be7c-44f4-884f-afdcc58fdc82" />
</p>
Click on agents. Click add new agent. Make the name John Doe. Assign an email address. Make the username john. Click on the access tab. Assign the Support department and view only role. Click create.
</br>
<p>
<img width="797" height="487" alt="Screenshot 2026-01-12 012254" src="https://github.com/user-attachments/assets/12d9305d-65a9-4dfe-a9c4-fd041e126b62" />
</p>
Click on the agent panel at the top right. Click on the users tab. Click add user. Assign an email address. Make the name Karen. Click add user.
</br>
<p>
<img width="588" height="352" alt="Screenshot 2026-01-12 012715" src="https://github.com/user-attachments/assets/d083ff31-34e7-4aa5-81fd-11f67ad7c21c" />
</p>
Click on the admin panel at the top right. Click on the manage tab. Click on SLA. Make the name Sev-A. Make the grace period one hour. Make the schedule 24/7. Click add plan.
</br>
<p>
<img width="778" height="481" alt="Screenshot 2026-01-12 013350" src="https://github.com/user-attachments/assets/35ac473d-9782-4301-ae39-650692c14714" />
</p>
Click on add new SLA plan. Make the name Sev-B. Make the grace period four hours. Make the schedule 24/7. Click add plan.
</br>
<p>
<img width="738" height="477" alt="Screenshot 2026-01-12 013556" src="https://github.com/user-attachments/assets/79dfd4a5-d8aa-4ec6-b759-6aaa882b514a" />
</p>
Click on add new SLA plan. Make the name Sev-C. Make the grace period eight hours. Make the schedule business hours. Click add plan.
</br>
<p>
<img width="783" height="478" alt="Screenshot 2026-01-12 013759" src="https://github.com/user-attachments/assets/26d54e2f-8310-47b3-9ecc-adf7859e0246" />
</p>














