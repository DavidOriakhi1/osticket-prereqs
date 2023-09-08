osticket prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

-Create Resource group in Azure

-Connect to Remote Desktop

-Install: Internet Information Services, PHP manager for IIS, Rewrite Module, VC_Redist, My SQL, osTicket

-Download Heidi SQL

-Install osTicket


- 
<h2>Installation Steps</h2>


<p>
<img src="https://i.imgur.com/OeZuWHg.jpg"height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/BSdm146.jpg" width="80%" alt="Disk Sanitization Steps"/></p>
<p>
 1. Create a resource group in microsoft azure & a virtual machine using windows 10, with 2 vcpu's
</p>
<br />



<p>
<img src="https://i.imgur.com/jMYdQXJ.jpg"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
2. Copy+paste the 'public Ip address' of the Virtual machine created into 'Remote desktop' and log in with the username and password you created
<p>
</p>
<br />


<p>
<img src="https://i.imgur.com/STp7isr.jpg"width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/tCTmjhD.jpg"width="80%" alt="Disk Sanitization Steps"/>
3. Install 'Internet Information Services' (IIS) and enable 'CGI'
<p>
</p>
<br />


<p>
<img src="https://i.imgur.com/HoMrzwM.jpg"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
4. Download+Install: PHP manager for IIS, Rewrite module, and put contents into your 'C:\PHP' Folder
<p>
</p>
<br />



<p>
<img src="https://i.imgur.com/xpD1Pq8.jpg"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
5. Download and Install 'MYSQL' and set your username and password
<p>
</p>
<br />


<p>
<img src="https://i.imgur.com/vv8KHJP.jpg"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
6. Download osTicket and configure the recommended settings. Next, create your helpdesk url, email, and a username and password to use to log in to osTicket once installed. (Dont Forget!)
<p>
</p>
<br />



<p>
<img src="https://i.imgur.com/lMq0KUf.jpg"80%" width="80%" 
</p>

7. Download 'Heidi SQL' and create a new session with a username and password.
-Next, connect to the session and create a database and name it 'osTicket'
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/vv8KHJP.jpg"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
8. Finally, osTicket is installed with no errors! Now able to log in as an admin with the username and password created previously.
<p>
</p>
<br />
