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

<h2>Program walk-through:</h2>

<p align="center">
Create Server 2019 and Windows VM on Azure: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create domain controller to promote to Server 2019: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Users On Server Manager:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change adapter settings on Windows VM to communicate with Server 2019 via TCP/IPv4:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Make Windows 10 vm a member of the domain:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
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
