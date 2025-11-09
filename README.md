# 🔐 File Permissions in Linux

This project was completed as part of the **Google Cybersecurity Professional Certificate**.  
It focuses on reviewing, managing, and securing file and directory permissions in a Linux environment to ensure proper access control and system security.

---

## 📘 Project Overview

The main objective of this project was to analyze and manage file permissions within a research team environment.  
The goal was to ensure that each user and group only had access to the files and folders they were authorized to use.

This involved:
- Checking existing file and directory permissions
- Identifying unauthorized access
- Applying proper permission settings
- Documenting all permission changes for accountability

By the end of the project, the system’s files and directories were more secure, with clearly defined access rules.

---
## ⚙️ Commands Used

### Check File and Directory Details
ls -la

**Change File Permissions**
chmod o-w project_k.txt

**Change Hidden File Permissions**
chmod u-w,g-w,g+r .project_x.txt

**Change Directory Permissions**
chmod g-x,g-r,o-r,o-x projects


**🧠 Key Skills Demonstrated**
Linux command-line operations
File and directory permission management
Access control and security configuration
Documentation and verification of security changes
Understanding of Linux permission strings (e.g., -rw-rw-r--)

**🔒 Summary **
This project demonstrates how to effectively manage Linux file and directory permissions to maintain data confidentiality and integrity.
By applying the ls and chmod commands, users can control who has access to specific files, reducing the risk of unauthorized modification or exposure.
Proper permission management is an essential cybersecurity practice for protecting sensitive organizational data.

