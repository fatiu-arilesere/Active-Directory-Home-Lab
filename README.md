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
<img src="https://i.imgur.com/nomt1yB.png" height="80%" width="80%" alt="AD installation"/>
<br />
<br />
Promoting Server to AD controller: <br/>
<img src="" height="80%" width="80%" alt=""/>
<br />
<br />
Creating OU with Powershell:  <br/>
<img src="https://i.imgur.com/gMYUIJe.png" height="80%" width="80%" alt="Code for creating OU"/>
<img src="https://i.imgur.com/Gt2SImF.png" height="80%" width="80%" alt="Created OU's in Active Directory Users and Computers Utility"/>
<br />
<br />
Creating an AD User with Powershell script:  <br/>
<img src="https://i.imgur.com/uGyT2zl.png" height="80%" width="80%" alt="Power-Shell Script"/>
<img src="https://i.imgur.com/NpKTOOx.png" height="80%" width="80%" alt="Created AD User's in Active Directory Users and Computers Utility"/>
<br />
<br />
Printer Installation:  <br/>
<img src="https://i.imgur.com/B4sVlqy.png" height="80%" width="80%" alt="Printer Deployment"/>
<img src="https://i.imgur.com/4f6m1A8.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/wY4VfGA.png" height="80%" width="80%" alt="Printer Drivers"/>
<img src="https://i.imgur.com/DuXX1yy.png" height="80%" width="80%" alt=""/>
<br />
<br />
Adding a BackupDrive:  <br/>
<img src="https://i.imgur.com/XXTFC7o.png" height="80%" width="80%" alt="Adding a drive to the VM"/>
<img src="https://i.imgur.com/KssqSqc.png" height="80%" width="80%" alt="Formating the newly added Disk from the Disk Management"/>
<img src="https://i.imgur.com/TLdPxXE.png" height="80%" width="80%" alt="Checking the Disk from the file manager"/>
<img src="https://i.imgur.com/e8SPFVU.png" height="80%" width="80%" alt="Installing the Windows Server Backup"/>
<img src="https://i.imgur.com/UNJDigP.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/3QJzvGt.png" height="80%" width="80%" alt="Windows Server Backup Configuration "/>
<img src="https://i.imgur.com/i7Ftxzm.png" height="80%" width="80%" alt=""/>
<br />
<br />
Creating Group Policy Object(GPO):  <br/>
<img src="https://i.imgur.com/uh17m9e.png" height="80%" width="80%" alt=""/>
<br />
<br />
Joining Workstation to Domain:  <br/>
<img src="https://i.imgur.com/DqQuoYD.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/vsKscpL.png" height="80%" width="80%" alt="Confirm the Workstation is Part of the Domain"/>
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
