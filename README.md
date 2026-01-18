# IT Technician Lab: Windows 10 VM Installation

## Overview
This lab demonstrates deploying a Windows 10 workstation in a virtualized environment (Oracle VirtualBox) for IT Technician practice.  
It shows core skills including:

- Virtual machine creation and configuration
- Windows OS installation from ISO
- Local admin account setup
- Privacy configuration
- Device inspection and system maintenance

---

## Phase 1: Virtual Machine Creation

Screenshots of VM settings:

![VM Name & OS](screenshots/vm_name_os.png)
![VM Hardware](screenshots/vm_hardware.png)
![VM Hard Disk](screenshots/vm_harddisk.png)
![VM List](screenshots/vm_list.png)

> VM configuration:
> - Windows 10 (64-bit)
> - 4 GB RAM, 2 CPU cores
> - 60 GB dynamically allocated disk
> - Manual installation (unattended install skipped)

---

## Phase 2: Windows Setup

Screenshots from the Windows installation process:

![Language Selection](screenshots/windows_setup_language.png)
![Activation / Product Key](screenshots/windows_activation_key.png)
![Version Selection](screenshots/windows_version_selection.png)
![License Agreement](screenshots/windows_license_agreement.png)
![Installation Type](screenshots/windows_installation_type.png)
![Partition Selection](screenshots/windows_partition_selection.png)
![Installation In Progress](screenshots/windows_install_in_progress.png)
![Initialization](screenshots/windows_initialization.png)

> Steps performed:
> 1. Started VM, booted from ISO
> 2. Selected language, time, and keyboard
> 3. Skipped product key (lab-only)
> 4. Chose Windows 10 Pro
> 5. Accepted license
> 6. Custom installation on unallocated disk
> 7. Let Windows install and restart automatically

---

## Phase 3: OOBE (Out-of-Box Experience)

Screenshots from account setup and privacy configuration:

![Region Selection](screenshots/oobe_region.png)
![Keyboard Layout](screenshots/oobe_keyboard_layout.png)
![Account Type](screenshots/oobe_account_type.png)
![Offline Account](screenshots/oobe_offline.png)
![Local User Setup](screenshots/oobe_local_user_name.png)
![Security Questions](screenshots/oobe_security_question_1.png) <!-- Can repeat 2 & 3 if desired -->
![Privacy Settings](screenshots/oobe_privacy.png)
![Desktop Ready](screenshots/desktop.png)

> Local admin account:
> - Username: `ITLabAdmin`
> - Password: `Password123!` (lab only)
> - Security questions: fake answers (lab environment)
> 
> PC name can be customized as desired, current name is for lab documentation purposes only

---

## Phase 4: IT Technician Tasks

Screenshots demonstrating routine IT Technician tasks:

![Device Manager Inspection](screenshots/device_manager.png)
![Windows Updates Applied](screenshots/windows_updates.png)

> Tasks performed:
> - Verified all devices in Device Manager
> - Installed all Windows updates
> - Confirmed VM is operational and ready for troubleshooting
> 
> Additional tasks such as snapshots and simulated troubleshooting can be used to expand this lab in the future

---

## Skills Demonstrated

- Virtual Machine configuration and deployment
- Windows 10 installation and setup
- Local admin account creation and privacy configuration
- Device inspection and system maintenance
- Documentation for portfolio / hiring purposes
