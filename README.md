[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279095&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11



Step 1: Check System Requirements
Ensure your PC meets the minimum system requirements for Windows 11:

Processor: 1 gigahertz (GHz) or faster with at least 2 cores on a compatible 64-bit processor or System on a Chip (SoC)
RAM: 4 GB or more
Storage: 64 GB or larger storage device
System firmware: UEFI, Secure Boot capable
TPM: Trusted Platform Module (TPM) version 2.0
Graphics card: DirectX 12 compatible graphics / WDDM 2.x
Display: >9” with HD Resolution (720p)
You can check if your device meets the requirements by running the PC Health Check app.

Step 2: Download Windows 11
Visit the official Microsoft download page for Windows 11.
Scroll down to the "Download Windows 11 Disk Image (ISO)" section.
Select "Windows 11" from the dropdown menu and click "Download".
Choose your product language and click "Confirm".
Click on the 64-bit Download button to start the download.
Step 3: Create a Bootable USB Drive
To create a bootable USB drive, you will need:

A USB flash drive with at least 8 GB of space.
Rufus, a free tool to create bootable USB drives.
Download and install Rufus.
Insert your USB flash drive into your PC.
Open Rufus and select the USB drive.
In the Boot selection dropdown, choose "Disk or ISO image (Please select)".
Click the "SELECT" button and choose the Windows 11 ISO file you downloaded.
Under "Partition scheme", select "GPT" if your system uses UEFI, or "MBR" for legacy BIOS systems.
Click "START" to create the bootable USB drive.
Step 4: Install Windows 11
Insert the bootable USB drive into the PC where you want to install Windows 11.
Restart the PC and enter the BIOS/UEFI settings (usually by pressing F2, F12, Delete, or Esc during startup).
Set the USB drive as the primary boot device.
Save the changes and exit the BIOS/UEFI settings.
The PC should boot from the USB drive and start the Windows 11 installation process.
Follow the on-screen instructions to complete the installation of Windows 11.
Make sure to back up any important data before starting the installation process, as it may erase all data on the target drive.
 
2.Install a Text Editor or Integrated Development Environment (IDE):
Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   
To download and install Visual Studio Code, follow these steps:

Step 1: Download Visual Studio Code
Visit the Visual Studio Code download page.
Choose the version of Visual Studio Code that matches your operating system (Windows, macOS, or Linux).
For Windows, click on the "Windows" button to download the installer.
For macOS, click on the "macOS" button to download the installer.
For Linux, select the appropriate package for your distribution.
Step 2: Install Visual Studio Code on Windows
Run the downloaded installer (VSCodeSetup-x64-x.x.x.exe).
Follow the prompts in the installation wizard:
Accept the license agreement.
Choose the destination folder for the installation.
Select additional tasks (e.g., creating a desktop icon, adding "Open with Code" to the context menu).
Click "Install" to begin the installation.
Once the installation is complete, click "Finish" to launch Visual Studio Code.
Step 3: Install Visual Studio Code on macOS
Open the downloaded VSCode-darwin-stable.zip file.
Drag the Visual Studio Code application to the Applications folder.
Open Visual Studio Code from the Applications folder.
Step 4: Install Visual Studio Code on Linux
For Debian and Ubuntu-based distributions:

Download the .deb package from the Visual Studio Code download page.
Open a terminal and navigate to the directory where the .deb package is located.
Run the following command to install Visual Studio Code:
bash
Copy code
sudo apt install ./<file>.deb
For Red Hat, Fedora, and CentOS-based distributions:

Download the .rpm package from the Visual Studio Code download page.
Open a terminal and navigate to the directory where the .rpm package is located.
Run the following command to install Visual Studio Code:
bash
Copy code
sudo rpm -i <file>.rpm
For other distributions, refer to the official Linux installation documentation.

Step 5: Customize Visual Studio Code
Launch Visual Studio Code.
Install extensions for your preferred programming languages and workflows:
Click on the Extensions icon in the Activity Bar on the side of the window.
Search for extensions such as "Python", "JavaScript", "C++", etc., and cTo set up a version control system using Git and GitHub, follow these steps:

3.Set Up Version Control System:
 Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first 
 commit. https://github.com

Step 1: Install Git
Windows
Download Git for Windows from the official Git website.
Run the downloaded installer (Git-x.x.x-x64.exe).
Follow the prompts in the installation wizard. You can use the default settings for most options, but make sure to select the following:
"Use Git from the Windows Command Prompt" or "Git Bash Here" context menu option.
"Use the OpenSSH" for the SSH executable.
"Checkout Windows-style, commit Unix-style line endings".
macOS
Install Git using Homebrew. Open a terminal and run:
bash
Copy code
brew install git
Linux
For Debian and Ubuntu-based distributions, open a terminal and run:
bash
Copy code
sudo apt update
sudo apt install git
For Red Hat, Fedora, and CentOS-based distributions, run:
bash
Copy code
sudo dnf install git
Step 2: Configure Git
Open a terminal or Git Bash.
Set your username:
bash
Copy code
git config --global user.name "Your Name"
Set your email:
bash
Copy code
git config --global user.email "your.email@example.com"
Step 3: Create a GitHub Account
Go to GitHub.
Click on "Sign up" and follow the prompts to create a new account.
Step 4: Initialize a Git Repository
Create a new directory for your project or navigate to your existing project directory:
bash
Copy code
mkdir my-project
cd my-project
Initialize a new Git repository:
bash
Copy code
git init
Step 5: Make Your First Commit
Create a new file, for example README.md:
bash
Copy code
echo "# My Project" > README.md
Add the file to the staging area:
bash
Copy code
git add README.md
Commit the changes:
bash
Copy code
git commit -m "Initial commit"
Step 6: Push Your Repository to GitHub
Create a new repository on GitHub:

Go to your GitHub profile and click on the "Repositories" tab.
Click on the "New" button.
Enter a repository name, description (optional), and choose whether to make it public or private.
Click on "Create repository".
Connect your local repository to the GitHub repository:

bash
Copy code
git remote add origin https://github.com/your-username/your-repository.git
Push your local commits to GitHub:

bash
Copy code
git push -u origin master
Step 7: Verify Your Repository on GitHub
Go to your GitHub repository page.
You should see your README.md file and the initial commit.
Now you have Git installed, a GitHub account set up, and your first project committed and pushed to GitHub.
Configure your settings:
Open the settings by clicking on the gear icon in the bottom left corner and selecting "Settings".
Customize the settings according to your preferences.
Now you have Visual Studio Code installed and ready to use for your development projects.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Step 1: Download and Install Python
Visit the official Python website: python.org.
Click on the "Download Python 3.x.x" button. This will download the latest version of Python.
Windows
Run the downloaded installer (python-3.x.x.exe).
Make sure to check the box that says "Add Python to PATH".
Click "Install Now" and follow the prompts to complete the installation.
macOS
Open the downloaded .pkg file.
Follow the prompts in the installer to complete the installation.
Linux
For Debian and Ubuntu-based distributions:

Open a terminal and run:
bash
Copy code
sudo apt update
sudo apt install python3 python3-pip
For Red Hat, Fedora, and CentOS-based distributions:

Open a terminal and run:
bash
Copy code
sudo dnf install python3 python3-pip
Step 2: Verify the Installation
Open a terminal or command prompt.

Verify the Python installation by checking the version:

bash
Copy code
python --version
or

bash
Copy code
python3 --version
Verify that pip (Python's package installer) is installed:

bash
Copy code
pip --version
or

bash
Copy code
pip3 --version
Step 3: Install Necessary Packages and Tools
Install common packages using pip. For example:

bash
Copy code
pip install numpy pandas matplotlib
If your project has specific dependencies, you can install them by creating a requirements.txt file in your project directory with the required packages listed, and then run:

bash
Copy code
pip install -r requirements.txt
Step 4: Set Up a Virtual Environment (Optional but Recommended)
Using a virtual environment helps manage dependencies for different projects.

Create a virtual environment:

bash
Copy code
python -m venv myenv
or

bash
Copy code
python3 -m venv myenv
Activate the virtual environment:

On Windows:

bash
Copy code
myenv\Scripts\activate
On macOS and Linux:

bash
Copy code
source myenv/bin/activate
Install packages within the virtual environment as needed:

bash
Copy code
pip install <package-name>
Step 5: Install IDE or Text Editor Extensions for Python
If you are using Visual Studio Code, install the Python extension:
Open Visual Studio Code.
Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
Search for "Python" and install the extension by Microsoft.
Now you have Python installed along with its package manager and a virtual environment set up, which provides a robust setup for developing your project.

5.Install Package Managers:
 To install Python and set up the necessary tools to build and execute your code, follow these steps:

Step 1: Install Python
Download Python:
Visit the official Python website: python.org.
Click on the "Download Python 3.x.x" button. This will download the latest version of Python.
Windows
Run the downloaded installer (python-3.x.x.exe).
Make sure to check the box that says "Add Python to PATH".
Click "Install Now" and follow the prompts to complete the installation.
macOS
Open the downloaded .pkg file.
Follow the prompts in the installer to complete the installation.
Linux
For Debian and Ubuntu-based distributions:

Open a terminal and run:
bash
Copy code
sudo apt update
sudo apt install python3 python3-pip
For Red Hat, Fedora, and CentOS-based distributions:

Open a terminal and run:
bash
Copy code
sudo dnf install python3 python3-pip
Step 2: Verify the Installation
Open a terminal or command prompt.

Verify the Python installation by checking the version:

bash
Copy code
python --version
or

bash
Copy code
python3 --version
Verify that pip (Python's package installer) is installed:

bash
Copy code
pip --version
or

bash
Copy code
pip3 --version
Step 3: Install Necessary Packages and Tools
Install common packages using pip. For example:

bash
Copy code
pip install numpy pandas matplotlib
If your project has specific dependencies, you can install them by creating a requirements.txt file in your project directory with the required packages listed, and then run:

bash
Copy code
pip install -r requirements.txt
Step 4: Set Up a Virtual Environment (Optional but Recommended)
Using a virtual environment helps manage dependencies for different projects.

Create a virtual environment:

bash
Copy code
python -m venv myenv
or

bash
Copy code
python3 -m venv myenv
Activate the virtual environment:

On Windows:
bash
Copy code
myenv\Scripts\activate
On macOS and Linux:
bash
Copy code
source myenv/bin/activate
Install packages within the virtual environment as needed:

bash
Copy code
pip install <package-name>
Step 5: Install Package Managers for Other Languages (Optional)
If you are using other programming languages, you may need additional package managers:

Node.js and npm (JavaScript)
Download and install Node.js from nodejs.org.
Verify the installation by running:
bash
Copy code
node --version
npm --version
Ruby and Bundler
Install Ruby from ruby-lang.org.
Install Bundler:
bash
Copy code
gem install bundler
Java and Maven/Gradle
Install Java from oracle.com.
Install Maven from maven.apache.org or Gradle from gradle.org.
Step 6: Install IDE or Text Editor Extensions for Python
If you are using Visual Studio Code, install the Python extension:
Open Visual Studio Code.
Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
Search for "Python" and install the extension by Microsoft.
Now you have Python installed along with its package manager and a virtual environment set up, which provides a robust setup for developing your project. Additionally, you've installed other package managers for various programming languages as needed.

6.Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   
To download, install, and configure MySQL on your system, follow these steps:

Step 1: Download MySQL
Visit the MySQL Community Downloads page for Windows: MySQL Installer 5.7.
Click on the "Download" button for the MySQL Installer (choose either the web or the full version).
Step 2: Install MySQL
Run the Installer:

Open the downloaded installer file (mysql-installer-community-5.7.x.x.msi).
Choose Setup Type:

In the Setup Type window, choose "Developer Default" or "Full" if you want all components installed, or "Custom" if you want to select specific components.
Check Requirements:

The installer will check for any missing requirements. If any are missing, you can install them via the installer or manually.
Install MySQL:

Click "Execute" to download and install the selected components. This might take some time.
Step 3: Configure MySQL
Configuration Overview:

After installation, the MySQL Installer will guide you through configuration steps. Click "Next".
Type and Networking:

Select the "Standalone MySQL Server" option.
Choose the appropriate configuration type. For most users, "Development Machine" is suitable.
Ensure the "TCP/IP" option is checked, and the default port is set to 3306.
Authentication Method:

Choose the legacy authentication method if you need compatibility with older MySQL clients and libraries.
Accounts and Roles:

Set a root password.
Optionally, create additional user accounts.
Windows Service:

Choose to run MySQL as a Windows Service.
You can opt to start the MySQL server at system startup.
Apply Configuration:

Review your configuration settings and click "Execute" to apply the configuration.
Step 4: Verify Installation
Open MySQL Workbench:

If you installed MySQL Workbench, you can use it to manage your databases.
Open MySQL Workbench and create a new connection to the local MySQL server using the root account and the password you set.
Command Line Client:

Alternatively, you can use the MySQL Command Line Client to interact with the server.
Open the MySQL Command Line Client and log in with the root account:
bash
Copy code
mysql -u root -p
Step 5: Create a Database
Log in to MySQL:

bash
Copy code
mysql -u root -p
Create a New Database:

sql
Copy code
CREATE DATABASE mydatabase;
Use the New Database:

sql
Copy code
USE mydatabase;
Create a Table:

sql
Copy code
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL,
    email VARCHAR(100) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
Insert Data into the Table:

sql
Copy code
INSERT INTO users (username, email) VALUES ('john_doe', 'john@example.com');
Query the Table:

sql
Copy code
SELECT * FROM users;
Now, you have MySQL installed, configured, and running on your system. You also have created a database and a table, and performed basic SQL operations to verify the installation.


7.Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Setting up development environments and virtualization using tools like Docker or virtual machines can greatly enhance the consistency and portability of your projects. Here’s a step-by-step guide on how to get started with Docker:

Step 1: Install Docker
Windows and macOS
Download Docker Desktop from the Docker website.

Install Docker Desktop:

Run the downloaded installer and follow the prompts to complete the installation.
During the installation, ensure that the option to install the Docker CLI is checked.
Start Docker Desktop:

After installation, launch Docker Desktop. It may require you to log in or create a Docker account.
Linux
Install Docker Engine:

Open a terminal and run the following commands:
bash
Copy code
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io
Add your user to the Docker group:

bash
Copy code
sudo usermod -aG docker $USER
Enable and start Docker:

bash
Copy code
sudo systemctl enable docker
sudo systemctl start docker
Step 2: Verify Docker Installation
Open a terminal or command prompt.

Run the following command to verify the installation:

bash
Copy code
docker --version
Run a test container:

bash
Copy code
docker run hello-world
Step 3: Create a Dockerfile
Create a new directory for your project:

bash
Copy code
mkdir my-docker-project
cd my-docker-project
Create a Dockerfile in your project directory:

dockerfile
Copy code
# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
Step 4: Build and Run Your Docker Container
Build the Docker image:

bash
Copy code
docker build -t my-python-app .
Run the Docker container:

bash
Copy code
docker run -p 4000:80 my-python-app
Step 5: Using Docker Compose (Optional)
For more complex applications, you can use Docker Compose to define and run multi-container Docker applications.

Create a docker-compose.yml file in your project directory:

yaml
Copy code
version: '3'
services:
  web:
    build: .
    ports:
      - "4000:80"
    volumes:
      - .:/app
    environment:
      - NAME=World
Run Docker Compose:

bash
Copy code
docker-compose up
Step 6: Set Up Virtual Machines (Optional)
If you prefer using virtual machines, you can use tools like VirtualBox or VMware. Here’s how to set up a VM using VirtualBox:

Download and Install VirtualBox from the VirtualBox website.
Download and Install Vagrant from the Vagrant website.
Create a Vagrantfile
Create a new directory for your Vagrant project:

bash
Copy code
mkdir my-vagrant-project
cd my-vagrant-project
Initialize a new Vagrantfile:

bash
Copy code
vagrant init hashicorp/bionic64
Edit the Vagrantfile to configure your VM. For example:

ruby
Copy code
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.synced_folder ".", "/vagrant"
  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
    apt-get install -y apache2
  SHELL
end
Start and provision the VM:

bash
Copy code
vagrant up
SSH into the VM:

bash
Copy code
vagrant ssh
By setting up Docker or Vagrant, you can ensure consistent development environments across different machines, which can significantly streamline your development workflow

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

To enhance the functionality of your text editor or Integrated Development Environment (IDE), you can explore and install various extensions and plugins. Here’s a guide on how to do this using Visual Studio Code (VS Code) as an example, but similar steps apply to other editors and IDEs as well.

Step 1: Open the Extensions View
Open Visual Studio Code:
Launch VS Code on your machine.
Open Extensions View:
Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS).
Step 2: Search for Extensions
Search for Extensions:
Use the search bar at the top of the Extensions view to find extensions related to your needs. You can search for keywords like "Python", "JavaScript", "linting", "Git", etc.
Step 3: Install Recommended Extensions
Here are some recommended extensions to enhance your development experience:

Language Support
Python:
Python by Microsoft
JavaScript/TypeScript:
ESLint for linting JavaScript and TypeScript
HTML/CSS:
HTML CSS Support
C++:
C/C++ by Microsoft
Code Formatting
Prettier - Code Formatter:
Prettier
Version Control
Git Integration:
GitLens — Supercharge the built-in Git capabilities
GitHub Pull Requests and Issues by GitHub
Development Tools
Docker:
Docker for managing Docker containers
Live Server:
Live Server for launching a local development server with live reload feature
Productivity Enhancements
Bracket Pair Colorizer:
Bracket Pair Colorizer for matching brackets with colors
Path Intellisense:
Path Intellisense for autocompleting file paths
Step 4: Configure and Use Extensions
Install Extensions:

Click the "Install" button on the extension you want to add. Once installed, some extensions might require additional configuration or dependencies to be installed.
Configure Extensions:

After installing, you can often configure extensions by clicking on the gear icon next to the "Uninstall" button and selecting "Extension Settings". This allows you to customize the behavior of the extension according to your needs.
Use Extensions:

Utilize the installed extensions in your workflow. For example, if you installed Prettier, you can format your code by right-clicking and selecting "Format Document" or by using the keyboard shortcut Shift+Alt+F (Windows/Linux) or Shift+Option+F (macOS).
Step 5: Keep Extensions Updated
Update Extensions:
Regularly check for updates to your installed extensions. You can do this by clicking on the Extensions icon and looking for an "Update" button next to any extensions that have new versions available.
Additional Tips
Explore New Extensions: Frequently visit the Visual Studio Code Marketplace to discover new extensions that can improve your workflow.
Read Reviews and Documentation: Before installing an extension, read user reviews and check the documentation to ensure it meets your requirements.
Experiment: Don’t hesitate to try different extensions to see which ones work best for you and your specific development needs.
By exploring and installing the right extensions and plugins, you can significantly enhance the functionality of your text editor or IDE, streamline your development process, and improve your overall productivity


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

Here's a comprehensive document outlining the steps taken to set up your developer environment, including configurations, customizations, and troubleshooting steps encountered during the process.

Developer Environment Setup Guide
Overview
This guide outlines the steps taken to set up a complete developer environment including operating system installation, text editor/IDE configuration, version control setup, programming language installation, database configuration, and the use of development environments and virtualization tools.

1. Operating System Installation
Windows 11 Installation
Download Windows 11:
Visit the official Microsoft website: Windows 11 Download.
Download the Windows 11 installation media.
Install Windows 11:
Follow the on-screen instructions to install Windows 11 on your machine.
2. Install a Text Editor or Integrated Development Environment (IDE)
Visual Studio Code Installation
Download Visual Studio Code:
Visit the official VS Code download page: VS Code Download.
Install Visual Studio Code:
Run the downloaded installer and follow the prompts to complete the installation.
3. Set Up Version Control System
Git and GitHub Configuration
Install Git:

Windows: Download from Git for Windows and run the installer.
macOS: Install via Homebrew:
bash
Copy code
brew install git
Linux: Install via package manager:
bash
Copy code
sudo apt update
sudo apt install git
Configure Git:

bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub Account:

Sign up at GitHub.
Initialize a Git Repository:

bash
Copy code
mkdir my-project
cd my-project
git init
Make Your First Commit:

bash
Copy code
echo "# My Project" > README.md
git add README.md
git commit -m "Initial commit"
Push to GitHub:

bash
Copy code
git remote add origin https://github.com/your-username/your-repository.git
git push -u origin master
4. Install Necessary Programming Languages and Runtimes
Python Installation
Download Python:
Visit the official Python website: Python Download.
Install Python:
Windows: Run the installer and ensure "Add Python to PATH" is checked.
macOS/Linux: Use the package manager:
bash
Copy code
sudo apt update
sudo apt install python3 python3-pip
Verify Installation:
bash
Copy code
python --version
pip --version
5. Install Package Managers
pip (Python Package Manager)
Install Common Packages:
bash
Copy code
pip install numpy pandas matplotlib
Create a requirements.txt file with necessary dependencies:
bash
Copy code
pip install -r requirements.txt
6. Configure a Database (MySQL)
MySQL Installation and Configuration
Download MySQL:
Visit the MySQL Community Downloads.
Install MySQL:
Run the installer and follow the prompts to install MySQL.
Configure MySQL:
Set up a root password and configure the server.
Verify Installation:
bash
Copy code
mysql -u root -p
7. Set Up Development Environments and Virtualization
Docker Installation
Download Docker Desktop:
Visit the Docker website.
Install Docker Desktop:
Run the installer and follow the prompts.
Verify Docker Installation:
bash
Copy code
docker --version
docker run hello-world
Create a Dockerfile
Create Dockerfile:

dockerfile
Copy code
FROM python:3.9-slim
WORKDIR /app
COPY . /app
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 80
ENV NAME World
CMD ["python", "app.py"]
Build and Run Docker Container:

bash
Copy code
docker build -t my-python-app .
docker run -p 4000:80 my-python-app
8. Explore Extensions and Plugins
Visual Studio Code Extensions
Python:
Python Extension
JavaScript/TypeScript:
ESLint
Code Formatting:
Prettier - Code Formatter
Git Integration:
GitLens
GitHub Pull Requests and Issues
Productivity Enhancements:
Bracket Pair Colorizer
Path Intellisense
Troubleshooting Steps
Python Not Added to PATH: If Python is not recognized, ensure the installation path is added to the system PATH environment variable.
MySQL Service Not Starting: Check if the MySQL service is running via the Services management console (services.msc).
Docker Daemon Not Running: Ensure Docker Desktop is started and running correctly. Restart the service if necessary.
By following these steps, you have set up a robust developer environment with all necessary tools, configurations, and extensions to enhance productivity and maintain consistency across different development machines.    

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
