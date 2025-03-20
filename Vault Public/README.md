# Vault

This is a database system that Dominic Minnich and I created to move away from having large excel files that can get complicated due to data changing frequently or having too many different versions saved and not knowing which one to access. This provides our users with a user-friendly GUI that allows them to enter in devices, students, staff, repair details, and a built-in file explorer. All of the devices, students, and staff can be imported or exported with an Excel sheet.

Directory Structure

├── init.py
├── pycache/
├── app.py
├── backup_db.py
├── config.py
├── forms.py
├── models.py
├── README.md
├── routes.py
├── scheduler.py
├── static/
│ ├── styles.css
│ ├── bg12.png
│ ├── Logo.png
│ ├── Logo2.png
│ └── Logo3.png  
├── templates/
│ ├── add_device.html
│ ├── add_personnel.html
│ ├── add_repair.html
│ ├── add_staff.html
│ ├── base.html
│ ├── device_detail.html
│ ├── devices.html
│ ├── edit_device.html
│ ├── edit_personnel.html
│ ├── edit_repair.html
│ ├── edit_staff.html
│ ├── homepage.html
│ ├── import_devices.html
│ ├── import_personnel.html
│ ├── import_staff.html
│ ├── login.html
│ ├── personnel_detail.html
│ ├── personnels.html
│ ├── register.html
│ ├── repair_details.html
│ └── web_files.html

Overview

User Management: Users can be set to two different roles, admin or normal user based on the verification key used on registration.

Personnel Management: Add, edit, view, or delete personnel information.

Device Management: Add, edit, view, or delete device information.

Repair Management: view and manage repairs for devices, including status and repair record.

File Explorer: Custom made file explorer that allows for adding, deleting, and dragging and dropping files to upload.

Database Backup: The database is automatically backed up to ensure data is not lost.

Registration Page
