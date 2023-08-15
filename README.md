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
<h4> 1. Configure Roles</h4>
<h4> 2. Configure Departments</h4>
<h4> 3. Configure Teams </h4>
<h4> 4. Allow anyone to create tickets </h4>
<h4> 5. Configure Agents (workers) </h4>
<h4> 6. Configure Users (customers) </h4>
<h4> 7. Configure SLA </h4>
<h4> 8. Configure Help Topics </h4>
  
<h2>Configuration Steps</h2>


<h4> 1. Configure Roles </h4>

 Admin Panel -> Agents -> Roles
 

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/4288abda-f907-47ef-8ee2-f32407a6a668) 

Agents -> Roles

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/187cf4d9-9b61-448d-8e2c-62417cf0fdb3)

Adding and configuring  a new role "Supreme Admin" 

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/d63394cc-b6b1-4e41-8b2d-4bc8f0c685e9) ![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/d367c96e-b2a2-4fba-96da-a98ece11e88c)


<h4> 2. Configure Department </h4>

Admin Panel -> Agents -> Departments  

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/0c7ce372-03e4-4c17-a44f-5de64117bb7f)

Adding and Configuring a new Department.



![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/f9e4b2ca-b019-4fab-80f5-b7e3b442a761) 

Kept the default settings.

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/54b26762-3be6-42e4-a2c0-c12bc14caf81)


<h4> 3. Configuring Teams </h4>

Admin Panel -> Agents -> Teams

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/fd1d37cd-4e71-41ca-8b33-1a868451ccd1)

Create a New Team and add members respectively.

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/1085dbd4-14f4-4773-aed2-08ba44789640)

<h4> 4. Allow anyone to create tickets </h4>

Admin Panel -> Settings -> Users -> Authentication Settings (Registration required leave unchecked)

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/b8bd6fd4-9fc1-4235-a565-0171f7259c96)


<h4> 5. Configure Agents (Workers) </h4>

Admin Panel -> Agents -> Add New Agent

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/90b71315-f318-40f5-b1fc-88356780be12)

Configure and manage their Account, Access, Permissions and Teams here.

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/fb2a8724-60f9-46ce-90bb-078934ba4a2f)

Access Tab, let's you select what Department and Roles can be assigned

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/01492811-5e96-4cbf-8b9b-8cc92346fa9a)

Permission Tab

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/f3fb845f-88e9-4d77-804d-94b2ca56a4f0)

Teams Tab

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/c521e701-a133-4471-970b-6fe03a6c547a)


<h4> 6. Configure Users </h4>

Agent Panel -> Users -> Add new

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/a677a595-083a-4d76-b4a9-451b6e23291b)

Users -> Add new

![image](https://github.com/marvrodriguez/osticket-post-install-config/assets/141983161/9b41ee48-8a0f-499a-b768-16f3d06cf299)






