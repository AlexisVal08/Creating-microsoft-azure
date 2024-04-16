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

## 1. **Go to website to begin a brand new Microsoft Azure account:**

   - Go to [Azure portal Website](https://portal.azure.com/). Make sure not to click on ads.
   - Sign up for a brand new account, click where it states `Start free`.
   - Create new acoount with your email and put in the verfication code sent to your account.
   - fill in all your pesronal inforamtion then your acount will be ready for you.
<img width="428" alt="Step1A" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/9be5ed9b-8a1d-42c3-a0a6-74ccb82df3bf">
<img width="428" alt="Step1B" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/95eacf14-ff6e-4012-8014-b4f1f9272f94">
<img width="428" alt="Step1C" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/08cecbb5-f3c2-46e3-afe2-0a3613ce4c81">
<img width="428" alt="Step1D" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/f0a89ffd-169f-47bf-9e37-1171dbde3021">
<img width="428" alt="Step1E" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/196f2062-b1f6-4542-bf51-b5008a2ff673">
<img width="428" alt="Step1F" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/1d57486c-27eb-467b-8ce3-5ac64bf2bd3a">

## 2. **Within the Azure Portal, Create a Resource Group:**

   - click go to azure portal and you are in the main page now logged in.
   - Check to see if your new account created a subcription default directory
   - This is the default subscription that is active and with a $200 credit to use for your azure account 
<img width="428" alt="Step2A" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/8ef075df-3437-4322-96b6-003f329493a6">
<img width="428" alt="Step2B" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/4fe7de04-dfa5-4859-9056-08226f2b3d09">
<img width="428" alt="Step2C" src="https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/20f50af9-2957-4955-83f9-26960fa28284">
<img width="428" alt="Step2D" src="(https://github.com/AlexisVal08/Creating-mircosoft-azure/assets/135868956/f4caca7e-a2ed-4e1b-8882-4c8c171b2047">
<img width="428" alt="Ste2Ep" src="">

## 3. **Create a Storage Account within the Resource Group created in Step 2:**

   - Go to Control Panel -> Programs -> Turn Windows features on and off.
   - Install/enable IIS with CGI and Common HTTP Features
   - World Wide Web Services -> Application Development Features
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 4. **Create a file on your local desktop and upload it into the Storage Account:**

   - Download and install PH
   -P Manager for IIS (PHPManagerForIIS_V1.5.0.msi).
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 5. **Edit the file within the Storage Account (within the Azure Portal):**

   - Download and install the Rewrite Module (rewrite_amd64_en-US.msi).
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 6. **Download the file and observe the changes:**

   - Create a Directory folder named `PHP` in the C drive.
   - Download PHP 7.3.8 (php-7.3.88-nts-Win32-VC15-x866.zip) extract and unzip it into `C:\PHP`.
   - Download and install VC_redist.x86.exe from the installation files.
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 7. **Delete the Resource Group created in step 1 (in order to ensure you don’t incur “cost”):**

   - Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi). For installation accept agreements and set my sql as typical. 
   - Set up MySQL with a root password (e.g., Password1).
   - MySQL server instance configuration wizard installation completion will create a database within the computer so it can storage occupied for osTicket.
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">
<img width="428" alt="step" src="">

## 8. **Verify that the Resource Group has been deleted:**

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



