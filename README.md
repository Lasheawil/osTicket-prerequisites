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

- Enable Internet Information Services (IIS)
- Web Platform Install
- Install My SQL (Set Up Usernames And Passwords)
- Configure permissions and Install Osticket

<h2>Installation Steps</h2>

<p align="center">
 <br/></b>
 I first created my Windows 10 Azure Virtual Machine (VM), which has 4 vCPUs and named it 'osticket-vm'. I Logged into the VM with Remote Desktop. Within the VM (osticket-vm), I then downloaded the osTicket-Installation-Files.zip and unzipped it onto my desktop. I will use the files within this folder to install osTicket and some of its dependencies. I went ahead and Installed / Enabled IIS in Windows With CGI (World Wide Web Services > Application Development Features > [X] CGI.) I verified that it was functional by checking the local host, 127.0.0.1 to loop back.
 <img src="https://github.com/Lasheawil/osTicket-prerequisites/blob/main/PrereqFiles/CGI.png" height="80%" width="80%"/>
 <br/>

  <p align="center">
 <img src="https://github.com/Lasheawil/osTicket-prerequisites/blob/main/PrereqFiles/IIS%20windows%20loopback.PNG" height="80%" width="80%"/>
 <br/>

</p>
<br />
