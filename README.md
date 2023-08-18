<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This guide outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Key Prerequisites</h2>

- Internet Information Services(IIS)
- PHP Manager
- C++ Redistributable
- MySQL Server
- Heidi SQL
- Download/Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/ZOhWuQF.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 
<p> The very first step in the installation of osTicket is to install/enable Internet Informatin Services(IIS) on computer which 
is done by first going to the device's control panel>programs & featrures>turn windows featurs on/off>click box for 
"Internet Information Services" as next image shows.

</p>
<br />

<p>
<img src="https://i.imgur.com/f6czbb7.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Image above shows the checkbox selection for  "Internet Information Services" 
</p>
<br />

<p>
<img src="https://i.imgur.com/uP6k5Zz.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To ensure the proper installation of IIS on the device and after all the necessary steps have been performed the user can type the 
device's loopback address (in this case 127.0.0.1) in the device's browser to test if the IIS home screen opens up as the above image 
shows.
</p>
<br /># osticket-prerequisites

<p>
<img src="https://i.imgur.com/PKPvdZX.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step is to install "PHP Manager for IIS" as above image shows followed by: download/install Rewrite Module, create the directory (C:) for PHP, download/install PHP-7.3.8-nts-win32-vc15x86 which is a general server side scripting language some applications need.
</p>
<br /># osticket-prerequisites


<p>
<img src="https://i.imgur.com/yaJZJLg.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step is to download/install C++ Redistributable which PHP requires. 
</p>
<br /># osticket-prerequisites

<p>
<img src="https://i.imgur.com/hziG2FF.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step is to download/install MySQL server which will serve as database for our osTicket application.
</p>
<br /># osticket-prerequisites

<p>
<img src="https://i.imgur.com/X4QXRl4.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step is to download/install osTicket and set up osTicket admin credentials followed by: dowload/install HeidiSQL>sync HeidiSQL with our MySQL database which lets us interact with our SQL databse>enter MySQL credentials in osTicket settings>create new database in Heidi called osTicket>click "install" in osTicket settings>do some "clean-up". If osTicket installed properly the above image should appear on device's screen...Go to your osTicket admin login link to test final installation success! 
</p>
<br /># osticket-prerequisites


