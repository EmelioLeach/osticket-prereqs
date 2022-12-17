# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
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

- Create virtual machine 
- Install / Enable IIS in Windows
- Install osTicket v1.15.8 files
- Install HeidiSQL
- Item 5

<h2>Installation Steps</h2>

<p> Hello welcome to my first tutorial! First we must have an active subscription with Azure to create a resource group and a virtual machine. The VM will protect our actual computer while we use the remote computer to setup a osticketing system. 
<img src=https://i.imgur.com/8aYi62y.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  Next we will use the public ip address from the vm to connect into and install ISS by opening the control panal from the start menu.Select turn windows features on or off at the top left and enable Internet Information Services.
<img src=https://i.imgur.com/giNG5GS.png height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>Download Web Platform installer this helps other web applications run smoothly, here is a link to that application https://drive.google.com/drive/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
<br />

<p>
<img src=https://i.imgur.com/sspi8MP.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will install these items that are required for the osticketing system to work 
</p><img src=https://i.imgur.com/52biG6y.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Now we can use IIS to browse 80 folder and osTicket installer should pop up its own webpage.PHP is a programming language and uses a mysql database to store information.


<img src=https://i.imgur.com/baw1rsr.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we can go into IIS and open PhP managenment and navigate down to OSticket and enable php_intl.dll
</p>
<img src=https://i.imgur.com/SXhmCFb.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
