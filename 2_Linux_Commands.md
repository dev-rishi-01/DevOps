# 🐧 Linux Commands 

## 📂 File & Directory Management

```bash id="cmd001"
pwd        # Show current working directory
ls         # List directory contents
ls -l      # Detailed list with permissions
ls -a      # Show hidden files
cd         # Change directory
cd ..      # Move to parent directory
cd ~       # Go to home directory
mkdir      # Create a new directory
rmdir      # Remove empty directory
tree       # Display directory structure as tree
stat       # Show file/directory details
basename   # Extract file name from path
dirname    # Extract directory path
realpath   # Show absolute file path
```

---

## 📄 File Operations

```bash id="cmd002"
touch      # Create empty file
cp         # Copy files/directories
mv         # Move or rename files
rm         # Delete files/directories
unlink     # Remove a file
cat        # Display file content
tac        # Show file content in reverse
less       # View file page by page
more       # View file with forward navigation
head       # Show first lines of file
tail       # Show last lines of file
nl         # Show file with line numbers
wc         # Count words, lines, characters
file       # Identify file type
```

---

## 🔍 Search & Text Processing

```bash id="cmd003"
grep       # Search text pattern in files
egrep      # Extended grep (regex support)
fgrep      # Fast grep (fixed strings)
find       # Search files in directory
locate     # Find files quickly using database
which      # Show command path
whereis    # Locate binary/source files
awk        # Pattern scanning and processing
sed        # Stream editor for text
cut        # Extract columns from text
sort       # Sort lines of text
uniq       # Remove duplicate lines
tr         # Translate characters
diff       # Compare two files
comm       # Compare sorted files line by line
```

---

## 📦 Compression & Archiving

```bash id="cmd004"
tar        # Archive files
gzip       # Compress files
gunzip     # Decompress gzip files
zip        # Create zip archive
unzip      # Extract zip archive
bzip2      # Compress using bzip2
bunzip2    # Decompress bzip2
xz         # Compress files with xz
unxz       # Decompress xz files
```

---

## 👤 User Management

```bash id="cmd005"
whoami     # Show current user
who        # Show logged-in users
w          # Show user activity
id         # Show user ID info
useradd    # Add new user
userdel    # Delete user
usermod    # Modify user
passwd     # Change password
groupadd   # Create group
groupdel   # Delete group
groups     # Show user groups
```

---

## 🔐 Permissions

```bash id="cmd006"
chmod      # Change file permissions
chown      # Change file owner
chgrp      # Change group ownership
umask      # Set default permissions
```

---

## ⚙️ Process Management

```bash id="cmd007"
ps         # Show running processes
top        # Real-time process viewer
htop       # Interactive process viewer
kill       # Terminate process by PID
killall    # Kill processes by name
nice       # Set process priority
renice     # Change priority of running process
bg         # Resume job in background
fg         # Bring job to foreground
jobs       # Show active jobs
```

---

## 💾 Disk & Storage

```bash id="cmd008"
df         # Show disk space usage
du         # Show directory size
mount      # Mount filesystem
umount     # Unmount filesystem
lsblk      # List block devices
blkid      # Show device UUIDs
fdisk      # Partition disk
mkfs       # Create filesystem
fsck       # Check filesystem errors
```

---

## 🌐 Networking

```bash id="cmd009"
ping       # Test network connectivity
ifconfig   # Show network config (old)
ip         # Show/manage network interfaces
ss         # Display socket info
netstat    # Network statistics
curl       # Transfer data from URL
wget       # Download files from web
hostname   # Show system hostname
host       # DNS lookup
dig        # Detailed DNS query
```

---

## 🖥️ System Information

```bash id="cmd010"
uname      # Show system info
uptime     # Show system uptime
date       # Display current date/time
cal        # Show calendar
whoami     # Show current user
hostnamectl # System hostname info
arch       # Show architecture
lscpu      # CPU info
lsusb      # USB devices info
lspci      # PCI devices info
free       # Memory usage
vmstat     # System performance stats
```

---

## 📦 Package Management (Debian/Ubuntu)

```bash id="cmd011"
apt        # Package manager tool
apt-get    # Advanced package tool
apt-cache  # Query package cache
apt update # Update package list
apt upgrade # Upgrade packages
apt install # Install package
apt remove # Remove package
apt autoremove # Remove unused packages
dpkg       # Debian package manager
dpkg -i    # Install .deb file
```

---

## 📜 File Permissions & Ownership

```bash id="cmd012"
getfacl    # Get file ACL permissions
setfacl    # Set file ACL permissions
```

---

## 🔄 Redirection & Pipes

```bash id="cmd013"
>          # Redirect output (overwrite)
>>         # Redirect output (append)
<          # Input redirection
|          # Pipe output to another command
tee        # Output to file and screen
xargs      # Convert input to arguments
```

---

## ⌨️ Shell & Environment

```bash id="cmd014"
echo       # Print text
env        # Show environment variables
export     # Set environment variable
set        # Show/set shell variables
unset      # Remove variable
alias      # Create shortcut command
unalias    # Remove alias
source     # Run script in current shell
history    # Show command history
clear      # Clear terminal
exit       # Exit shell
```

---

## 🧪 Advanced / Misc Commands

```bash id="cmd015"
watch      # Run command repeatedly
time       # Measure execution time
yes        # Output text repeatedly
sleep      # Pause execution
shutdown   # Shutdown system
reboot     # Restart system
logout     # Log out user
crontab    # Schedule tasks
at         # Run command later
wall       # Send message to all users
write      # Send message to user
script     # Record terminal session
```

---

## 💡 Pro Tip

```bash id="cmd016"
man <command>   # Show manual of command
```

Example:

```bash id="cmd017"
man ls
```

---
