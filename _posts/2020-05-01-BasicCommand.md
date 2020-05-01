---
title: Linux Basic Command
categories:
- Linux
- Debian
---

### Linux Basic Command

So, basically, a shell is a program that receives commands from the user and gives it to the OS to process, and it shows the output. Linux's shell is its main part. Its distros come in GUI (graphical user interface), but basically, Linux has a CLI (command line interface). In this tutorial, we are going to cover the basic commands that we use in the shell of Linux.
<br>
<br>
Sometimes, commands are also referred as "programs" since whenever you run a command, it's the corresponding program code, written for the command, which is being executed. Let's learn the must know Linux commands.
<br>

<h4><u> Navigation </u></h4>

| Command | Description |
| :-: | :-: |
| ```pwd``` | Print name of the current / working directory |
| ```ls [path]``` | List directory content |
| ```cd [path]``` | Change directory |

<br>

<h4><u> Help </u></h4>

| Command | Description |
| :-: | :-: |
| ```man [command]``` | Display summary information of a command |
| ```apropos [command]``` | Display all the available man pages |
| ```command  --help``` | Display short summary information of a command |
| ```command  -h``` | Display short summary information of a command |

<br>

<h4><u> Text Editor </u></h4>

| Command | Description |
| :-: | :-: |
| ```nano``` | Simple text editor |
| ```vi``` | Advance text editor |
| ```gedit``` | Notepad |

<br>

<h4><u> File Visualization </u></h4>

| Command | Description |
| :-: | :-: |
| ```echo '[text]'``` | Display a line of text |
| ```cat [file]``` | Concatenate Files |
| ```head [file]``` | Print the first 10 lines of the text file |
| ```tail [file]``` | Print the last 10 lines of the text file |
| ```more [file]``` | View the content part by part |
| ```less [file]``` | View the content part by part |
| ```grep [file]``` | Print lines of a text file that match a pattern |

<br>

<h4><u> File Information </u></h4>

| Command | Description |
| :-: | :-: |
| ```file [path]``` | Print file type |
| ```stat [path]``` | Print detailed information about the file |
| ```wc [path]``` | Print lines, word and byte counts |
| ```diff --color [file 1] [file 2]``` | Compare two text file line by line |

<br>

<h4><u> Administration </u></h4>

| Command | Description |
| :-: | :-: |
| ```sudo [command[``` | Execute a command as the superuser |
| ```su [username]``` | Change User |
| ```su``` | Login to superuser |

<br>

<h4><u> Process </u></h4>

| Command | Description |
| :-: | :-: |
| ```ps``` | Display the running processes of the current terminal |
| ```ps -e``` | Display all running processes |
| ```kill``` | Sends a kill signal to the process |
| ```top``` | Real-time viewer of the processes |

<br>

<h4><u> File Permissions and Ownerships </u></h4>

| Command | Description |
| :-: | :-: |
| ```chmod``` | Change file mode bits |
| ```umask``` | Set file mode creation mask |
| ```chown``` | Change file owner and group |
| ```chgrp``` | Change group ownership |
| ```setfacl``` | Set file special permission |
| ```getfacl``` | Get file permission |

<br>

<h4><u> Disk and Devices </u></h4>

| Command | Description |
| :-: | :-: |
| ```lsblk``` | List block devices |
| ```df -H``` | Report file system disk space usage |

<br>

<h4><u> File Manipulation </u></h4>

| Command | Description |
| :-: | :-: |
| ```cp [source file] [destination file]``` | Copy a File |
| ```mv [source file] [destination file]``` | Move or rename files and direcotry |
| ```mkdir [path]``` | Make empty directories |
| ```rm [file]``` | Remove a file |
| ```rmdir [path]``` | Remove a directory |
| ```ln -s [source file] [destination file]``` | Create a symbolic link |

<br>

<h4><u> Redirection </u></h4>

| Command | Description |
| :-: | :-: |
| ```[command 1] | [command 2]``` | Redirect output of command1 to command2 |
| ```[command] > [file]``` | Redirect output of the command to a file |
| ```[command] >> [file]``` | Append output of the command to a file |
