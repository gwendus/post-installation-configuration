<p align="center">

<img src="https://d7umqicpi7263.cloudfront.net/img/product/29bda7f2-2c99-40b8-a338-1448bc043ff1.com/214c16a85047ad91f1dfcddfb916db68" height="40%" width="40%" alt="osTicket logo"/>
 
 <h1># osTicket Post-Installation Configuration</h1>
 This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.
<br />

<h2>Environments and Utilities</h2>

- <b>Microsoft Azure</b> 
- <b>Remote Desktop Protocol</b>
- <b>Internet Information Services(ISS)</b>

<h2>Operating Systems</h2>

- <b>Windows 10</b> (22H2)

<h2>Post-installation Objectives</h2>

- <b>Configuring roles, departments, and teams</b>
- <b>Creating an environment to simulate interactions between agents (IT professionals) and users (clients)</b>
- <b>Applying Service Level Agreements(SLAs) to scenarios</b>
- <b>Adding Help Topics for tickets</b>
- <b>Explore how identity access management plays a vital role in configuring a ticketing system</b>

<h2>Let's get into it!</h2>

<b>We begin by connecting to our virtual machine in Azure through remote desktop protocol. From there, we launch the utility osTicket and sign into our agent panel. In the top left, we can see the admin panel, which allows us to configure the application.</b>
<p align="center">

Launch the utility. Login to osTicket. Observe the "admin panel" at the top of the page. <br/>
<br />
<img src="https://i.imgur.com/SV40Ehw.png" height="70%" width="70%" alt="Login Screen Agent"/>
<br />
<br />

Click "admin panel" to access configuration controls for the platform. Now we see "agent panel" in the top right corner as we access admin or backend controls. While the initial screen shows many technical settings, for the purpose of this lab, we will be focusing on configuring the agents' user interface. <br/>
<br />
<img src="https://i.imgur.com/y66Nifq.png" height="70%" width="70%" alt="Admin Panel"/>
<br />
<br />

We will begin by adding our departments for our company. In this simulation, we will be managing the IT needs for an online bank.  <br/>
<br />
<img src="https://i.imgur.com/hlcEM3c.png" height="70%" width="70%" alt="Departments"/>
<br />
<br />

Under every category, we can manage who can access tickets and information pertaining to each department.  <br/>
<br />
<img src="https://i.imgur.com/onIcpBf.png" height="70%" width="70%" alt="Departments config"/>
<br />
<br />

For teams, we will have level I and II support.  <br/>
<br />
<img src="https://i.imgur.com/TvjmTqM.png" height="70%" width="70%" alt="teams"/>
<br />
<br />
Teams allow us to more appropriately route tickets according to severity and agent roles. <br/>
<br />
<img src="https://i.imgur.com/3dWzU28.png" height="70%" width="70%" alt="Teams configuration"/>
<br />
<br />
In this lab, we will have two support agents, John and Jane. We also have an entry for myself as a sys admin.  <br/>
<br />
<img src="https://i.imgur.com/kkAx8eI.png" height="70%" width="70%" alt="Adding agents"/>

When we manage agents within the osTicket system, we can also give consideration to their primary department and whether or not they can have extended access with different permissions. In the example pictured, as a system administrator, I will have extended access to all departments. Access can range from "view only" to "all access." Permissions consist of the ability to create, delete, and edit users (customers) to name a few.  <br/>
<br />
<img src="https://i.imgur.com/xiLkSgu.png" height="70%" width="70%" alt="Configuring agents"/>

Lastly, we configure roles for our agents. Note that each role has different access and permissions.  <br/>
<br />
<img src="https://i.imgur.com/LNactQV.png" height="70%" width="70%" alt="Added Roles"/>
<br />
<br />
We can configure the settings under each role for identity access management. This is very important in reference to giving team members the right tools to do their job. <br/>
<br />
<img src="https://i.imgur.com/JOEiUEX.png" height="70%" width="70%" alt="configuring roles"/>
<br />
<br />
Add users <br/>
<br />
<img src="https://i.imgur.com/XmYjXow.png" height="70%" width="70%" alt="Adding users"/>
<br />
<br />

Configure users <br/>
<br />
<img src="https://i.imgur.com/9pVNEVY.png" height="70%" width="70%" alt="Config users"/>
<br />
<br />
<h2>Applying Service Level Agreements(SLAs) to scenarios</h2>
Blurb on importance of SLAs. Expanding on categories. Go back into VM and capture. <br/>
<br />
<img src="https://i.imgur.com/4XbMjTQ.png" height="70%" width="70%" alt="SLAs"/>
<br />
<br />

<h2>Adding Help Topics for tickets</h2>
Blurb on importance of Help Topics. Expanding on categories. Go back into VM and capture. <br/>
<br />
<img src="https://i.imgur.com/wgTTNed.png" height="70%" width="70%" alt="Help Topics"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
