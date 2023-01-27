<h1>REST API for Medical Clinic Database Project (Node JS & Express)</h1>

<img src="https://imgur.com/dgYs8Ga.png" height="80%" width="80%" alt="diagram"/>
<img src="https://imgur.com/Toy5vt4.png" height="80%" width="80%" alt="diagram"/>

<h2>Description</h2>
In this project, I setup a REST API that tracks a Medical Clinics database. The API will be able to get, create, update, and delete patient information. This lab is done using Python and JSON on Virtual Studio Code. I also use Node JS and Express to run the server, and Postman to send data. This is a step by step guide so feel free to follow along! 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Python</b>
- <b>JSON</b>

<h2>Environments Used </h2>

- <b>Virtual Studio Code</b>
- <b>Postman</b>

<h2>Program walk-through:</h2>

<p align="center">
First we will install some packages that will be needed to complete this project. We will initialize the Node Package Manager (NPM) by using the command "init npm". nmp is used to manage dependencies: <br/>
<img src="https://imgur.com/GglLUNs.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Install the following packages and ensure VS Code is running as adminstrator to use Powershell commands:  <br/>
<img src="https://imgur.com/efz3U4F.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Create a Log Analytics Workspace to log the inbound traffic to the VM: <br/>
<img src="https://imgur.com/WVrBleM.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Connect the Log Analytics Workspace to the VM:  <br/>
<img src="https://imgur.com/cvc2aWg.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Run the VM and connect to it via Remote Desktop Connection:  <br/>
<img src="https://imgur.com/cywVdub.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Turn off Windows Firewall within the RDC VM:  <br/>
<img src="https://imgur.com/blLn2D8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Test ping from personal computer to VM:  <br/>
<img src="https://imgur.com/pfj1r2L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Get an API Key if you dont already have one (ipgeolocation.io):  <br/>
<img src="https://imgur.com/55RDEz9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run custom script with your API Key on Windows PowerShell ISE to get Geo Data from attackers :  <br/>
<img src="https://imgur.com/IZv9ErM.png" height="80%" width="80%" alt="Cyber Attack Event Management"/>
<br />
<br />
Save script as log file and it'll create a txt file with all the failed login attempts Geo Data :  <br/>
<img src="https://imgur.com/BTvCbJb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a custom log thats linked to the txt file with all the failed login attempts Geo Data:  <br/>
<img src="https://imgur.com/pOMAErE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using the SQL Query in logs, observe the data from the custom log:  <br/>
<img src="https://imgur.com/feqrZqR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Extract the fields from raw custom logs:  <br/>
<img src="https://imgur.com/jLsYsXo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check custom fields to confirm before testing:  <br/>
<img src="https://imgur.com/AHNYV0x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Test new custom fields which were extracted to see if they collect the data:  <br/>
<img src="https://imgur.com/rjCRuf2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Microsoft Sentinel:  <br/>
<img src="https://imgur.com/Ij2CQgX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Within Microsoft Sentinel, setup a map in workbooks using longitude and latitude:  <br/>
<img src="https://imgur.com/TnOTZlc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use the following SQL Query to isolate which data to be shown, and the following map settings to display on world map:  <br/>
<img src="https://imgur.com/jkC9uK0.png" height="80%" width="80%" alt="workbook setup"/>
<img src="https://imgur.com/TAeiN3Q.png" height="80%" width="80%" alt="workbook setup"/>
<img src="https://imgur.com/F7WlgYG.png" height="80%" width="80%" alt="workbook setup"/>
<br />
<br />
After a couple hours the VM will be found by the cyber attackers of the world. Now you can observe Geo Data from where your VM is being breached!:  <br/>
<img src="https://imgur.com/srMTOOG.png" height="80%" width="80%" alt="Cyber Attack Event Management"/>
<br />
<br />
This Concludes This Microsoft Azure SIEM Project!
NOTE: You can toggle map setting to display other custom fields  <br/>
<br />
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
