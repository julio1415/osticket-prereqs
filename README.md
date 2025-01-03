<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Prerequisites and Installation

This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.

## Video Demonstration

- [How To Install osTicket with Prerequisites](https://www.youtube.com)

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 (21H2)

## List of Prerequisites

- **Web Server (IIS)**: Ensure that IIS is installed and configured on your Windows VM.
- **PHP**: PHP 7.4 or newer must be installed and configured to run with IIS.
- **MySQL**: MySQL 5.7 or MariaDB 10.3 or newer must be available to store the osTicket data.
- **PHP Extensions**: Required PHP extensions include gd, mbstring, mysqli, and intl.
- **Mail Server**: An SMTP server must be configured for osTicket to send out email notifications.

## Installation Steps

### 1. Preparing the Environment
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Environment Preparation"/>
</p>
<p>
Set up your Microsoft Azure virtual machine and configure Windows 10 and IIS to host osTicket.
</p>

### 2. Installing PHP and Required Extensions
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="PHP Installation"/>
</p>
<p>
Install PHP via the Web Platform Installer in IIS and ensure all required extensions are enabled.
</p>

### 3. Configuring the Database
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Database Configuration"/>
</p>
<p>
Set up MySQL or MariaDB and create a database and user specifically for osTicket.
</p>

### 4. Installing osTicket
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="osTicket Installation"/>
</p>
<p>
Download and extract osTicket, then follow the web-based installation process to configure the helpdesk system.
</p>

This structured guide provides clear and concise instructions for setting up osTicket, complete with steps and images for each phase of the installation process.
