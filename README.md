<h1>Active Directory Home lab</h1>



<h2>Description</h2>
This project outlines the installation and configuration of an IT environment for Pasilan Koulutus Oy’s for student network. Due to the COVID-19 restrictions, the setup is first deployed in a QEMU/KVM Environment before any physical server Installation.<br />


<h2>Languages and Utilities Used</h2>

- <b>QEMU/KVM</b>
- <b>PowerShell</b>




<h2>Environments Used </h2>

- <b>Windows Server</b> (21H2)
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Setting up the Windows Server: <br/>
Windows Server was deployed using the QEMU/KVM
<img src="https://i.imgur.com/YAZZWSI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing AD and enabling AD edu.local:  <br/>
<img src="https://i.imgur.com/nomt1yB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Promoting Server to AD controller: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating OU with Powershell:  <br/>
<img src="https://i.imgur.com/NIUEgcA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating an AD User with Powershell script:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Printer Installation:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding a BackupDrive:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Group Policy Object(GPO):  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setting up Workstation VM:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Joining Workstation to Domain:  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
