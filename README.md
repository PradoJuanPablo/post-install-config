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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents(workers)
- Configure Users(customers)
- Configure SLAs
- Configure Help Topics


<h2>Configuring Roles</h2>

<p>
<img width="720" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/113d156b-c4f7-40be-9ef1-e5e6349d3972">

<img width="721" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/0623b425-e792-4fb2-a510-87efbaa59f85">


</p>
<p>
First, we're going to create a Supreme Admin role and set its permissions to have complete control. 

To do that we go to 
1. Admin Panel
2. Agents
3. Roles
4. Create a role called "Supreme Admin"
</p>
<br />

<h2>Configuring Departments</h2>

<p>
<img width="650" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/8587ab8c-cd8f-4ff7-bde4-f92cf77d911e">


</p>
<p>
To configure departments we go to
  
1. Admin Panel
2. Agents
3. Departments
4. Create a department called "System Administrators"

<br />
<h2>Configuring Teams</h2>


<p>
<img width="719" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/165e5363-c18e-4355-814f-f40a44a168bb">

</p>
<p>
To configure teams we go to
  
1. Admin Panel
2. Agents
3. Teams
4. Create a team named "Level II Support"
</p>
<br />

<h2>Configuring Agents</h2>


<p>
<img width="719" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/1cfd0ceb-5d6a-4b66-8819-935ff9dfc383">


</p>
<p>
To configure agents we go to
  
1. Admin Panel
2. Agents
3. Add New Agent

Here, we can also set what kind of permissions they have and what department they belong to.
   
</p>
<br />

<h2>Configuring Users</h2>


<p>
<img width="719" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/0ae89240-e1e8-4c61-ab5f-673c17735bd1">


</p>
<p>
To configure users we go to
  
1. Agent Panel
2. Users
3. Add New Users

</p>
<br />

<h2>Configuring SLAs</h2>


<p>
<img width="719" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/b37bc4cc-600b-4c27-a298-3edb51e45e1f">

</p>
<p>
To configure SLAs we go to
  
1. Admin Panel
2. Manage
3. SLA
4. We're going to create three SLAs
   
- SEV-A (1 hour, 24/7)
- SEV-B (4 hours, 24/7)
- SEV-C (8 hours, business hours)



</p>
<br />

<h2>Configuring Help Topics</h2>


<p>
<img width="719" alt="image" src="https://github.com/PradoJuanPablo/post-install-config/assets/160810181/165e5363-c18e-4355-814f-f40a44a168bb">

</p>
<p>
To configure help topics we go to
  
1. Agent Panel
2. Agents
3. Teams
4. Create a team named "Level II Support"
</p>
<br />
