# File Permissions in Linux

This project was completed as part of the **Google Cybersecurity Professional Certificate**.

## 📘 Project Overview
The main goal of this project was to review and manage file permissions in a Linux environment to ensure that team members only have access to files and directories they are authorized to use.

## 🔍 Tasks Performed
- Checked existing file and directory permissions using the `ls -la` command.
- Analyzed the Linux permission string (e.g., `-rw-rw-rw-`).
- Updated permissions using the `chmod` command to remove or grant access.
- Modified permissions for hidden files and directories.
- Documented all permission changes for future reference.

## 💻 Commands Used
```bash
ls -la
chmod o-w project_k.txt
chmod u-w,g-w,g+r .project_x.txt
chmod g-x,g-r,o-r,o-x projects
