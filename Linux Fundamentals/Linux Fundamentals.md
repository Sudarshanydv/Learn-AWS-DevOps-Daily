# ✨ Daily Learning Update – Linux Fundamentals 🐧

Today I learned Linux fundamentals, and it was a super valuable experience for me as an AWS & DevOps Engineer. 🤗  
I understood how Linux is the backbone of most cloud environments, servers, and container systems like Docker & Kubernetes.  
It provides a secure, stable, and highly customizable platform, making it essential for automation, troubleshooting, and cloud deployment.

Learning Linux is definitely boosting my confidence in building efficient cloud and DevOps solutions. 🚀  
If you found this helpful, share your thoughts, experiences, or tips in the comments — I’d love to learn from you too! 😊

---

## 🐧 History of Linux
Linux was created in 1991 by Linus Torvalds as a free and open-source alternative to UNIX.  
The first Linux kernel was released publicly, allowing global developers to contribute and improve it.  
Today, Linux powers servers, supercomputers, Android devices, and modern cloud platforms like AWS.

---

## 🐧 What is Linux? — Fundamentals
Linux is an open-source, Unix-based operating system widely used in servers, cloud platforms, and DevOps environments.  
It manages hardware resources and provides a secure, stable, and customizable platform for running applications.  
Its hierarchical file system and shell interface enable automation and scripting, making Linux essential for DevOps workflows.

---

## ✔ Pros of Linux
- Free and open source
- Highly secure & stable
- Best performance for servers and cloud workloads
- Flexible & customizable with automation support
- Huge community and support

## ❌ Cons of Linux
- Steeper learning curve for beginners
- Limited compatibility with some commercial software
- More manual configuration required

---

## ⭐ Why Linux is Valuable in AWS DevOps
- Most AWS compute and container services run on Linux
- Supports automation & CI/CD for reliable deployment
- Strong performance, security & troubleshooting capabilities

---
# 📌 Linux Useful Commands – GitHub Table Format

| **Category** | **Command / Item** | **Description / Purpose** |
|-------------|---------------------|----------------------------|
| **Colors Meaning in Terminal** | Files | White |
| | Folders | Blue |
| | All Permission Granted | Green |
| | Close Editing File | `:q!`, `ctrl + x → Enter` |
| **Package Managers** | `apt-get` | Advanced Package Tool (Debian-based) |
| | `yum / dnf` | Yellowdog Updater Modified (RHEL-based) |
| | `dpkg` | Debian package manager |
| | `rpm` | RedHat Package Manager |
| **File System Operations** | `ls` | List files & folders |
| | `ls -lt`, `ls -ltr` | Permissions, groups, latest first |
| | `ls -l` | Detailed file listing |
| | `pwd` | Show current path |
| | `cat file` | View file content |
| | `touch file` | Create empty file |
| | `touch file{1..10}` | Create multiple files |
| | `nano file` | Create/Edit file |
| | `vi/vim file` | Edit file via VI editor |
| | `cd` | Change directory |
| | `cd ..` | Move back one folder |
| | `cd ../..` | Move back two levels |
| | `mkdir folder` | Create directory |
| | `mkdir -p a/b/c` | Create nested folders |
| | `rm file` | Remove file |
| | `rmdir folder` | Remove directory |
| | `cp file folder/` | Copy file to folder |
| | `mv file folder/` | Move/Cut file |
| | `mv old new` | Rename file or folder |
| | `head -5 file` | Show first 5 lines |
| | `tail -5 file` | Show last 5 lines |
| | `grep "word" file` | Search word |
| | `egrep "a|b"` | Search multiple words |
| | `wc -l file` | Line count |
| | `cmp fileA fileB` | Compare files |
| | `diff fileA fileB` | Show differences |
| | `find ./ -name test.csv` | Find file |
| | `locate file` | Locate file (after `updatedb`) |
| | `history` | Show executed commands |
| | `man ls` | Manual of command |
| | `gzip`, `gunzip`, `tar`, `zip` | Compress/Extract |
| | `wget <url>` | Download file |
| | `uptime` | Server running time |
| | `script` | Record terminal session |
| | `ctrl + d` | Exit & save |
| **Networking & Security** | `ping domain.com` | Check connectivity |
| | `ssh user@ip` | Connect remote |
| | `scp file user@ip:/path` | Transfer files |
| | `netstat -putan` | Check ports |
| | `traceroute url` | Track packet route |
| | `systemctl start/stop/status` | Service management |
| | `chmod`, `chown`, `chgrp` | File permissions & ownership |
| | `pgrep nginx` | Get process ID |
| | `pkill nginx` | Kill process |
| | `reboot`, `shutdown` | Restart / Stop server |
| **User & Group Management** | `useradd`, `userdel` | Add/Delete user |
| | `groupadd`, `groupdel` | Add/Delete group |
| | `passwd user` | Set password |
| | `su user` | Switch user |
| | `cat /etc/group` | View groups |
| **Scheduling** | `at 05:10 PM` | Schedule task |
| | `echo "task" > file` | Apply at schedule |






