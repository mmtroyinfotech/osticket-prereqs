<p align="center">
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

- Create a Azure Virtual Machine: https://github.com/mmtroyinfotech/azure-resource-group-virtual-machines
- Internet Access: Ensure the VM has internet access to download necessary software.
- Remote Desktop Connection: Install Microsoft RD Client (Remote Desktop) to connect to the VM.
- IIS (Internet Information Services): Install IIS on the VM.
- PHP Manager for IIS: Download and install PHP Manager for IIS.
- Rewrite Module: Download and install the rewrite module for IIS.
- PHP 7.3: Download and install PHP 7.3.
- VC Redist: Install VC Redist (Visual C++ Redistributable) for PHP.
- MySQL 5.5: Download and install MySQL 5.5.
- osTicket Files: Download osTicket from the official website.
- Permissions: Set appropriate permissions for osTicket files and directories

<h2>Installation Steps</h2>

- Type Remote Desktop in the start menu and click remote desktop.
<p>
<img src="https://imgur.com/GJKCqN8.png"/>
</p>
<p>
<img src="https://imgur.com/byDkS9t.png"/>
</p>

- Input Virtual Machine public address into Remote Desktop. Click Connect.
- Input Username and Password created when vm was created. Then OK
<p>
<img src="https://imgur.com/fuyoNxp.png"/>
</p>

- VM will load up.
- All the rest of the steps will done in Virtual Machine.
<p>
<img src="https://imgur.com/h0YhpCP.png"/>
</p>
<br />

<h2>Install / Enable IIS in Windows WITH CGI</h2>

<p>
<img src="https://imgur.com/xKHzc77.png"/>
</p>
<p>
<img src="https://imgur.com/2uu5UM4.png"/>
</p>
<p>
<img src="https://imgur.com/9n15mwQ.png"/>
</p>
<p>
<img src="https://imgur.com/C5ztdWN.png"/>
</p>
<p>
<img src="https://imgur.com/SQoayij.png"/>
</p>
<p>
<img src="https://imgur.com/3KklzpS.png"/>
</p>
<p>
<img src="https://imgur.com/QuDN4oC.png"/>
</p>
<p>
<img src="https://imgur.com/3OLQaHv.png"/>
</p>
<p>
<img src="https://imgur.com/yuJPjbr.png"/>
</p>

<h2>osTicket Installation</h2>

<p>
In my class lab I was provided with links to download osTicket and it's packages. But just follow along for now.
</p>
- This is the osTicket folder extracted.
<p>
<img src="https://imgur.com/Eg4rkvq.png"/>
</p>
- These of the packages
<p>
<img src="https://imgur.com/Pm41j62.png"/>
</p>

- HeidiSQL_12.3.0.6589_Setup
<p>HeidiSQL is a user-friendly tool for managing databases, allowing you to connect, browse, edit, and query your databases efficiently.</p>
- mysql-5.5.62-win32
- osTicket-v1.15.8
- php-7.3.8-nts-Win32-VC15-x86
- PHPManagerForIIS_V1.5.0
- rewrite_amd64_en-US
- VC_redist.x86
  
<p>
I may make a video going through each file and installing them.
</p>
<br />


<br />
