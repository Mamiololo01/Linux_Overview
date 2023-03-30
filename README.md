# Linux_Overview
Overview of Linux commands.

Basic Linux commands PART 1

Check Free CPU memory
Free; This shows the used, total and free memory.



Check current processes
Ps; shows a snapshot of current processes.

 


Check active Linux processes
top; displays current Linux processes.

<img width="971" alt="Screenshot 2023-03-28 at 16 57 41" src="https://user-images.githubusercontent.com/67044030/228941702-f44a0df7-0fdc-42ec-82de-dcfb76c116d4.png">

htop: gives graphical representation.
 


IP traffic monitor
Iptraf; shows a GUI page for ethernet traffic 

<img width="998" alt="Screenshot 2023-03-28 at 16 43 51" src="https://user-images.githubusercontent.com/67044030/228940577-50cca05a-548f-4f10-836b-381202398e46.png">
 

Iptraf -ng nc; captures traffic

<img width="661" alt="Screenshot 2023-03-28 at 16 44 23" src="https://user-images.githubusercontent.com/67044030/228940795-bcb98800-728b-4786-9f62-691dba8cb683.png">
 

Controlling Network manager
Nmcli; shows all network interface

<img width="772" alt="Screenshot 2023-03-28 at 16 47 01" src="https://user-images.githubusercontent.com/67044030/228940976-cb5ff551-2c06-47be-ab06-d570e686138a.png">
 

List files and directories
ls; list all files and directories
ls -a; list all hidden files
ls-al;
ls -ah;

<img width="824" alt="Screenshot 2023-03-28 at 16 53 14" src="https://user-images.githubusercontent.com/67044030/228941274-c7c5f268-ba2b-4167-994c-8907b3beab37.png">

<img width="921" alt="Screenshot 2023-03-28 at 16 53 50" src="https://user-images.githubusercontent.com/67044030/228941547-d18a2986-ae18-4ce1-a266-d254270acfc9.png">
 

 

Controls the hostname
hostnamectl; displays all info on controlling the hostname

<img width="709" alt="Screenshot 2023-03-28 at 17 00 46" src="https://user-images.githubusercontent.com/67044030/228941962-1a741118-f70f-4ae6-9579-eb89d7865ed5.png">
 

Netstat
Check listening ports
netstat -tulpn; shows all active ports on ‘’listening’’ mode

<img width="874" alt="Screenshot 2023-03-28 at 17 04 40" src="https://user-images.githubusercontent.com/67044030/228942188-aedac0de-230a-4d7b-942c-14174053dd64.png">

Check all open ports
netstat
 

Make directory
mkdir; creates a directory

<img width="705" alt="Screenshot 2023-03-28 at 17 09 15" src="https://user-images.githubusercontent.com/67044030/228942505-3ea84ed6-6176-4c15-86e6-6c7100ce66bb.png">
 

Check present working directory
pwd; checks the current working directory

<img width="697" alt="Screenshot 2023-03-28 at 17 10 52" src="https://user-images.githubusercontent.com/67044030/228942962-27890aba-615a-47e8-80c7-181d032edb88.png">
 

Remove files and directory
rm filename ; removes a file
rm -r directory_name; removes a directory

<img width="782" alt="Screenshot 2023-03-28 at 17 15 35" src="https://user-images.githubusercontent.com/67044030/228943147-b06ec411-e4bc-4126-9715-ba7c8229c19e.png">


<img width="649" alt="Screenshot 2023-03-28 at 17 42 45" src="https://user-images.githubusercontent.com/67044030/228939510-4361f948-d996-4686-a0b2-dadf316fc648.png">
 

To check uptime
uptime; to check uptime of the server.

<img width="653" alt="Screenshot 2023-03-28 at 17 17 07" src="https://user-images.githubusercontent.com/67044030/228943350-5ca8ac48-b278-4cd5-8f7a-b47e6ece1f33.png">
 

Copy file content
 cp {filename1} {filename2}; copies the content of one file to another
 
 <img width="867" alt="Screenshot 2023-03-28 at 17 22 48" src="https://user-images.githubusercontent.com/67044030/228943702-ac8e7510-a3d7-45f9-a092-543d091980fa.png">
 

Displays content of file
cat {file_name}; displays content of {file_name}

Create a new file
touch {file_name}; creates a new file

<img width="703" alt="Screenshot 2023-03-28 at 17 33 32" src="https://user-images.githubusercontent.com/67044030/228943968-79556d65-a8f0-4832-ac8e-13c517ecbd28.png">
 

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

<img width="718" alt="Screenshot 2023-03-28 at 19 03 11" src="https://user-images.githubusercontent.com/67044030/228938290-054031dc-d2da-4297-9511-679154385b10.png">
 

NSLOOKUP
nslookup {domain_name}; displays info about internet domain.


Download file from internet.
wget {filename/web address}; downloads the file or the document from webpage

<img width="828" alt="Screenshot 2023-03-28 at 19 09 22" src="https://user-images.githubusercontent.com/67044030/228938619-be208445-9ba0-4248-a075-09056cbb3cc9.png">
 

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

<img width="843" alt="Screenshot 2023-03-28 at 19 15 01" src="https://user-images.githubusercontent.com/67044030/228938927-1b9763f0-c21c-4254-8c21-765edc16545b.png">
 

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

<img width="867" alt="Screenshot 2023-03-28 at 19 44 39" src="https://user-images.githubusercontent.com/67044030/228939159-487ed476-8948-4554-bb2c-2a0f216c0c76.png">

Ls/mnt



