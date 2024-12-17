<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

<b>- Microsoft Azure (Virtual Machines/Compute):</b> 
  1. Sign up and create a free subscription: https://azure.microsoft.com/en-us/free/
  2. Get logged into the Azure Portal: https://portal.azure.com
  3. Create an Azure Virtual Machine (Windows 10, 4 vCPUs)
     - The VM provides an isolated Windows environment to install and configure osTicket, ensuring a controlled setup.
  4. Log into the VM using Remote Desktop
     - This step grants access to the VM's graphical interface to perform installations and configurations.


<b>- osTicket Installation Files:</b> 
 1. Download the osTicket-Installation-Files.zip: [osTicket.zip](https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD) and unzip the file onto your VM's desktop into a folder.
    - The installation files contain all the necessary tools, dependencies, and software required to set up osTicket.


<h2>Installation Steps</h2>


<p>
<img src="https://github.com/user-attachments/assets/a7951c34-3cc6-4978-a9cc-1657848e9f2a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/6c4a18bf-0d44-4a78-91e7-b2bcc126f724" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First we need to Install / Enable IIS in Windows WITH CGI. IIS (Internet Information Services) is the web server needed to host osTicket, and CGI allows IIS to execute PHP scripts.
  
  1.  Navigate to Control Panel > Programs > Programs and Features and head into "Turn Windows Features on or off"
  2.   Check the box "internet infortmation services (ISS)"
  3.  Expand ISS -> Expand "World Wide Web Services" -> Expand "Application Development Feature" -> Check the box "CGI"
  4.  Press "OK" to continue with the installation 



</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
