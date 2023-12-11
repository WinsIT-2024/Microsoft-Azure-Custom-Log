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


<h2>Project Walk-through:</h2>

<p align="left">
Azure Virtual Machine Creation:<br/>
The first step involved setting up a virtual machine in Microsoft Azure. This process included selecting the appropriate VM size, configuring the network settings, and setting up the storage. <br/> 
<img src="https://imgur.com/SXbbun6.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<br />
Launch Command Prompt on your host computer from a different and type "ping (IPv4 address of the target machine)" to confirm you have connection:  <br/>
<img src="https://imgur.com/GZMnFXS.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<br />
Open Nessus Essentials from your host machine: <br/>
<img src="https://imgur.com/BlV1PeX.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<br />
Next Steps Coming Soon:  <br/>
<img src="https://imgur.com/NXzuety.png" height="80%" width="80%" alt="Azure Custom Log"/>
<br />
<br />
<h2>Project Conclusion:</h2>
This project successfully demonstrates the power of combining Azure VM provisioning, automated PowerShell scripting, Log Analytics data collection, and Defender workbook visualization to achieve comprehensive login tracking and insightful threat analysis. This solution can be customized and extended to address specific security needs and provide valuable insights for proactive threat management. <br/>
<img src="https://imgur.com/VctnWQI.png" height="80%" width="80%" alt="Azure Custom Log"/>

 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
