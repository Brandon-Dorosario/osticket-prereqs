<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This project outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1 - Log into the VM, download and unzip osTicket-Installation-Files.zip, then install PHP Manager, Rewrite Module, and PHP 7.3.8.
- Item 2 - Install MySQL 5.5.62, configure it with username "root" and password "root".
- Item 3 - Open IIS as Admin, register PHP, and restart IIS.
- Item 4 - Unzip and copy osTicket files to "c:\inetpub\wwwroot", rename to "osTicket", enable PHP extensions, and refresh the site.
- Item 5 - Set up the database using HeidiSQL, configure osTicket in the browser, and complete the installation. Clean up by deleting setup files and setting permissions on "ost-config.php".

<h2>Installation Steps</h2>

<p>
  
![OSticketfiles](https://github.com/user-attachments/assets/2ee7c8c4-37a5-4350-9492-241f74c70a6e)

</p>
<p>
 download and unzip osTicket-Installation-Files.zip.
</p>
<br />

<p>

![PHPDRIVE](https://github.com/user-attachments/assets/fde861ce-ab41-44a3-b509-1f2f862cbb54)

</p>
<p>
Created the directory C:\PHP
</p>
<br />

<p>
  
![enableIIS](https://github.com/user-attachments/assets/7af99e5b-e25d-4198-8e78-9232bb3478fb)

</p>
<p>
Open IIS as an Admin , Register PHP from within IIS (PHP Manager -> C:\PHP\php-cgi.exe) , Reload IIS (Open IIS, Stop and Start the server)

</p>
<br />

<p>  

![osTicketinstalled](https://github.com/user-attachments/assets/5a4a13c9-8764-49bf-95b5-24503b7d0e1c)

</p>
<p>
Installation completed.

