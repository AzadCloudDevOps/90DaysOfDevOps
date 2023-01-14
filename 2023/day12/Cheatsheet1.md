# Cheatsheet for Linux
Lets discuss what we learnt uptill now about Linux
## All about Linux
### Basics
```
#		  : root user
$		  : normal users
/ 	 	  : root directory 
~ 	 	  : home directory
man 		  : access manual pages for all Linux commands
uname    	  : show name of kernel (OS)
uname -r 	  : show version of kernel 
clear             : clear screen
whoami   	  : show currently login user name
history  	  : show list of previously used commands
date     	  : show time and date
cal      	  : show this month's calendar
lastlog  	  : details of a recent login of all users
df		  : shows the amount of free space on a file system
head  	 	  : shows the top N lines of the file (maximum 10)
tail     	  : shows the bottom N lines of the file (maximum 10)
cd ~ or cd        : change the directory to the home directory
cd - 		  : Go to the last working directory.
cd .. 		  : change the directory to one step back
cd ../.. 	  : Change directory to 2 levels back
users    	  : display the username of all users currently logged on the system
useradd		  : add new user
usermod		  : change existing users details
Chmod    	  : change the access permissions of files and directories
Chown    	  : change the file Owner or group
passwd		  : change the password for user
userdel & groupdel: to delete the user & group
```
### Networking
```
ping              : check the connectivity of host
sudo		  : allows regular users to run programs with the security privileges of the superuser
ssh 		  : secure shell command
ftp               : Opens an ftp connection to a host
```
### File management
```
ls 	  	  : long listing format of the files and directories with extra information
pwd 	 	  : present working directory
touch		  : to create a file
mkdir  		  : to make a directory in a specific location
rm & rmdir	  : used to remove a file & directory 
cp		  : copy files from one directory to another
mv 		  : move or rename files
cat       	  : view the content inside the file
echo 		  : print any text
grep              : Searches for a pattern in a file or a stream of text
find              : Searches for files and directories
awk               : Processes text files and data streams
diff 		  : find the difference between files
mount		  : mount file systems
umount            : unmount file systems
vim or nano       : to create a file and edit it
service 	  : to start and stop services
tar               : creates and extracts archive files
gzip              : compresses and decompresses files
unzip             : uncompresses archive files
crontab		  : schedules commands (specially backup) to be executed automatically
apt,pacman,yum,rpm: package managers used for diff. linux flavors
```
### Process Management
```
ps                : shows the running processes
kill 		  : kill active processes by process ID or name
top 		  : view active processes live with their system usage
```
