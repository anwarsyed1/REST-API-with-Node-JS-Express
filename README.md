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
- <b>Windows 10</b>

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
Create a js file named whatever, in our case index.js in your API folder directory. I then built a simple outline of the API running on localhost port 3000 which I will build on to. Use the command "nodemon index.js" to start the Node JS server.: <br/>
<img src="https://imgur.com/mYdDrgM.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Here is the outline of the API and its functionalities, as well as the use of Postman to send API request to our REST API (POST, PUT, DELETE, and GET). We will be using header for authentication and body for miscellaneous purposes (reason why I used bodyParser):  <br/>
<img src="https://imgur.com/IuvhRab.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Build the database for the medical records and the patients:  <br/>
<img src="https://imgur.com/9YZZJq1.png" height="80%" width="80%" alt="set up"/>
<br />
<br />
Now I will begin working on the functionalities, for the GET method there are a couple things we need to verify as shown below before we can provide the medical records. I've also logged the headers data from Postman to my server to test if the data is being recieved correctly:  <br/>
<img src="https://imgur.com/jKDTMRz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/bwIMDYd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I then created a if statement which checks to verify that if the values in the "sin" header does not match then respond with a status 404 code using a JSON message "Patient not found".:  <br/>
<img src="https://imgur.com/edFEDXC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Then created another if statement to verify if the firstname and lastname match with the corresponding sin. If successfull return status 200 (OK) with the mediacal record and a JSON message, else return an error JSON message with status 401 (unauthorized):  <br/>
<img src="https://imgur.com/bGWNHPr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
:  <br/>
<img src="https://imgur.com/INiv9Ii.png" height="80%" width="80%" alt="Cyber Attack Event Management"/>
<br />
<br />
For the next function, to create a new patient we want to be able to assert a new patient from the header to the database. So if the patients sin match equals the firstname, lastname, and phone. then add the patient to the database with a status 200 (OK):  
<br/>
<img src="https://imgur.com/W5alK8v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
