# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
A) sure your PC meets the minimum system requirements for Windows 11:
1 GHz or faster with 2 or more cores on a compatible 64-bit processor.
4 GB of RAM.
64 GB or larger storage device.
TPM version 2.0.
Secure Boot capable.
DirectX 12 compatible graphics / WDDM 2.x.
Backup Your Data:

Before installing a new operating system, it's important to back up your important files and data.
Steps to Download and Install Windows 11
Visit the Microsoft Windows 11 Download Page:

Go to the Windows 11 download page.
Select the Installation Method:

Windows 11 Installation Assistant: A guided tool to upgrade the current system to Windows 11.
Create Windows 11 Installation Media: A tool to create a bootable USB drive or DVD.
Download Windows 11 Disk Image (ISO): Direct ISO file download for manual installation.
Using the Windows 11 Installation Assistant
Download the Installation Assistant:

Click on the "Download now" button under "Windows 11 Installation Assistant".
Run the Installation Assistant:

Open the downloaded file and follow the on-screen instructions.
Complete the Installation:

The assistant will guide you through the upgrade process. Your PC will restart several times during the installation.
Creating Windows 11 Installation Media
Download the Media Creation Tool:

Click on the "Download now" button under "Create Windows 11 Installation Media".
Run the Media Creation Tool:

Open the downloaded file and follow the instructions to create a bootable USB drive or DVD.
Create Installation Media:

Choose the language, edition, and architecture (64-bit) for Windows 11.
Select USB flash drive (at least 8 GB) or ISO file to burn to a DVD later.
Installing Windows 11 from a Bootable USB Drive
Insert the USB Drive:

Insert the bootable USB drive into the PC where you want to install Windows 11.
Restart Your PC:

Restart the PC and boot from the USB drive. You may need to press a specific key (such as F12, F2, or Del) during startup to access the boot menu.
Start the Installation Process:

Follow the on-screen instructions to install Windows 11. Choose your preferences and partition the drive if necessary.
Complete the Installation:

Windows 11 setup will guide you through the process. Your PC will restart several times.
Set Up Windows 11:

After installation, follow the setup process to configure your settings, create a user account, and customize Windows 11 to your preferences.
Final Steps
Install Updates:

Once Windows 11 is installed, make sure to check for and install any available updates.
Reinstall Applications:

Reinstall your applications and restore your files from backup.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Go to the Visual Studio Code download page.
A) Download the Installer:
Choose the appropriate installer for your operating system. For Windows, click on the "Windows" download button.
Run the Installer:

Open the downloaded file (e.g., VSCodeUserSetup-x64-1.58.2.exe).
Follow the installation prompts:
Accept the license agreement.
Choose the installation location (the default location is usually fine).
Select the additional tasks (optional):
Create a desktop icon: Useful for quick access.
Add to PATH: Highly recommended for using VS Code from the command line.
Register code as an editor for supported file types: Useful for opening files directly in VS Code from File Explorer.
Complete the Installation:

Click "Install" and wait for the installation process to complete.
Once installed, click "Finish" to launch Visual Studio Code.
Initial Setup and Configuration
Launch Visual Studio Code:

Open VS Code using the desktop shortcut or from the Start menu.
Install Recommended Extensions:

Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
Search for and install extensions relevant to your development needs. Some popular ones include:
Prettier - Code Formatter: For consistent code formatting.
ESLint: For identifying and fixing JavaScript and TypeScript code issues.
Python: For Python development.
Live Server: For a quick development server with live reload capability.
GitLens: Enhances Git functionality within VS Code.
Customize Settings:

Go to File > Preferences > Settings or press Ctrl+, to open the Settings.
Adjust settings to suit your workflow, such as auto-save, font size, and themes.
Open a Project Folder:

Go to File > Open Folder and select your project folder to start working on your code.
Set Up Version Control:

If you are using Git, initialize a Git repository in your project folder:
bash
Copy code
git init
Use the Source Control view in VS Code to manage your Git repository.
Optional: Configure Language-Specific Extensions
JavaScript/TypeScript:

ESLint: Helps maintain code quality by identifying and fixing issues.
Prettier: For consistent code formatting.
Debugger for Chrome: Allows debugging JavaScript code in the Chrome browser.
Python:

Python: Provides IntelliSense, linting, debugging, and more.
Pylint: For code analysis.
Jupyter: For working with Jupyter notebooks.
Java:

