<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This list outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Domain Controller VM and Client VM
- Use same resource group for both VMs
- Ensure both VMs are in same Vnet
- Ensure connectivity between Client VM and Domain Controller VM
- Install Active Directory
- Create an Admin and Normal User account in AD
- Join Client VM to your domain
- Setup Remote Desktop for non-admin users on Client VM
- Create additional users and attempt to login to Client VM with one of the users

