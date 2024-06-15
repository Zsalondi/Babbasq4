<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Babba's Gullah restaurant: Q4 Performance Goals</h1>
This tutorial outlines how to determine some performance goals for a company’s email and social media marketing campaigns.<br />


<!---<h2>Video Demonstration</h2>

 ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com) --->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows
- Download / Install PHP Manager for IIS
- Download / Install the Rewrite Module 
- Create the directory C:\PHP
- Download / Unzip PHP 7.3.8
- Download / Install VC_redist.x86.exe.
- Download / Install MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
We will configure and activate Internet Information Services (IIS), a robust web server platform that enables a computer to host websites. Given that OsTicket operates through a web interface, it's essential to establish and fine-tune IIS settings to ensure the seamless operation of OsTicket<br/> 
 
Initiate the process by right-clicking the Start menu, selecting 'Run', and then entering 'control' to access the Control Panel. Navigate to 'Programs' and select 'Turn Windows features on or off'. Within the list, locate 'Internet Information Services > World Wide Web Services > Application Development Features'. Here, ensure to enable 'CGI' along with all of the 'Common HTTP Features' to properly configure the server environment. Select 'Ok' to initiate installation.
</p>
<p>
<img src="https://i.imgur.com/OxWAXSI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
To verify the successful installation of IIS, open your web browser and enter '127.0.0.1' into the address bar. This IP address is known as the 'localhost' and is used to refer to the computer you're currently using. If IIS has been installed and configured correctly, you should be greeted with the default IIS welcome page. This step is crucial as it confirms that your system is properly set up to host web applications.</p>
<p>
<img src="https://i.imgur.com/bn3eMwO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
