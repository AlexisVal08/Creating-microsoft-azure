<p align="center">
<img src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/3818220a-1891-411b-838b-9017ee37f8f2"/>
</p>

# Microsoft Azure - Prerequisites and Installation

This tutorial outlines the prerequisites and installation for Microsoft Azure

## Environments and Technologies Used

- **Microsoft azure website**
- **Internet service connection**
- **Internet browser microsoft edge**
- **Operating System:** Windows 10 (21H2)

## List of Prerequisites

- **Computer with internet connection**
- **Credit card(required for free azure credits)**

## Installation Steps

## 1. **:**

   - Go to [Azure portal Website](https://portal.azure.com/).
   -
   -
<img width="428" alt="Step1A" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/9be5ed9b-8a1d-42c3-a0a6-74ccb82df3bf">
<img width="428" alt="Step" src="">
<img width="428" alt="Step" src="">



## 2. **:**

   - Connect using Remote Desktop Connection app using the public IP address of the VM.
   - Also using the assigned login account and password
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 3. **:**

   - Go to Control Panel -> Programs -> Turn Windows features on and off.
   - Install/enable IIS with CGI and Common HTTP Features
   - World Wide Web Services -> Application Development Features
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 4. **:**

   - Download and install PH
   -P Manager for IIS (PHPManagerForIIS_V1.5.0.msi).
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 5. **:**

   - Download and install the Rewrite Module (rewrite_amd64_en-US.msi).
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 6. **:**

   - Create a Directory folder named `PHP` in the C drive.
   - Download PHP 7.3.8 (php-7.3.88-nts-Win32-VC15-x866.zip) extract and unzip it into `C:\PHP`.
   - Download and install VC_redist.x86.exe from the installation files.
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 7. **:**

   - Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi). For installation accept agreements and set my sql as typical. 
   - Set up MySQL with a root password (e.g., Password1).
   - MySQL server instance configuration wizard installation completion will create a database within the computer so it can storage occupied for osTicket.
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 8. **:**

   - Open IIS as an administrator.
   - Click on PHP Manager, register and enable the new PHP version by providing the path to `php-cgi.exe` in `C:\PHP`.
   - Whenever updating anything in the IIS it is recommendeded to restart the web server in manage server.
   - Reload IIS, Open IIS, Stop and Start the server.
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 9. **:**

   - Download osTicket from the Installation Files Folder.
   - Extract and copy the "upload" folder onto `C:\inetpub\wwwroot`. (This is our servers main folder)
   - Rename the "upload" folder to "osTicket".
   - Reload IIS.
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 10. **:**

   - Go to sites -> Default web site -> osTicket in IIS.
   - In the right side click *Browser *:80*
   - GO back to sites -> osticket -> In IIS Enable the following PHP extensions in PHP Manager:
      - php_imap.dll
      - php_intl.dll
      - php_opcache.dll
   - Check on osticket window if the PHP extentions have been updated with the green checkmark
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">



