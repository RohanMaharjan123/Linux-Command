# Week 1: Linux Command

## Essential Linux Commands

| **Command**       | **Usage**                        | **Example**                          |
|-------------------|----------------------------------|--------------------------------------|
| `ls`              | List directory contents         | `ls -l /etc`                         |
| `cp`              | Copy files or directories       | `cp file1 file2`                     |
| `mv`              | Move or rename files            | `mv file1 /tmp/`                     |
| `rm`              | Remove files or directories     | `rm file1`                           |
| `mkdir`           | Create directories              | `mkdir my_folder`                    |
| `touch`           | Create an empty file            | `touch new_file.txt`                 |
| `cat`             | View file contents              | `cat /etc/hosts`                     |
| `echo`            | Display a message               | `echo "Hello, World!"`               |
| `pwd`             | Print current working directory | `pwd`                                |
| `chmod`           | Change file permissions         | `chmod 755 file.sh`                  |
| `uname`           | Display system information      | `uname -a`                           |

---

## Linux Disk and Network Commands

| **Command**       | **Usage**                        | **Example**                          |
|-------------------|----------------------------------|--------------------------------------|
| `fdisk`           | Partition a disk                | `sudo fdisk /dev/sda`                |
| `fsck`            | Check and repair filesystems    | `sudo fsck /dev/sda1`                |
| `reboot`          | Reboot the system               | `sudo reboot`                        |
| `init`            | Change system runlevel          | `sudo init 0` (shutdown)             |
| `mkfs`            | Create a filesystem             | `sudo mkfs.ext4 /dev/sda1`           |
| `ifconfig`        | Configure network interfaces    | `ifconfig eth0`                      |
| `halt`            | Stop the system                 | `sudo halt`                          |

---

## Linux File and Log Management

| **Command**       | **Example**                     | **Description**                      |
|-------------------|----------------------------------|--------------------------------------|
| View logs         | `cat /var/log/syslog`           | Views the Linux system log.          |
| Cache             | `ls /var/cache`                | Lists cache files (may require sudo). |
| Temporary files   | `ls /tmp`                      | Lists temporary files.               |
| Clear logs        | `sudo rm /var/log/*.log`        | Clears log files (requires admin access). |

---

## Linux Disk and Directory Commands

| **Command**       | **Example**                     | **Description**                      |
|-------------------|----------------------------------|--------------------------------------|
| `find`            | `find . -name "*.txt"`          | Finds all `.txt` files in the current directory and subdirectories. |
| `df`              | `df -h`                         | Displays disk space usage in a human-readable format. |
| `du`              | `du -sh /var`                   | Shows disk usage of the `/var` directory. |
| `mount`           | `sudo mount /dev/sda1 /mnt`     | Mounts a partition to a directory.   |
| `umount`          | `sudo umount /mnt`              | Unmounts a partition from a directory. |
| `lsblk`           | `lsblk`                         | Lists information about block devices. |
| `blkid`           | `sudo blkid`                    | Displays UUID and file system type of devices. |
| `diskutil`        | `sudo mkfs.ext4 /dev/sda1`      | Formats a partition with the ext4 file system. |

---

## Linux System Management Commands

| **Command**       | **Example**                     | **Description**                      |
|-------------------|----------------------------------|--------------------------------------|
| `hostname`        | `hostname`                      | Prints the hostname of the system.   |
|                   | `sudo hostname new-hostname`    | Changes the hostname temporarily.    |
| `passwd`          | `passwd`                        | Changes the current user’s password. |
| `crontab`         | `crontab -e`                    | Opens cron jobs for scheduling tasks. |
|                   | `crontab -l`                    | Lists scheduled cron jobs.           |

---

## Linux Process and Resource Management

| **Command**       | **Example**                     | **Description**                      |
|-------------------|----------------------------------|--------------------------------------|
| `ps`              | `ps aux`                        | Displays information about running processes. |
| `top`             | `top`                           | Shows real-time system resource usage. |
| `htop`            | `htop`                          | Interactive process viewer (requires installation). |
| `kill`            | `kill -9 1234`                  | Kills a process with PID 1234.       |
| `free`            | `free -h`                       | Displays memory usage in human-readable format. |
| `uptime`          | `uptime`                        | Shows how long the system has been running. |

---

## Linux Package Management Commands

| **Command**       | **Example**                     | **Description**                      |
|-------------------|----------------------------------|--------------------------------------|
| `apt`             | `sudo apt update`               | Updates the package list (Debian/Ubuntu). |
|                   | `sudo apt upgrade`              | Installs available updates.          |
| `yum`             | `sudo yum update`               | Updates packages (Red Hat/CentOS).   |
| `dnf`             | `sudo dnf install package-name` | Installs a package (Fedora).         |
| `rpm`             | `rpm -qa`                       | Lists installed RPM packages.        |
| `snap`            | `snap install package-name`     | Installs a package via Snap.         |

---
