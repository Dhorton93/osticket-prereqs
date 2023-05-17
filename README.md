# osticket-prereqsp
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

- Install IIS
- Install Web platform installer
- Install MYSQL
- Install C++
- Configure permission install OSticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/gCClKgw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open the Control panel on your Windows Computer,Then select Programs and Features,Click on Turn Windows Features on or off.This will open the windows features dialog box. Scroll down the list and find internet Information Services, Expand the node by clicking on the + symbol next to it.
</p>
<br />

<p>
<img src="https://i.imgur.com/o7zj7qY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within the internet information Services you should select Web Management Tools and World Wide Web Services. Expand the World Wide Web Services node and select the specific features you require, such as Common HTTP feature or security.Click OK to close the Windows Features dialog box,Windows will start installing the selected componenets this process may take a few minutes. Once the installation is complete you can verify that IIS is installed by opening a web browser and typing localhost in the address bar. If you see the default IIS page it means IIS is successfully installed.
<img src="https://i.imgur.com/Hi0JBjs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 Once the installation is complete you can verify that IIS is installed by opening a web browser and typing localhost in the address bar. If you see the default IIS page it means IIS is successfully installed.
<img src="https://i.imgur.com/GruKFxj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
The link https:/www.mysql.com/. click downloads tab at the top of the page, scroll down to the MySql Community Edition Section, under the MySQL Community Server heading click on the download button for the version that is compatible with your operating system. Choose either the MySQL installer for windows or the MySQL community Server for other platforms(linux,macOS You will be directed to a new page with the list of available downloads. Select the appropiate download package for your operating system and click on the Download button next to it.Once download is complete locate the installer file run file and follow the installation wizard.The installer will guide you through the rest of installation including setting up the root password and configuring additional option if needed.After the installation is complete you have MySQL installed on your system.
<img src="https://i.imgur.com/OgWi4Oa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
