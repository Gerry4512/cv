# cv

# 🖥️ RHEL Home Lab Project

This repository documents my **Red Hat Enterprise Linux (RHEL) home lab**, where I set up and configured core sysadmin tasks.  
It covers **user management, storage, automation, networking, services, and monitoring**

---

## 🔹 1. System Basics & Users
- Created and managed local users and groups
- Configured password policies and permissions

![System Update](./uptdate%20system.png)  
![Users](./Users.png)  
![Alice Permissions](./Alice%20Permissions.png)  
![Home Files](./home%20files.png)  
![Login Definitions](./login%20defs.png)  

---

## 🔹 2. Storage Management
- Added new disk and created standard partitions
- Configured **Logical Volume Management (LVM)** for flexible storage

![New Disk Added](./nvmedisk%20added.png)  
![LVM Created](./Logical%20Volume%20Management%20created.png)  
![LVM Alternative](./Logical_VOlume_Management_created.png)  

---

## 🔹 3. Task Automation (Bash & Cron)
- Automated backups and health checks with Bash scripting
- Scheduled tasks using `cron`

![Backup Script](./backup_bash.png)  
![Backup Test](./backup_test.png)  
![Weekly Health Report](./bash_weekly_health_report.png)  
![Weekly Report 2](./weekly_health_report2.png)  
![Crontab Info](./crontab_info.png)  
![Disk Free Info](./dfh_info.png)  
![Disk Mount Status](./dms_test.png)  
![Service Monitoring](./service_monitoring_bash.png)  

---

## 🔹 4. Networking & Services
- Configured firewall rules with **firewalld**
- Set up and managed **Apache (httpd)** and **Nginx** web servers
- Configured **NFS** for Linux file sharing
- Configured **Samba** for Windows/Linux file sharing
- Set up **DNS (BIND)** server

![Firewall Rules](./firewalld_list_info.png)  
![Apache Installed](./httpd%20installed.png)  
![Apache Enabled](./httpd%20enabled-active.png)  
![Apache Website](./httpd(apache)_website.png)  
![Nginx Installed](./nginx%20installation.png)  
![Nginx Enabled](./nginx%20enabled-active.png)  
![Nginx Port Changed](./nginx%20port%20changed.png)  
![Nginx Website](./nginx_website.png)  
![NFS Setup](./NFS_setup.png)  
![Samba Created](./samba_created.png)  
![Samba Test](./samba_test.png)  
![DNS Config](./named_config(DNS).png)  

---

## 🔹 5. Monitoring & Security
- Installed and configured **Nagios** for system and service monitoring

![Nagios Setup](./nagios_setup.png)  

---

## 📌 Skills Demonstrated
- Linux user & permission management
- Storage configuration (LVM, partitions)
- Automation with Bash & Cron
- Network services (Apache, Nginx, DNS, NFS, Samba)
- Security hardening (firewalld, SELinux basics)
- Monitoring with Nagios

---

