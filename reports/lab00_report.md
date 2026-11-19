# Lab 00 – Linux Command-Line Practice

**Student Name:** Faizal Saifudeen  
**Course:** Cybersecurity (CS)

## 1. Introduction

Linux command-line tools are important in cybersecurity because they allow users to manage files, inspect system information, and control access permissions. This practical introduced basic terminal operations using Kali Linux.

## 2. Tasks Performed

During this practical, I worked with the Linux filesystem and performed the following operations:

- Used `pwd`, `cd`, and `ls` to navigate and inspect directories.
- Created a working directory and a subdirectory with `mkdir`.
- Created a text file using `touch` and entered content using `echo`.
- Organised files by moving them with `mv` and creating copies with `cp`.
- Renamed the text file to `my_profile.txt`.
- Used `du` to examine file and directory sizes.
- Applied `chmod 444` to make the profile file readable but not writable by its owner, group, or other users.
- Used `whoami` to identify the current account.
- Checked home-directory storage usage with `du -sh ~` and filesystem capacity with `df -h ~`.
- Verified the file contents and permissions using `cat` and `ls -l`.

## 3. Results and Learning

The practical demonstrated how everyday file-management tasks can be completed through terminal commands. I also learned that Linux permissions determine which users can read, modify, or execute a file. The `chmod 444` command provided a practical example of restricting write access.

## 4. Conclusion

This lab gave me practical experience with essential Linux commands in Kali Linux. I gained a better understanding of directory organisation, file operations, permission management, and basic system monitoring. These skills provide a useful foundation for further cybersecurity exercises.
