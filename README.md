<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" height: 60%; width: 60%; />
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS (Internet Infromation Services)
- Install Web PLatform Installer
- Install MySQL & Setup Username/Password
- Install C++ Redistributable
- Configure Permissions & Install OSticket

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/GTaylorUS/OSTicket-Prereqs/assets/146995823/733525c6-8939-4829-b63c-59de39ab4876" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
To access the installer for osTicket, follow these steps:

1. Launch a web browser.

2. Enter the URL http://SERVER/osticket into the browser's address bar, replacing "SERVER" with the IP address or domain of your hosting server.

3. Upon visiting this URL, you will be directed to the installer. The installer will begin by verifying that you have met the necessary requirements.
</p>
<br />

<p>
<img src="https://github.com/GTaylorUS/OSTicket-Prereqs/assets/146995823/9b9167d9-bd4a-4643-8cbc-bcb27408ac9a"
 height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Complete all the required fields with the following details in mind for the database configuration:

MySQL Database: osticketdb <br>
MySQL User: osticketuser <br>
MySQL Password: Use the password that was created for the osticketuser.

Upon completion of the installation, you'll encounter a summary page. This page will provide you with essential instructions, including the final command you need to execute:

To change permissions, run the following command:

sudo chmod 0644 /var/www/html/osticket/include/ost-config.php

Additionally, you will find links that grant access to various osTicket tools.
<br>

Once you have entered this information, proceed by clicking the "Install Now" button.
</p>
<br />

<p>
<img src="https://github.com/GTaylorUS/OSTicket-Prereqs/assets/146995823/d392f146-117e-44be-aa71-79a9eefc68e2"
 height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />
