# SysAdmin Automation Scripts (Linux Shell Scripting Project)

This repository contains 5 Linux system administration tasks written as Shell Scripts.  
These tasks automate monitoring, reporting, and maintenance operations on a Linux/RHEL system.

---

## 🚀 Tasks Included

### **Task 1 – Disk Space Alert System (task1.sh)**
Monitors disk usage of the root partition `/`.  
If usage exceeds a threshold (default: 80%), it logs an alert and optionally sends an email.  
Helps prevent system crashes due to full disk.

---

### **Task 2 – Old File Archiver (task2.sh)**
Finds all files older than 30 days and moves them into an archive folder.  
Useful for cleaning logs, old backups, temporary files, and improving system storage.

---

### **Task 5 – Zombie Process Detector (task5.sh)**
Detects zombie processes (STAT = Z) and logs them for review.  
Helps identify buggy programs that fail to clean up child processes.

---

### **Task 10 – User Session Logger (task10.sh)**
Logs all currently logged-in users using the `who` command.  
Very useful for auditing and tracking user activity.

---

### **Task 44 – System Boot History Summary (task44.sh)**
Shows the system’s reboot history using `last reboot`.  
Helps track uptime, crashes, and unexpected restarts.

---
