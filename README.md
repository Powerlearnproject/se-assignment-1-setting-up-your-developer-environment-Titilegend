[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15276465&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment


#Tasks:


### Download and Install Windows 11 Using a Flash Drive
#### Requirements
A USB flash drive with at least 8GB of storage.
A computer with an internet connection.
Step-by-Step Guide
1. Download Windows 11 Installation Media
Visit the Windows 11 Download Page:

Go to Windows 11 Download.
Download the Media Creation Tool:

Under the "Create Windows 11 Installation Media" section, click on the "Download now" button.
Run the Media Creation Tool:

Locate the downloaded file (MediaCreationToolW11.exe) and double-click it to run the tool.
You may be prompted by User Account Control; click "Yes" to allow the tool to make changes to your device.
Accept the License Terms:

Read and accept the Microsoft license terms to proceed.
2. Create Installation Media
- Choose Your Installation Media:

- Select "Create installation media (USB flash drive, DVD, or ISO file) for another PC" and click "Next".
Select Language, Edition, and Architecture:

- Use the recommended options for your PC or customize the language, edition, and architecture (32-bit or 64-bit) as needed. Click "Next".

- Choose USB Flash Drive:

Select "USB flash drive" and click "Next".
Select Your USB Flash Drive:

- Ensure your USB flash drive is connected to your computer. Select the drive from the list and click "Next".
Download Windows 11 and Create Installation Media:

The tool will now download Windows 11 and create the installation media on your USB flash drive. This process may take some time depending on your internet connection speed.
Finish:

- Once the process is complete, click "Finish" and safely remove your USB flash drive from the computer.
#### b. Install Windows 11
Insert the USB Flash Drive:

- Insert the USB flash drive into the computer where you want to install Windows 11.


- Restart your computer and enter the BIOS or UEFI settings (commonly done by pressing a key such as F2, F12, Delete, or Esc during startup; refer to your computer's manual for specific instructions).


-- In the BIOS or UEFI settings, change the boot order to prioritize the USB flash drive. Save the changes and exit.
- Windows 11 Setup:

Your computer will boot from the USB flash drive and start the Windows 11 setup process.
Follow the on-screen instructions to choose your language, time, and keyboard preferences. Click "Next".

- Click "Install now".
- Activate Windows:
Enter your Windows 11 product key if prompted, or click "I don't have a product key" if you want to enter it later. Click "Next".
Accept License Terms:

- Read and accept the license terms. Click "Next".
- Choose Installation Type:

Select "Custom: Install Windows only (advanced)".
Select the Drive to Install Windows:

Choose the partition where you want to install Windows 11. If you have a clean drive, select it and click "Next". If necessary, delete existing partitions (note that this will erase all data on those partitions).
Installation Process:

Windows 11 will now begin installing. Your computer may restart several times during this process.
Initial Setup:

After installation, follow the on-screen instructions to set up your Windows 11 preferences, create a user account, and configure settings.
Complete Setup:

Once the setup is complete, you will be taken to the Windows 11 desktop.



### How to Download Visual Studio Code
1. Visit the Visual Studio Code Download Page:https://code.visualstudio.com/Download

Open your web browser and go to the Visual Studio Code Download page.
Select the Windows Download:

Click on the download link for Windows. This will download the Visual Studio Code installer (VSCodeUserSetup-x64-<version>.exe) to your computer.

2. Install Visual Studio Code
Run the Installer:

Locate the downloaded installer file (VSCodeUserSetup-x64-<version>.exe) in your Downloads folder or the location where you saved it.
- Double-click the installer file to start the installation process.
- Read the license agreement, and if you agree to the terms, select "I accept the agreement" and click "Next".
- Choose the destination folder where you want Visual Studio Code to be installed. The default location is usually fine. Click "Next".

Choose any additional tasks you want the installer to perform. It's recommended to check the following options:
"Create a desktop icon" (for easy access to VS Code).
"Add to PATH" (useful for command-line operations).
"Register Code as an editor for supported file types" (allows you to open files with VS Code directly from the file explorer).
Click "Next".
3. Ready to Install:

Review your installation settings. If everything looks good, click "Install" to start the installation.


Once the installation is complete, you will see a completion screen. You can choose to launch Visual Studio Code immediately by checking the "Launch Visual Studio Code" box.
Click "Finish" to close the installer.



### Set Up Version Control System
Install Git
- Visit the Git Download Page: https://www.git-scm.com/downloads

- Click on the Windows download link.


- Run the downloaded installer and follow the default options unless you have specific preferences.
- Configure Git
Open Command Prompt or PowerShell:

Press Win + R, type cmd or powershell, and press Enter.
Configure Your Git Username and Email:


git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"



b. Create a GitHub Account
- Visit the GitHub Signup Page:

- Follow the instructions to create a new GitHub account.
- Initialize a Git Repository
- Create a New Directory for Your Project:


mkdir my_project
cd my_project
- Initialize a Git Repository:

git init
 - Create a Sample File and Make Your First Commit:

echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"



### Install Python
 - Visit the Python Download Page:
https://www.python.org/downloads/

- Download the Latest Version of Python:

- Click on the download link for the latest version of Python for Windows.


- Run the downloaded installer.
- Ensure "Add Python to PATH" is checked.
- Follow the on-screen instructions to complete the installation.



  ### Install Package Managers:
  - Open Command Prompt or PowerShell:

  - Press Win + R, type cmd or powershell, and press Enter.
  - Verify pip Installation:

  pip --version



### Configure a Database (MySQL):
 - Visit the MySQL Download Page: https://dev.mysql.com/downloads/windows/installer/5.7.html

 -  Click on the download link for the MySQL Installer.

 -  Run the downloaded installer.
 -  Choose "Custom" installation.
 -  Select "MySQL Server" and "MySQL Workbench".
 -  Follow the on-screen instructions to complete the installation.

 ### Explore Extensions and Plugins:

   -  Open Visual Studio Code:

   -  Double-click the VS Code icon on your desktop or find it in your start menu.
   -  Go to the Extensions View,Click the Extensions icon in the Activity Bar on the side of the window.
   Search for and install the following extensions:
   - Python (for Python development)
   - GitLens (for Git integration)
   - Prettier (for code formatting)
   - ESLint (for linting)

Github repo ; https://github.com/Titilegend/user_input



### Reflection on Challenges
During the setup process, I encountered a few challenges:

- Git Configuration: Initially, I had issues with Git recognizing my username and email. I resolved this by double-checking the configuration commands and ensuring there were no typos.
- Python PATH: After installing Python, some scripts did not recognize the Python command. This was resolved by ensuring "Add Python to PATH" was checked during installation and restarting the terminal.
- MySQL Installation: There were issues with the MySQL server not starting. I resolved this by reconfiguring the server using the MySQL Installer and ensuring the correct port was set.