Java Extension Pack: Includes essential tools for Java development.
Spring Boot Tools: For Spring Boot applications.
C#:

C#: Provides IntelliSense, debugging, and more for C# development.
.NET Core Tools: For working with .NET Core applications.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com Visit the Git download page.
Choose your operating system (Windows, macOS, Linux) and download the installer.
Follow the installation instructions provided by the installer.
Verify Installation:

After installation, open a terminal (Command Prompt, PowerShell on Windows / Terminal on macOS or Linux).
Type the following command to verify that Git is installed and to see the installed version:
bash
Copy code
git --version
This command should display the installed Git version, confirming that Git is installed correctly.
2. Configure Git
Set Up Your Name and Email:

Open a terminal or Git Bash (if using Windows).
Configure your name and email address:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Replace "Your Name" with your actual name and "your.email@example.com" with your email address associated with your GitHub account.
Optional: Configure Other Settings:

You can configure other Git settings such as default text editor and credential caching if needed.
3. Create a GitHub Account
Sign Up for GitHub:

Go to GitHub and sign up for a new account if you don't have one.
Verify Your Email Address:

Follow the instructions in the email sent to you by GitHub to verify your email address.
A) Go to GitHub Website:

Open your web browser and go to GitHub.
Start the Sign-Up Process:

On the GitHub homepage, you will see a form to create an account. Fill in the following details:
Username: Choose a username that will serve as your GitHub handle.
Email address: Provide a valid email address that you have access to.
Password: Create a secure password for your GitHub account.
Complete the CAPTCHA:

Complete any CAPTCHA verification if prompted to prove that you are not a robot.
Click on "Create an account":

After filling in all the required information, click on the green "Create an account" button.
Verify Your Email Address
Check Your Email Inbox:

After signing up, GitHub will send a verification email to the address you provided during sign-up.
Open the Verification Email:

Go to your email inbox associated with the email address you used to sign up for GitHub.
Look for an email from GitHub with the subject "Please verify your email address".
Click on the Verification Link:

Open the email and click on the verification link provided by GitHub.
Alternatively, copy and paste the verification link into your web browser's address bar and press Enter.
Confirm Your Email Address:

Once you click on the verification link, your email address will be verified, and you will be redirected to GitHub's website.
Set Up Your GitHub Profile (Optional):

After verifying your email address, you may want to set up your GitHub profile. This includes adding a profile picture, bio, and any other relevant information.

Initialize a Git Repository
Navigate to Your Project Directory:

Open a terminal or Git Bash.
Navigate (cd) to your project directory where you want to initialize the Git repository.
Initialize Git:

Use the following command to initialize a new Git repository:
This command initializes a new Git repository in the current directory.
Make Your First Commit
Add Files to Staging Area:

Start by creating or adding files to your project directory.
Use git add to add files to the staging area. For example, to add all files, use:
git add .
Replace . with specific file names or directories as needed.
Commit Your Changes:

Once files are added to the staging area, commit them with a commit message:
git commit -m "Initial commit"
Replace "Initial commit" with a meaningful commit message describing the changes made in this commit.
Create a Repository on GitHub
Create a New Repository:

Log in to your GitHub account.
Click on the "+" icon in the top right corner and select "New repository".
Enter a repository name, optionally add a description, choose visibility (public or private), and initialize with a README file if desired.
Click on "Create repository".
Connect Your Local Repository to GitHub:

Follow the instructions provided on GitHub under "…or push an existing repository from the command line".
For example, if you haven't added a remote repository yet, use:
git remote add origin https://github.com/your-username/repository-name.git
Replace your-username with your GitHub username and repository-name with the name of your repository.
Push Your Changes to GitHub:

Finally, push your committed changes to GitHub:
git push -u origin main
Replace main with master if you are using the master branch as the default branch.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  A) Download Python Installer:

Go to the Python official website.
Click on the "Downloads" tab in the top navigation menu.
Choose the Python Version:

Select the appropriate Python version for your project. Typically, choose the latest stable version unless your project specifically requires an older version.
Click on the download link to get the installer for your operating system (Windows, macOS, or Linux).
Run the Python Installer:

Once the installer is downloaded, run it to start the installation process.
For Windows:
Double-click the downloaded .exe file.
Check the box that says "Add Python X.X to PATH" before clicking "Install Now". This option ensures Python is added to your system PATH, allowing you to run Python from the command line.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   A) Check Python Installation:

