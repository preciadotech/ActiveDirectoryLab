<h1>Active Directory Home Lab</h1>



<h2>Description</h2>
In this lab, I successfully set up a Windows Server 2019 domain controller in Azure, created a domain, added users, configured network settings, and joined a Windows 10 VM to the domain.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Microsoft Azure</b>
- <b>Active Directory</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Server 2019</b> 

<p align="center">
<h2>Step 1: Create Server 2019 and Windows VMs on Azure: </h2>
One VM is running Windows Server 2019 to serve as the Domain Controller. <br/>
The second VM is a Windows 10 VM, which will act as a domain member client. <br/>
I ensured both VMs were placed in the same Virtual Network (VNet) to ensure they could communicate with each other over the internal network. <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Step 2: Install Active Directory Domain Services (AD DS) on the Server 2019 VM:  </h2>
After creating the Server 2019 VM, I used Remote Desktop Protocol (RDP) to connect to it and started configuring it. <br/>
I opened Server Manager, went to Add Roles and Features, and selected Active Directory Domain Services (AD DS) for installation. <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 3: Promote Server 2019 to Domain Controller: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 4: Create Users in Active Directory:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 5: Change Network Adapter Settings on Windows 10 VM:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 6: Join the Windows 10 VM to the Domain:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 7: Verify Domain Membership:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
