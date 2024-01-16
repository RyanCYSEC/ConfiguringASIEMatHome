# Configuring a SIEM lab at home via Virtual Box and Elastic

<h1>Purpose</h1>
The goal of this project was to generate an at-home cybersecurity laboratory where I could develop a deeper understanding of security information and event management (SIEM) tools, how security incidents are detected, investigated, and responded to in operational environments. Additionally, going through this project would enable me to conduct follow on cyber skills building exercises and gain hands-on experience.
 

<h2>Skills Demonstrated</h2>

•	Elastic Stack SIEM Configuration and Management: 

Successfully set up and configured Elastic Stack SIEM in a home lab environment. Demonstrated proficiency in deploying a Kali Linux VM, configuring Elastic Agents for log collection, and forwarding data to the SIEM for effective security event monitoring.

•	Security Event Simulation and Analysis: 

Acquired hands-on experience in generating and analyzing security events using Nmap on Kali Linux. Proficient in querying Elastic SIEM to identify and investigate security incidents, enhancing skills in network security monitoring and threat detection.

•	Visualization and Alerting in SIEM: 

Developed a custom dashboard in Elastic SIEM to visualize security events, demonstrating skills in data interpretation and pattern recognition. Successfully created and tested alert rules for detecting specific security events, showing competency in proactive incident response and alert management.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Kali Linux</b> 
- <b>Elastic Cloud</b>
- <b>Nmap</b>
- <b>Virtual Box</b>



<h2>Project walk-through:</h2>
<h3>Phase 1: Set up a cloud account and deployment where the SIEM can be run.<h3>
<p align="left">
The first step in setting up this type of home lab was to gain access to a cloud environment. For my limited needs, purposes, and resources, I chose to utilize a free trial cloud instance via cloud.elastic.co.  <br/>
<img src="[https://i.imgur.com/E6BhavB.png]" height="80%" width="80%" alt="SIEM Steps"/>
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
<img src="https://i.imgur.com/IgLLUAM.jpeg)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
