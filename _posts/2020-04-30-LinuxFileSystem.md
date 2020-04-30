---
title: [1] Linux File System
categories:
- Linux
- Debian
---

### Linux Filesystem Structure

The Filesystem Hierarchy Standard (FHS) defines the structure of file systems on Linux and other UNIX-like operating systems. However, Linux file systems also contain some directories that aren’t yet defined by the standard.
<br>
<br>
In Debian, ext4 is the default file system for new installations. GNU/Linux can be installed on any filesystem that supports some special constructs (file permissions, symbolic links and device files). Many file systems are journaling, meaning they are able to prevent data loss on system crashes or power failures
<br>
<br>

![Linux File System](/image/LinuxFileSystem.png)
<br>
<br>

| File Directory | Description |
| :-: |:-:|
| / | Root Directory for the entire file system |
| /bin/ | User Binaries |
| /opt/ | Optional Add-On Apps |
| /boot/ | Boot Loader Files |
| /root/ | Home Directory for the 'root' user |
| /dev/ | Device Files |
| /sbin/ | System Binaries |
| /etc/ | Configuration Files |
| /srv/ | Service Data |
| /home/ | Home Directories |
| /tmp/ | Temporary Files |
| /lib/ | System Libraries |
| /usr/ | User Programs |
| /media/ | Removable Device |
| /var/ | Variables Files |
| /mnt/ | Mount Directory |
