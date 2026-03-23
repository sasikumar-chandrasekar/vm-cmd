VM / Linux Basic Commands

# Directory Navigation Commands

## Show the current working directory
pwd

## List files and directories
ls

## List files with detailed information
ls -l

## List all files including hidden files
ls -a

## Change directory to /home
cd /home

## Go back one directory level
cd ..

## Go to home directory
cd ~

# File and Directory Management

## Create a directory
mkdir test

## Create nested directories
mkdir -p parent/child

## Create an empty file
touch file.txt

## Display file content
cat file.txt

## View file content page by page
less file.txt

## Copy a file
cp file.txt backup.txt

## Copy a directory recursively
cp -r test test_backup

## Move or rename a file
mv file.txt data.txt

## Delete a file
rm data.txt

## Delete a directory and its contents
rm -r test

# System Information Commands

## Display kernel, OS, and architecture information
uname -a

## Display hostname of the VM
hostname

## Show system uptime and load
uptime

## Show CPU details
lscpu

## Show OS version details
cat /etc/os-release

# Disk and Memory Commands

## Show disk usage in human readable format
df -h

## Show size of a directory
du -sh /var/log

## Show RAM usage
free -h

## Show mounted file systems
mount

# Process Management

## Display running processes in real time
top

## Display all running processes
ps -ef

## Search for a process by name
ps -ef | grep nginx

## Kill a process using PID
kill 1234

## Force kill a process
kill -9 1234

# Network Commands (Very Important for VMs)

## Show IP address and network interfaces
ip a

## Show routing table
ip route

## Test network connectivity
ping google.com

## Show open ports and listening services
ss -tuln

## Check DNS resolution
nslookup google.com

# User and Permission Management

## Show current logged-in user
whoami

## Show logged-in users
who

## Change file permissions
chmod 755 script.sh

## Give full permission to owner
chmod u+rwx file.txt

## Change file ownership
chown user:user file.txt

# Package Management
  
Ubuntu / Debian

## Update package list
sudo apt update

## Install a package
sudo apt install nginx

## Remove a package
sudo apt remove nginx

RHEL / CentOS

## Install a package
sudo yum install nginx

# Service Management (systemd)

## Start a service
sudo systemctl start nginx

## Stop a service
sudo systemctl stop nginx

## Restart a service
sudo systemctl restart nginx

## Enable service at boot
sudo systemctl enable nginx

## Check service status
sudo systemctl status nginx

# VM Power Commands

## Reboot the virtual machine
sudo reboot

## Shutdown the VM immediately
sudo shutdown now

## Shutdown the VM after 5 minutes
sudo shutdown +5

# Help and Troubleshooting Commands

## Show manual page for a command
man ls

## Show help for a command
ls --help

## Show command path
which ls

## Show command history
history

## Clear terminal screen
clear
