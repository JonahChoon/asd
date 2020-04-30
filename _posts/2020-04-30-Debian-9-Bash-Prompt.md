---
title: Debian Bash Prompt
categories:
- Linux
- Debian
---

STEP 1: EDIT THE BASHRC
vi ~/.bashrc
export PS1="escape codes"

Escape Codes:
\d: Insert the current date 
\t: Insert the current time
\u: Insert the current user
\h: Insert the hostname
\H: Insert the FQDN
\w: Insert the working directory
\\: Insert a backslash
\n: Insert a new line

STEP 2: RELOAD BASHRC
source ~/.bashrc
