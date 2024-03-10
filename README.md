<h1>SIEM-AZURE-SENTINAL-AND-MAP</h1>


 ### Description of Project
 The Script below takes IP's from Event viewer then pushes them to the GEOIP website where it grabs its Location Information then plots it on the Azure Sentinal Map.This logs every single Failed log in attempt for me using this third party API, I then connected 
 it to a Live VM machine I created in Azure that Acts as a Honey Pot. 
<h2>Description</h2>
<b>
</b>
<br />
<br />

![Power shell Script](https://github.com/Dmoore125/SIEM--AZURE-SENTINAL-AND-MAP/assets/162640561/9d97f14e-557e-4f66-b846-afe44e3417ef)

![EV_FAILED_IPGEO](https://github.com/Dmoore125/SIEM--AZURE-SENTINAL-AND-MAP/assets/162640561/459a4f8d-a691-4767-9f14-71dd4e4d5984)


</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Website Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from alll around the world coming in!</h2>

![SIEM_WORLDMAP_RDP_BRUTEFORCE](https://github.com/Dmoore125/SIEM--AZURE-SENTINAL-AND-MAP/assets/162640561/5e83cb06-d173-4446-93c1-796eef1acd4f)
<p align="center">

</p>

 ### Steps of Project
1.  Created Azure Subscription
2.  Created Virtual Machine
3.  Allowed all in Firewall
4.  Created Log Analytics Workspace
5.  Enable gathering VM logs in Security Center of Azure
6.  Connect Log Analytics to my VM
7.  Setup Azure Sentinel
8.  Log into VM with Remote Desktop (failed 1 logon to view)
9.  Observed Event Viewer Logs in my VM
10. Turn of Windows Firewall in my VM
11. Downloaded PowerShell Script for IPGEO
12. Get Geolocation.io API Key
13. Run Script To get Geo Data from attackers world wild
14. Created custom log in LAW to bring in our custom log for IPGEO
15. Create custom fields/extract fields from raw custom log data ( isolating portions of the log data and extracting )
16. Tested Extracts
17. Setup map in sentinel with Latitude and Longitude (or country)
18. Waited some time then snapped a picture of the map.

<p align="center">

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
