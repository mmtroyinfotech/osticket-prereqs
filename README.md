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

<p>1. PHPManagerForIIS_V1.5.0 is a tool for managing PHP installations on Internet Information Services (IIS). It allows you to register PHP with IIS, configure PHP settings, enable or disable PHP extensions, and manage multiple PHP versions on the same server.</p>

<p>2. rewrite_amd64_en-US is the installer file for the URL Rewrite Module version 2.0 for 64-bit Windows systems, which allows web administrators to create rules for URL rewriting and redirection on IIS.</p>

<p>3. php-7.3.8-nts-Win32-VC15-x86 is the installer file for PHP version 7.3.8, which is a non-thread-safe (NTS) build for 32-bit Windows systems, compiled with Visual C++ 15 (VS2017).</p>

<p>4. VC_redist.x86 is the installer for the Visual C++ Redistributable for Visual Studio 2015, 2017, 2019, and 2022, which installs the runtime libraries required for running applications built with these versions of Visual Studio on 32-bit Windows systems.</p>

<p>5. mysql-5.5.62-win3 is the installer for MySQL Community Server version 5.5.62, a widely-used open-source relational database management system for Windows.</p>

<p>6. osTicket-v1.15.8 is a maintenance release of the osTicket support ticketing system, which addresses security vulnerabilities and introduces various improvements and bug fixes.</p>

<p>7. HeidiSQL is a user-friendly tool for managing databases, allowing you to connect, browse, edit, and query your databases efficiently.</p>
<br />
<p><img src="https://imgur.com/n839Ura.png"/></p>

<p>
I may make a video going through each file and installing them. There will be to many slides if I was to screenshot all of the process.
</p>
<br />
