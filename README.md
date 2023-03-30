# Linux_Overview
Overview of Linux commands.

Basic Linux commands PART 1

Check Free CPU memory
Free; This shows the used, total and free memory.



Check current processes
Ps; shows a snapshot of current processes.

 


Check active Linux processes
top; displays current Linux processes.
htop: gives graphical representation.
 


IP traffic monitor
Iptraf; shows a GUI page for ethernet traffic 
 

Iptraf -ng nc; captures traffic
 

Controlling Network manager
Nmcli; shows all network interface
 

List files and directories
ls; list all files and directories
ls -a; list all hidden files
ls-al;
ls -ah;
 

 

Controls the hostname
hostnamectl; displays all info on controlling the hostname
 

Netstat
Check listening ports
netstat -tulpn; shows all active ports on ‘’listening’’ mode

Check all open ports
netstat
 

Make directory
mkdir; creates a directory
 

Check present working directory
pwd; checks the current working directory
 

Remove files and directory
rm filename ; removes a file
rm -r directory_name; removes a directory
 

To check uptime
uptime; to check uptime of the server.
 

Copy file content
 cp {filename1} {filename2}; copies the content of one file to another
 

Displays content of file
cat {file_name}; displays content of {file_name}

Create a new file
touch {file_name}; creates a new file
 

File {filename}; shows the type of document
 

Removes files or directory
rm -I {file_name}; ask for permission before removing a file
rm -rf {file_name}; forcefully removes a file or directory
rm {file_name}; removes only a file, not the file_name.

More
more is a filter for paging through text one screenful at a time. This version is especially primitive. Users should realize that less (1) provides more(1) emulation plus extensive enhancements.

head {file_name}; shows the first 10 lines in the file.
tail {file_name}; shows the last 10 lines in the file.

Displays active users
id; displays active users 
 

Shows system logins
last; shows lists of all active system logins
 

Current logon
who; shows who is currently logged in.
 


Add new group
groupadd {group_name}; adds a new group.
 

Add a new user
adduser {user_name}; creates a new user.

<img width="853" alt="Screenshot 2023-03-28 at 17 51 15" src="https://user-images.githubusercontent.com/67044030/228935887-21399cfb-b23f-407a-9c81-807aadafecee.png">

 

Delete user
userdel {user_name}; deletes an active user.

<img width="729" alt="Screenshot 2023-03-28 at 17 55 09" src="https://user-images.githubusercontent.com/67044030/228936244-1948a867-2e9a-4bdf-8e2d-d1d3507fcbb1.png">
 

Modify user
usermod {user_name}; modifies an active user.


Change directory group
chgrp {group_name} {directory_name}; changes the directory group.

Install package manager
sudo apt install {package_manager};  installs package manager.
 

Terminate a Linux process
Kill {PID}; Kills a Linux process under a given ID.

Terminate all processes
Kill all {process_name}; Terminates all processes with the labelled ID

Resume stopped jobs
bg; list and resume stopped jobs in the background
 

Resume recently suspended jobs
fg; brings up the most recently suspended jobs to the foreground.
 

Shows kernel info
Uname -a; displays kernel release info

<img width="1008" alt="Screenshot 2023-03-28 at 18 11 40" src="https://user-images.githubusercontent.com/67044030/228936627-9ae0c7df-7b31-4b67-ae2d-15a6c874425f.png">
 

Display current date
date; shows current time.

<img width="703" alt="Screenshot 2023-03-28 at 18 14 52" src="https://user-images.githubusercontent.com/67044030/228937025-b0a41d90-d478-4f71-8958-d96e01f07a3e.png">
 

Displays IP address
hostname -I; shows IP address

<img width="583" alt="Screenshot 2023-03-28 at 18 16 58" src="https://user-images.githubusercontent.com/67044030/228937260-84aacda2-949e-4b4e-87e3-964ed9301adb.png">
 

List IP address
Ip add show; list all IP address and network interfaces

<img width="975" alt="Screenshot 2023-03-28 at 18 18 04" src="https://user-images.githubusercontent.com/67044030/228937526-9aefcc9c-eba1-4027-b75d-6b44787de1d3.png">
 

Add IP address to interface.
ip address add {IP_address}; assigns IP address to interface etho

Shutdown
Shutdown {hh:mm}; schedules shutdown
Shutdown now; immediate shutdown

DISKS
df -h; shows free and used space on mounted system

<img width="722" alt="Screenshot 2023-03-28 at 18 27 36" src="https://user-images.githubusercontent.com/67044030/228937818-ca73ac09-b70b-4570-bdd9-408161887426.png">
 
df -ah; shows disk usage for all files and directory.

<img width="632" alt="Screenshot 2023-03-28 at 18 28 36" src="https://user-images.githubusercontent.com/67044030/228938039-3eb265f0-510c-47de-b1b8-05cc557d8c0b.png">
 

SSH
ssh user@host; connects to host as user
ssh -p {port} user@host; connect to host using a specific port number

File ownership
Chmod 777 {file_name}; assigns read, write and execute permissions to everyone
Chmod 755 {file_name}; assigns read, write, and execute to owners, read and execute to group and others.
Chmod 766 {file_name}; assigns full ownership to owner, read and right permission to group and others.
Chmod 600 {file_name};  full permission to owner, no access to group and others.
Chown {user_name}:{group} {file_name}; changes the owner and group membership of a file.

DNS information
Dig; shows dns information about a domain
 

NSLOOKUP
nslookup {domain_name}; displays info about internet domain.


Download file from internet
wget {filename/web address}; downloads the file or the document from webpage
 

Remote file save
Curl -o {file_name}; saves a remote file to your system

Lock account
Usermod -L {account_name}; locks an account.

Admin user add.
sudo useradd -m {user_name}; adds users as admin

Set password
Sudo password {user_name}; sets user password.

Query system
Journalctl; queries the system 
 

SYSTEMCTL
Controls the systemd system and service manager
Manage service
Service {service_name} status
Systemctl status {service_name}
Systemctl status httpd.service; checks status of httpd service
Systemctl start httpd. service; starts httpd service
Systemctl restart httpd. service; restarts httpd service
Systemctl status apache2; checks status of apache service

Search files
Ps aux | grep {service_name}; Searches for a pattern in each file.

Disk
Mount; Checking existing mount
 

Ls/mnt



