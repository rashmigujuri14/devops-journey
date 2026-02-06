# Linux Basics – DevOps Journey

Linux is the backbone of modern DevOps practices. Most servers, cloud platforms, and DevOps tools run on Linux.
Created by Linus Torvalds



**What is Linux?**
Linux is an open-source operating system kernel used to manage hardware and software resources. Most servers, cloud platforms, and containers run on Linux.
Why Linux is important for DevOps?
Most production servers run Linux
DevOps tools (Docker, Kubernetes, Jenkins) are Linux-native
Powerful CLI automation
Stable, secure, and lightweight

**Linux Architecture**
Hardware - CPU, Memory, Disk
Kernel - Core of Linux (process, memory, file system)
Shell - Interface between user & kernel
Applications - Commands & programs

**##Common Linux Commands with Examples**
🟢 1. File & Directory Commands
ls          -list files
ls -la      - detailed list
pwd         - current directory
cd          - change directory
cd ..       - go back
cd ~        - home directory
mkdir       - create directory
rmdir       - delete empty directory
touch       - create file
cp          - copy files
mv          - move/rename files
rm          - delete file
rm -r       - delete directory
rm -rf      - force delete (danger ⚠️)
tree        - directory structure


🟢 2. File Viewing & Editing
cat         - view file
tac         - reverse cat
less        - scroll view
more        - basic view
head        - first lines
tail        - last lines
tail -f     - live logs
nano        - editor
vi / vim    - editor


🟢 3. File Permissions & Ownership
chmod        - change permission
chmod 777 file
chmod +x file
chown        - change owner
chgrp        - change group
umask        - default permission


🟢 4. Search & Find
find         - find files
locate       - fast search
which        - command location
whereis      - binary location
grep         - search text
grep -i      - ignore case
grep -r      - recursive


🟢 5. Disk & Storage
df -h        - disk usage
du -sh      - folder size
lsblk       - block devices
mount       - mount disk
umount      - unmount
blkid       - UUID info


🟢 6. Process & System Monitoring
top         - live process
htop        - advanced (if installed)
ps          - process list
ps aux
kill        - kill process
kill -9     - force kill
uptime      - system time
free -h     - RAM usage
watch       - repeat command


🟢 7. User & Group Management
whoami
id
who
users
useradd
userdel
usermod
groupadd
groupdel
passwd
su
sudo


🟢 8. Networking Commands
ip a
ip r
ifconfig        -old
ping
netstat
ss
curl
wget
scp
rsync
ftp
telnet
traceroute


🟢 9. Package Management (Ubuntu/Debian)
apt update
apt upgrade
apt install
apt remove
apt purge
apt search
dpkg -i

(RHEL/CentOS)
yum
dnf
rpm


🟢 10. Compression & Archives
tar -cvf
tar -xvf
tar -czvf
tar -xzvf
zip
unzip
gzip
gunzip


🟢 11. Environment & Variables
env
printenv
export
set
unset
alias
unalias


🟢 12. Shell & Utility Commands
history
clear
exit
date
cal
time
watch
yes
sleep
bc


🟢 13. Redirection & Pipes (VERY IMPORTANT 🔥)
>       -overwrite
>>      - append
<       - input
|       - pipe
2>      - error
&>      - all output

Example:
ls | grep txt


🟢 14. System Control
shutdown
reboot
poweroff
systemctl
systemctl status
systemctl start
systemctl stop
systemctl restart
journalctl


🟢 15. Help & Documentation (Never forget this!)
man command
command --help
info command


