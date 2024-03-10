<h1>SIEM-AZURE-SENTINAL-AND-MAP</h1>


 ### Description of Project
 The Script below takes IP's from Event viewer then pushes them to the GEOIP website where it grabs its Location Information then plots it on the Azure Sentinal Map.This logs every single Failed log in attempt for me using this third party API, I then connected 
 it to a Live VM machine I created in Azure that Acts as a Honey Pot. 


![SCRIPT_IPGEPLOCATOR_POWERSHELL](https://github.com/Dmoore125/SIEM--AZURE-SENTINAL-AND-MAP/assets/162640561/f18191cb-f614-466c-ad67-11cb870da935)

<h2>Description</h2>
<b>
</b>
<br />
<br />



</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/LhDCRz4.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
