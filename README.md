<h1>Network & Cybersecurity Tasks</h1>

<h2>Description</h2>
                
<h> I have compiled a list of various tasks in this section that showcase my expertise in different circumstances. It will include tasks that share investigating hash files, and incident reports analysis, using TCPdump logs.<hr />


<h2>Investigating Hash File</h2>

<b>Scenario</b>

<h>Working as a level one security operations (SOC) analyst at a financial service company. I received an alert that there was a suspicious file being downloaded on one of the employee's computers. The employee received an email 1:11 p.m. containing an attachment that was password-protected. The password was provided in the email. When the password was entered to open the file at 1:13 p.m., a malicious payload was executed on the computer at 1:15 p.m. After retrieving the malicious file the intrusion detection system detected the file at 1:20 p.m. I create a SHA256 hash of the file. I researched the hash file in VirusTotal to see if there are any additional IoC's associated. </h>

<b>Response</b>

   - <h>After reviewing the hash file I documented it with the Pyramid of Pain template see below</h>

<b>Pyramid of Pain</b> 

![Screenshot 2024-01-15 200343](https://github.com/digital-md/Analyzing-network-structure-security/assets/156498985/5e141f85-b19c-4546-8f96-f37d5d8abac6)
![Screenshot 2024-01-15 200530](https://github.com/digital-md/Analyzing-network-structure-security/assets/156498985/69916b3c-2863-4575-bfcf-d441e673906c)

   

<h2>Incident Report Network Attack </h2>

<b>Scenario</b>

<h>Working as a security analyst for a travel agency that advertises sales and promotions on their website. The employees of the company access the company's sales webpage to search for vacation packages that customers may like. One afternoon, I received an automated alert from the monitoring system indicating a problem with the web server. I attempted to visit the company's website but received a connection timeout error message in my browser. I used a packet sniffer to capture data packets in transit to and from the web server. I noticed a large number of TCP SYN requests coming from an unfamiliar IP address. The server appeared to be overwhelmed by the volume of incoming traffic and was losing its ability to respond to the number of SYN requests. I took the server offline temporarily so the machine could recover and return to a normal operating status. I also configured the company's firewall to block the IP address that was sending the abnormal number of SYN requests. Knowing that the IP blocking solution won't last that long, as an attacker could spoof other IP addresses to get around this block. I alerted the manager about this problem quickly and discussed the next steps to stop this attacker and prevent this problem from happening again. I need to be prepared to tell my boss the type of attack that was discovered and how it was affecting the web server and employees.</h>

<b>Response</b>





<h2>Incident Report Network Traffic Analysis</h2>

<b>Scenario</b>

<h>In this scenario I will be working with a company specializing in providing IT consulting services. Some customers contacted the company to report they were not able to access the company's website www.yummyrecipesforme.com mock website. They were seeing an error "destination port unreachable" when the page loaded. I was asked to analyze the situation and determine which network protocol was affected during this incident. Once I visited the website I received the same error message. Next, I loaded a network analyzer tool called "tcpdump" and then I loaded the page again. The results showed a lot of packets sending UDP packets and receiving an ICMP response in return. The results contained an error message: "udp port 53 unreachable." See Below</h>

<b>Response</b>

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