•	## Networking
ifconfig : Configure network interfaces
ping : Test network connectivity
netstat : Network statastics display
traceroute : Tracing the path an IP packet takes across one or many networks
iptables : Configure firewall rules
dig : a flexible toold for interrogating DNS name server
ip : Check IP


•	## System Service
Systemctl : Control system service 
Service : Manage system service 
Chkconfig : Service runlevel management 

•	## Process Management
ps : Display running processes
ps -ef | grep java : for check specific service.
ps –u :display technical all information about the processes
ps –A : This command lists even those processes that are currently not running.
top : System performance monitor
du : how much memory use in specific folder 
kill : Terminate a process
killall : Terminate processes by name

•	## Shell Scripting
bash : Bourne Again Shell
sh : Bourne Shell
awk : is a “general scanning and processing language”
tac : tac does the same thing as cat (in that it concatenates files)
grep : used to search lines containing a specific keyword in a file
sed : Stream editor for transformations
wc : Word Count was detailed in section 5 but has another often overlooked behaviour
tr : tr is used to “translate characters”
sort : used to rearrange lines of text in files or from standard input
diff : diff is used to find differences between two byte streams
tee : to split the output of a program so that it can be both displayed and saved in a file.

•	## System Information 
uname : Display System information 
df, df -h : Disk space usage, mounted, size
free : Memory usage information 
hostname : show/set system hostname
nslookup : command is used to troubleshoot network connectivity issues in the system.
systeminfo : shows your pc's details.
lscpu : cpu, core, thread info in server.
lsblk : disk partition, storage devices.
uname -a, cat /etc/os-release : showing OS related info.

•	## File Permission 
chmod : To change file permissions
chmod +x : Add execute permission to a file
Usage: To make a file executable.
Syntax: chmod +x [file]
Example: chmod +x script.sh
chown : To change file ownership
Syntax: chown [owner] [file]
Example: chown john myfile.txt
chgrp : To change group ownership
Syntax: chgrp [group] [file]
Example: chgrp admin myfile.txt
umask : Set default file creation permissions
Syntax: umask [mask]
Example: umask 022
getfacl : Get file access control lists (ACL)
Syntax: getfacl [file]
Example: getfacl myfile.txt
Displays the ACLs of myfile.txt.


u Means – User, g Means – Group, o Menas – Owner 
File Level permissions : These control permissions on the file level. 
r – read, w – write, x – execute…
Access 	Symbolic Mode	Octal Mode
Read	r	4
Write	w	2
Execute	x	1
	



Octal Value 	File Permissions Set 	Permissions Description 
0	---	No permissions 
1	--x	Execute permission only 
2	-w-	Write permission only 
3	-wx	Write and execute permissions 
4	r--	Read permission only 
5	r-x	Read and execute permissions 
6	rw-	Read and write permissions 
7	rwx	Read, write, and execute permissions 


•	## User And Group Management 
useradd : Add a new user
Syntax: useradd [options] username
Example: useradd john
usermod : Modify Existing user
Syntax: usermod [options] username
Example: usermod -aG sudo john
userdel : Remove existing user 
Syntax: userdel [options] username
Example: userdel john
groupadd : Create a new group
Syntax: groupadd [options] groupname
Example: groupadd admins 
groupmod : Modify existing group
Syntax: groupmod [options] groupname
Example: groupmod -n developers devs
groupdel : Remove existing group
Syntax: groupdel groupname
Example: groupdel devs

… Thank You …


#DevOps #AWS #Linux #LearningJourney #CloudComputing #Automation #CareerGrowth #DevOpsEngineer

## Name – Sudarshan Yadav, Contact - 7709877817
## Email Id – sudarshanyadav4080@gmail.com
GitHub: https://github.com/Sudarshanydv
Dev.to Blog: https://dev.to/sudarshan_yadav
LinkedIn: https://www.linkedin.com/in/sudarshan-yadav
Resume (Drive) - https://drive.google.com/file/d/1jas-UeQuCSR6OZCP6pAPTnLiWcJiAVk1/view?usp=drive_link
