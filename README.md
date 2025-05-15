# unix-project
Unix Project of Kukes Kanthasamy, Fahad Malik and Ethan Cole Hafso


Project Description
The aim of this project is to establish a GNU/Linux web server with automated deployment of websites. This process entails establishing a Virtual Private Server (VPS), implementing fundamental security measures, setting up the web server, and automating deployment: whenever a commit is made to the git repository, the website gets updated automatically. We will utilize a Public Domain license

 
Platform of Choice
We are using server as our platform choice.
Demonstration Plan
For the demonstration plan we will be using VPS.
Requirements
-          Basic system setup and security: Rent a VPS, Update the System, create a new user, set up SSH Key Authentication, Disable Root SSH Login & Password Authentication, set up a Firewall, set time zone and sync time and Install Essential Packages.
-          Process or service management/scheduling: Use systemd for service management, use cron for scheduled tasks,  	
-          Automated tasks using a script language: Use bash scripts for automation, backing up the database, set up the systemd services.

-      
Major technical solutions compared:
This project will compare different web servers (Nginx vs Apache) and Ubuntu and Debian and deployment automation methods to determine the most efficient and reliable setup. 
We will compare it based on ease of configuration, performance (how well it handles loading databases), security features, uptime and maybe more. 

Week 1:  
- Research Web Servers (Compare Nginx vs Apache) 
- Research Operating Systems (Compare Ubuntu vs Debian or other OS) 
- Research Deployment automation methods 
- Research a VPS Provider 
- Purchase a VPS (whichever was researched to be best) 
- Create GitHub repository 

Week 2:
- Install Web Server (whichever was researched to be best)
- Set up SSH Keys for each of us
- Set up Account for each of us
- Set up Firewall
- Disable root login
- Set timezone and time
- Install essential packages + updating
- Set up the OS in VPS
- Add database
Week 3:
- Configure deployment scripts to automatically update web servers using GitHub
- Set up cron jobs to automate deployments on the VPS
- Test the automated deployments by using the git commands




SSH Key (Ethan)

ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINycUt9EO81sktntefum4Tsu00czAFoU2LeAM9IDMJw+ ethan@your-email.com

