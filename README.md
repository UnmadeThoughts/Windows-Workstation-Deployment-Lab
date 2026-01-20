# Windows Workstation Deployment & IT Support Lab

## Overview

This lab documents the deployment and initial configuration of a Windows 10 workstation in a virtualized environment using Oracle VirtualBox.

The objective of this project is to demonstrate **core entry-level IT support and workstation deployment skills**, including operating system installation, system configuration, endpoint validation, and technical documentation.

This lab mirrors real-world responsibilities commonly performed in roles such as:

- IT Technician  
- Help Desk / Tier 1 Support  
- Desktop Support  
- IT Support Specialist  

---

## Skills Demonstrated

- Workstation deployment and OS provisioning  
- Virtual machine configuration and resource allocation  
- Windows 10 installation from ISO  
- Local administrator account creation  
- Privacy and initial system configuration  
- Device Manager inspection and driver validation  
- Windows Update management  
- Technical documentation and change tracking  

---

## Phase 1: Virtual Machine Creation

Screenshots documenting virtual machine configuration:

![VM Name & OS](screenshots/vm_name_os.png)
![VM Hardware](screenshots/vm_hardware.png)
![VM Hard Disk](screenshots/vm_harddisk.png)
![VM List](screenshots/vm_list.png)

**Configuration details:**
- Operating System: Windows 10 (64-bit)
- Memory: 4 GB RAM
- CPU: 2 processors
- Storage: 60 GB dynamically allocated disk
- Installation method: Manual (unattended install skipped)

This phase demonstrates proper preparation of a workstation prior to OS deployment.

---

## Phase 2: Windows Installation

Screenshots from the Windows setup process:

![Language Selection](screenshots/windows_setup_language.png)
![Activation / Product Key](screenshots/windows_activation_key.png)
![Version Selection](screenshots/windows_version_selection.png)
![License Agreement](screenshots/windows_license_agreement.png)
![Installation Type](screenshots/windows_installation_type.png)
![Partition Selection](screenshots/windows_partition_selection.png)
![Installation In Progress](screenshots/windows_install_in_progress.png)
![Initialization](screenshots/windows_initialization.png)

**Process performed:**
1. Booted system from Windows ISO
2. Configured regional and keyboard settings
3. Skipped activation (lab environment)
4. Selected Windows 10 Pro
5. Performed custom installation on unallocated disk
6. Completed OS installation and automatic reboot

This phase reflects standard workstation imaging and deployment workflows used in IT environments.

---

## Phase 3: Out-of-Box Experience (OOBE)

Screenshots from initial system configuration:

![Region Selection](screenshots/oobe_region.png)
![Keyboard Layout](screenshots/oobe_keyboard_layout.png)
![Account Type](screenshots/oobe_account_type.png)
![Offline Account](screenshots/oobe_offline.png)
![Local User Setup](screenshots/oobe_local_user_name.png)
![Security Questions](screenshots/oobe_security_question_1.png)
![Privacy Settings](screenshots/oobe_privacy.png)
![Desktop Ready](screenshots/desktop.png)

**Account configuration:**
- Local administrator account created for system access
- Offline account used (typical for enterprise environments)
- Security questions populated with placeholder values
- Privacy settings reviewed and configured

This phase demonstrates secure initial workstation setup prior to user handoff.

---

## Phase 4: Post-Deployment Validation

Screenshots demonstrating system verification:

![Device Manager Inspection](screenshots/device_manager.png)
![Windows Updates Applied](screenshots/windows_updates.png)

**Validation steps performed:**
- Verified all hardware devices installed correctly
- Checked for missing or failed drivers
- Installed all available Windows updates
- Confirmed system stability and readiness for use

This reflects standard IT post-imaging validation procedures.

---

## Why This Lab Matters

In real-world IT environments, technicians are responsible not only for installing systems, but for ensuring devices are **fully operational, secure, and properly documented** before delivery to end users.

This lab demonstrates the ability to:

- Follow structured deployment procedures  
- Validate system health after installation  
- Document technical work clearly and professionally  

These skills are foundational to entry-level IT and support roles.

---

## Future Expansion

This lab can be expanded to include:

- User account management
- Snapshot creation and rollback
- Simulated troubleshooting scenarios
- Software installation and removal
- Basic network configuration

---

