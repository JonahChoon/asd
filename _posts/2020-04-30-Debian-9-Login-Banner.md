---
title: Debian Login Banner
categories:
- Linux
- Debian
---

STEP 1: BEFORE LOGIN AND NETWORK BANNER
vi /etc/issue

STEP 2: AFTER LOGIN AND NETWORK BANNER
vi /etc/motd

ESCAPE CODES
\b: Insert the baud rate of the current line.
\d: Insert the current date.
\s: Insert the system name, the name of the operating system.
\l: Insert the name of the current tty line.
\m: Insert the architecture identifier of the machine, eg. i486
\n: Insert the node name of the machine, also known as the hostname.
\o: Insert the domain name of the machine.
\r: Insert the release number of the OS, eg. 1.1.9.
\t: Insert the current time.
\u: Insert the number of current users logged in.
\v: Insert the version of the OS, eg. the build-date etc.
