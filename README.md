<h1>Microsoft Azure Custom Log</h1>


<h2>Project Overview</h2>
This project demonstrates the creation of a virtual machine (VM) in Microsoft Azure and the implementation of an automated PowerShell script for robust login attempt tracking and visualization. The script tracks failed login attempts and sends that information to a Log Analytics workspace. The raw data is then extracted from the workspace using a custom query and displayed as a world map in a Microsoft Defender workbook, providing insightful geographical context.
<br />

<h2>Key Technologies</h2>

- <b>Microsoft Azure</b>
- <b>Microsoft Defender</b>
- <b>Log Analytics</b>  
- <b>Kusto Query Language(KQL)</b>
- <b>PowerShell</b>


<h2>Environment Used </h2>

- <b>Windows® 10</b> (22H2)


<h2>Project Walkthrough:</h2>

<p align="left">
<b>Virtual Machine Creation:</b> <br/>
The first step involved setting up a virtual machine in Microsoft Azure. This process included selecting the appropriate VM size, configuring the network settings, and setting up the storage.Then created a resource group and allocated the appropriate resources. <br/> 
   
<img src="https://imgur.com/SXbbun6.png" height="80%" width="80%" alt="Azure Custom Log"/>

---

<br/>
<br/>
<b>Automate Login Tracking with PowerShell:</b> <br/>
Next, a PowerShell script was developed to track failed login attempts on the VM. This script was set to run automatically using Azure Automation, ensuring that it would continuously monitor the system without manual intervention. <br/>

<img src="https://imgur.com/wnqWQVn.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<img src="https://imgur.com/83aPhPF.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<img src="https://imgur.com/uZR50j7.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br/>
<img src="https://imgur.com/bpqFIh0.png" height="80%" width="80%" alt="Azure Custom Log"/>

---
<br />
<br />
<b>Log Analytics Workspace:</b>  <br/>
The data from the PowerShell script was then sent to a Log Analytics workspace. This workspace served as a centralized location for all log data, allowing for easy access and analysis. The workspace was configured to ingest the specific data points needed for this project, including the timestamp of the failed login attempt, the user name, and the IP address. <br/>

<img src="https://imgur.com/YeyRrvZ.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />

---

<b>Data Extraction and Visualization:</b> <br/>
Finally, the raw data from the Log Analytics workspace was extracted using a custom query and imported into a Microsoft Defender workbook. This workbook was set up to display the data as a world map, providing a visual representation of the locations of the failed login attempts. This visualization aids in identifying patterns and trends in the data, offering valuable insights into potential security threats. <br/>

<img src="https://imgur.com/fQMaIW0.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<img src="https://imgur.com/LKPbICq.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br/>
<br/>

---
<b>Project Benefits:</b>

- Enhanced security posture by actively tracking and identifying failed login attempts.
- Improved incident response capabilities with centralized data collection and analysis.
- Increased situational awareness with clear visualization of global login activity patterns.
- Proactive threat detection and mitigation through identifying potential attack origins.
- Automation of routine tasks for improved efficiency and scalability.
<br/>
<h2>Project Conclusion:</h2>
This project successfully demonstrates the power of combining Azure VM provisioning, automated PowerShell scripting, Log Analytics data collection, and Defender workbook visualization to achieve comprehensive login tracking and insightful threat analysis. This solution can be customized and extended to address specific security needs and provide valuable insights for proactive threat management. <br/>
<img src="https://imgur.com/LYcWfZf.png" height="80%" width="80%" alt="Azure Custom Log"/>

 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