Ensure Python is installed on your system. You can verify this by opening a terminal (Command Prompt, PowerShell on Windows / Terminal on macOS or Linux) and typing:
bash
Copy code
python --version
If Python is installed, this command will display the installed Python version. If not installed, refer to earlier instructions on how to install Python.
Install pip (if not already installed):

Recent versions of Python (Python 3.4 and later) come with pip pre-installed. To check if pip is installed, run:
pip --version
If pip is not installed or if you need to upgrade it, you can install or upgrade pip using the following command:
python -m ensurepip --upgrade
Installing Other Package Managers
npm (Node Package Manager):

npm comes with Node.js. You can download and install Node.js from the official Node.js website. npm will be installed automatically alongside Node.js.
Composer (PHP Package Manager):

To install Composer for PHP, follow the instructions on the Composer official website.
apt-get (Ubuntu/Debian Package Manager):

apt-get is a package manager for Debian-based Linux distributions. It is used to install software packages. To install packages using apt-get, use:
sudo apt-get install package-name
Replace package-name with the name of the package you want to install.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html Visit the MySQL Community Downloads page.
Click on the "Download" button for the MySQL Installer for Windows.
Run the MySQL Installer:

Once the installer is downloaded, run it by double-clicking on the downloaded .msi file.
MySQL Installer Setup:

The MySQL Installer will guide you through the installation process. Follow these steps:
Choose "Developer Default" or "Server only" installation type. "Developer Default" includes MySQL Server, MySQL Workbench, and other tools commonly used for development.
Click "Next" to proceed with the installation.
MySQL Product Selection:

Select the MySQL products you want to install. Typically, this includes MySQL Server and MySQL Workbench for managing the database visually.
Click "Next" to continue.
Installation Process:

Proceed with the default settings unless you have specific requirements.
The installer will download and install MySQL Server and other selected components.
Configure MySQL Server:

During the installation, you will be prompted to configure MySQL Server.
Set up the root password for MySQL Server. Choose a strong password and remember it for future use.
Configure other options as needed.
Complete the Installation:

Once the installation is complete, click on "Finish" to exit the MySQL Installer.
Verify MySQL Installation
Start MySQL Server:

MySQL Server should start automatically after installation. If not, you can start it from the Start menu.
Access MySQL Workbench:

Open MySQL Workbench from the Start menu or desktop shortcut (if selected during installation).
Connect to MySQL Server:

In MySQL Workbench, click on the "+" icon next to "MySQL Connections" to create a new connection.
Enter the connection details:
Connection Name: Enter a name for the connection.
Connection Method: Standard (TCP/IP).
Hostname: localhost (if MySQL Server is installed on the same machine).
Port: 3306 (default MySQL port).
Username: root (default MySQL root user).
Password: Enter the password you set during installation.
Click "Test Connection" to ensure MySQL Workbench can connect to the server.
Create a New Database (Optional)
Create a New Schema (Database):
Once connected to MySQL Server in MySQL Workbench, you can create a new schema (database) by right-clicking on the "SCHEMAS" section and selecting "Create Schema".
Enter a name for the new schema and configure any additional options as needed.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
 A) Install Docker Desktop:

Go to the Docker Desktop download page.
Download and install Docker Desktop for your operating system (Windows or macOS).
Follow the installation instructions provided by Docker.
Start Docker Desktop:

Once installed, start Docker Desktop from the Start menu or desktop shortcut.
Verify Docker Installation:

Open a terminal (Command Prompt, PowerShell on Windows / Terminal on macOS).
Run the following command to verify Docker installation:
bash
Copy code
docker --version
This command should display the installed Docker version.
Create and Manage Containers:

Use Docker to create containers for your applications or services. Containers are lightweight, portable, and isolated environments that package your application with its dependencies.
Virtual Machines (e.g., VirtualBox, VMware)
Install Virtualization Software:

Download and install virtualization software such as VirtualBox (VirtualBox download page) or VMware (VMware download page).
Follow the installation instructions provided by the virtualization software.
Create a Virtual Machine (VM):

Use the virtualization software to create a new virtual machine.
Allocate resources (CPU, memory, disk space) based on your project requirements.
Install an operating system (e.g., Ubuntu, Windows) on the virtual machine if necessary.
Configure Networking and Shared Folders:

Set up networking options to ensure communication between your host machine and virtual machine.
Configure shared folders to easily transfer files between the host and the virtual machine.
Benefits of Using Virtualization Tools
Isolation: Keep project dependencies isolated from your host system, preventing conflicts and ensuring consistency.

