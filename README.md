# Linux Cheatsheet

Welcome to the **Linux Cheatsheet** repository! This cheatsheet contains essential Linux commands categorized for easy reference.

## Table of Contents
- [Basic Commands](#basic-commands)
- [File Management](#file-management)
- [Process Management](#process-management)
- [User Management](#user-management)
- [Networking](#networking)
- [Permissions & Ownership](#permissions--ownership)
- [System Monitoring](#system-monitoring)
- [Package Management](#package-management)
- [Disk Management](#disk-management)

## Basic Commands
```sh
ls        # List directory contents
pwd       # Print current working directory
cd <dir>  # Change directory
whoami    # Display current user
man <cmd> # Show manual for a command
```

## File Management
```sh
touch file.txt     # Create an empty file
cp file1 file2     # Copy file1 to file2
mv file1 file2     # Rename/move file1 to file2
rm file.txt        # Delete a file
mkdir newdir       # Create a new directory
rmdir emptydir     # Remove an empty directory
```

## Process Management
```sh
ps aux             # View running processes
kill <PID>         # Kill a process by PID
killall <name>     # Kill all processes by name
top                # Display real-time process usage
htop               # Interactive process viewer (if installed)
```

## User Management
```sh
who          # Show who is logged in
id <user>    # Show user ID and group ID
sudo su      # Switch to root user
passwd       # Change user password
adduser new  # Add a new user
```

## Networking
```sh
ip a                # Show network interfaces
ping google.com     # Test network connectivity
netstat -tulnp      # Show active connections
curl -I <url>       # Fetch headers from a website
wget <url>          # Download a file
```

## Permissions & Ownership
```sh
chmod 755 file      # Change file permissions
chown user:group file # Change file ownership
ls -l              # Show file permissions
```

## System Monitoring
```sh
uptime      # Show system uptime
free -h     # Display memory usage
df -h       # Show disk usage
vmstat      # System performance stats
```

## Package Management
### Debian/Ubuntu:
```sh
apt update && apt upgrade  # Update and upgrade packages
apt install <package>      # Install a package
apt remove <package>       # Remove a package
```
### RHEL/CentOS:
```sh
yum update -y              # Update packages
yum install <package>      # Install a package
yum remove <package>       # Remove a package
```

## Disk Management
```sh
lsblk      # List block devices
fdisk -l   # Show disk partitions
mount /dev/sdX /mnt  # Mount a disk
umount /mnt  # Unmount a disk
```

## Contributing
Feel free to contribute to this cheatsheet! Submit a pull request with any new useful Linux commands.

## License
This project is licensed under the MIT License.

---
Enjoy using Linux! 🚀
