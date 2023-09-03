# Linux Shell Commands for Hosting

Description: This README provides an explanation of the Linux shell commands used in the project. It demonstrates the setup and configuration of various tools and services in a Linux environment.

## Before you proceed, ensure that you have access to a Linux-based operating system with a shell (e.g., Bash) and the following tools installed:

Node.js: A JavaScript runtime for executing JavaScript code on the server side.

Yarn (Optional): A package manager for Node.js projects.

Nginx: A web server and reverse proxy server.

MongoDB (Optional): A NoSQL database for data storage.


## Commands and Explanations
The following is a breakdown of the Linux shell commands used in the project:

> Directory Listing:
```
dir
ls -a
dir: List files and directories in the current directory.
```
ls -a: List all files and directories, including hidden ones.
> Clearing the Terminal:
```
clear
```
clear: Clears the terminal screen.

> Node.js and Package Management:
```
nvm
node -v
sudo yum update
sudo yum install –y nodejs
```

nvm: Node Version Manager.
node -v: Check Node.js version.
sudo yum update: Update system packages.
sudo yum install –y nodejs: Install Node.js.

> Git and Version Control:

```
git -v
```
git -v: Check Git version.

> Web Servers (Nginx and Apache):
```
apache -v
which http
which httpd
```
apache -v: Check Apache HTTP Server version.
which http: Find the location of an executable.
which httpd: Find the location of the Apache HTTP Server executable.

> Systemctl and Service Management:
```
sysctl stop httpd
sysctl status httpd
sysctl status httpd2
```
sysctl stop httpd: Stop the HTTPd service.
sysctl status httpd: Check the status of HTTPd service.
sysctl status httpd2: Check the status of HTTPd2 service.

> File and Directory Operations:
```
ls -la /etc/systemd/system/
```
ls -la /etc/systemd/system/: List files and directories in the specified directory.

> Nginx Installation:
```
sudo yum install nginx
```
sudo yum install nginx: Install Nginx web server.

> Editing Configuration Files:
```
cd /etc/nginx/
nano nginx.conf
```
cd /etc/nginx/: Change directory to Nginx configuration files.
nano nginx.conf: Edit the Nginx configuration file.

> Domain Resolution:
dig slowrug.io
dig slowrug.io: Perform DNS lookup for the domain "slowrug.io."

> Creating Directories:
```
mkdir sites-enabled
mkdir sites-available
```
mkdir sites-enabled: Create a directory for enabled Nginx sites.
mkdir sites-available: Create a directory for available Nginx sites.
> Editing Files:
```
nano slowrug.io
```
nano slowrug.io: Edit the "slowrug.io" file.

Checking Nginx Configuration:
```
nginx -t
```
nginx -t: Test the Nginx configuration for errors.