Portability: Easily share development environments with team members or deploy them across different machines.

Testing: Test applications in different environments (e.g., different operating systems) without affecting your main development setup.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   A) Open Visual Studio Code:

Launch Visual Studio Code on your computer.
Navigate to Extensions Marketplace:

Click on the Extensions icon in the Activity Bar on the side of the VS Code window (or press Ctrl+Shift+X).
Alternatively, you can use the shortcut Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (macOS) to open the Command Palette, and type Extensions: Install Extensions.
Search and Explore Extensions:

In the Extensions view, you can search for extensions by name or functionality. For example, search for "Python" for Python-related extensions, or "GitLens" for enhanced Git integration.
Browse through the results to find extensions that suit your needs.
Install Extensions:

Click on the extension you want to install.
Click on the "Install" button to install the extension.
Some popular extensions to consider:
Python: Adds support for Python development including linting, debugging, and IntelliSense.
GitLens: Enhances Git integration with features like blame annotations, commit details, and more.
Prettier: Provides code formatting capabilities for various languages.
ESLint or TSLint: Provides linting for JavaScript/TypeScript projects.
Live Server: Launches a local development server with live reload feature for web development.
Manage Installed Extensions:

After installing extensions, they will appear in the Extensions view.
You can disable, uninstall, or update extensions as needed.
VS Code will notify you of updates to installed extensions in the bottom-right corner.
Benefits of Using Extensions
Enhanced Functionality: Extensions add features tailored to specific languages, frameworks, or workflows.

Productivity Boost: Tools like code formatting, linting, and debugging streamline development tasks.

Integration: Extensions can integrate with external tools and services, enhancing collaboration and workflow efficiency.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    A) Table of Contents
1. Install Operating System and Updates
2. Install Text Editor or IDE
3. Set Up Version Control System
4.  Install Programming Languages and Runtimes
5. Configure Package Managers
6. Set Up Database
7. Explore and Install Extensions
8. Optional: Use Virtualization Tools
1. Install Operating System and Updates
Purpose: Ensure your operating system is up-to-date with the latest security patches and features.

Steps:

Install Windows 11 or your preferred operating system.
Apply system updates to ensure stability and security.
2. Install Text Editor or IDE
Purpose: Choose a text editor or integrated development environment (IDE) that suits your programming languages and workflow.

Steps:

Download and install Visual Studio Code from Visual Studio Code website.
Customize settings and preferences as needed.
Explore and install extensions for syntax highlighting, linting, and version control integration.
3. Set Up Version Control System
Purpose: Manage and track changes to your codebase efficiently.

Steps:

Install Git from Git official website.
Configure Git settings (username, email) using Git Bash or command line.
Create a GitHub account and set up SSH keys for secure access.
4. Install Programming Languages and Runtimes
Purpose: Install languages and runtimes necessary for your projects.

Example: Install Python:

Download Python installer from Python official website.
Run the installer and ensure Python is added to PATH.
Verify installation and update pip package manager.
5. Configure Package Managers
Purpose: Manage dependencies and libraries for your projects.

Example: Configure pip for Python:

Install pip if not included with Python installation.
Upgrade pip to the latest version using python -m pip install --upgrade pip.
Install necessary Python packages using pip install package-name.
6. Set Up Database
Purpose: Install and configure databases for storing application data.

Example: Install MySQL:

Download MySQL Installer from MySQL official website.
Run the installer, configure MySQL Server with root password.
Verify installation by connecting with MySQL Workbench and creating a new database.
7. Explore and Install Extensions
Purpose: Enhance functionality of your text editor or IDE with extensions.

Example: Install VS Code Extensions:

Open VS Code, navigate to Extensions Marketplace.
Search and install extensions like Python, GitLens, and Prettier for enhanced development experience.
Customize settings for each extension to match your workflow.
8. Optional: Use Virtualization Tools
Purpose: Isolate project dependencies and ensure consistent environments.

Example: Use Docker:

Install Docker Desktop from Docker official website.
Verify installation and run Docker containers for development and testing.
Create Dockerfiles and Docker Compose configurations for complex environments.
Conclusion
Setting up a developer environment involves installing essential tools, configuring settings, and customizing preferences to suit your project requirements. Regularly update tools and extensions to benefit from new features and security patches. Troubleshoot issues encountered during installation or configuration by consulting official documentation or community forums.

By following these steps, you'll have a robust developer environment ready for efficient software development, collaboration, and project management.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
