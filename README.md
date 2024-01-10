<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Domain Controller VM (Windows Server 2022) Named "DC1"     
- Create Client VM Named Client 1 on Windows 10 
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/LJ7sppr.png"/>
</p>
<p> Create a Windows server called "DC1" for domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/fxAlanS.png"/>
</p>
<p>
Create two virtual CPU's if using one it will be pretty slow.
</p>
<br />

<p>
<img src=https://i.imgur.com/frhWExA.png/>
</p>
<p>
The steps for creating the Client will be similar to creating our domain controller make sure the resource group is the same as the one you created with ur DM for the example it is "AD"
</p>
<br />
<P></P> img src="https://i.imgur.com/IZp9VJs.png"</P>
<p>
Go under the networking tab and make sure DC1-Vnet is selected under virtual networking.
</p>
