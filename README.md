<h1>Network & Cybersecurity Tasks</h1>

<h2>Description</h2>
                
<h> I have compiled a list of various tasks in this section that showcase my expertise in different circumstances. It will include tasks that share investigating hash files, incident reports analysis, how to read Wireshark, and how to read tcpdump logs.<hr />


<h2>Investigating Hash File</h2>

<b>Scenario</b>

<h>Working as a level one security operations (SOC) analyst at a financial service company. I received an alert that there was a suspicious file being downloaded on one of the employee's computers. The employee received an email 1:11 p.m. containing an attachment that was password-protected. The password was provided in the email. When the password was entered to open the file at 1:13 p.m., a malicious payload was executed on the computer at 1:15 p.m. After retrieving the malicious file the intrusion detection system detected the file at 1:20 p.m. I create a SHA256 hash of the file. I researched the hash file in VirusTotal to see if there are any additional IoC's associated. </h>

<b>Response</b>

   - <h>After reviewing the hash file I documented it in the Pyramid of Pain template see below</h>

<b>Pyramid of Pain</b> 

![Screenshot 2024-01-15 200343](https://github.com/digital-md/Analyzing-network-structure-security/assets/156498985/5e141f85-b19c-4546-8f96-f37d5d8abac6)
![Screenshot 2024-01-15 200530](https://github.com/digital-md/Analyzing-network-structure-security/assets/156498985/69916b3c-2863-4575-bfcf-d441e673906c)

   

<h2>Incident Report Analysis </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
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
