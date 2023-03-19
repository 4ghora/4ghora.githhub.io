---
title: Security Plus Chapter 5 - Hardening
categories: [Comptia,Security Plus, Chapter 4]
tags: [comptia,basics,security,notes]     # TAG names should always be lowercase
---

**Act of configuring an operating system securely by updating it, creating rules and policies to govern it, and removing unnecessary applications and services**

## Unnecessary Apps & Services

### Least Functionality
+ Process of configuring workstation or server to only provide essential applications and services required by users.
+ administrators should restrict un-needed applications, services and ports.
+ uninstall un-needed applications
+ utilize a secure baseline image when adding new computers.

#### SCCM (Microsoft's System Center Configuration Management) 
+ allows admins to mange large amounts of software across the network.

## Restricting Applications
+ **Application Whitelist**
  + Only applications that are on the list are allowed to be run by the operating system while all other applications are blocked.

+ **Application Blacklist**
  + Any application placed on the lst will be prevented from running all the others will be permitted to run.

## Disabling Services in Windows Linux and OSx
+ service are like applications that run in the backgrounf and it performs tasks like printspooler.
+ Any service that unneeded should be disabled

### Windows
+ start -> services -> select service -> stop
+ command
```terminal
sc stop <service name>
```

+ Another option
```terminal
net stop <service name>
```

### Linus and OSx
+ Find Pid of service using `top` command.
+ Use kill command to stop process using pid
```terminal
kill pid <pid number>
```

## Trusted Operating Systems
+ An operating system that meets the requirements set forth by government and multilevel security.
+ Manufacturer must provide regular updates and patches in order to maintain its security.

+ **Trusted Operating Systems**
  + `Windows 7 (and newer)`
  + `Mac OS X 10.6 (and newer)`
  + `FreeBSD (trusted BSD)`
  + `Red Hat Enterprise Server`

## Updates And Patches
### Patches
+ A single problem-fixing piece of software for an operating system or application
  + requires a reboot.

### Hotfix
+ A single problem-fixing piece of software for an operating system or application
  + hotfix can be installed with rebooting the system.

### Categories Of Updates
1. **Security updates**
   + Software code that is issued for a product-specific security related vulnerability
2. **Critical Update**
   + Software code for a specific problem addressing a critical, non-security bug in the software.
3. **Service Pack**
   + A tested, cumulative grouping of patches, hotfixes, security updates, critical updates, and possibly some feature or design changes.
4. **Windows Update**
   + Recommended update to fix a noncritical problem that users have found, as well as to provide additional features or capabilities.
5. **Driver Updates**
   + Updates device driver to fix a security issue or add a feature to support piece of hardware.
   + Windows 10 uses the windows update program(wuapp.exe) to manage updates

## Patch Management
+ process of planning, testing, implementing, and auditing of software patches.
+ patches can bugs in them too
+ **4 Steps To Patch Management**
  1. Planning
     + Verify it is compatible with your systems and plan for how you will test and deploy it.
  2. Testing 
     + Always test a patch prior to automating its deployment.
  3. Implementing
     + Manually or automatically deploy the patch to all your clients to implement it
     + Microsoft Provides a tool(Microsoft System Center Configuration Manager)
     + Larger organizations centerally manage updates through an update server to maintain full control over the process and patches. 
  4. Auditing
     + important to audit clients status after patch deployment.
     + to avoid unexpected failures.

+ To disable windows updates disable wuauserv service.
+ `Linux and OSx` also have built in management tools.
  + redhat linux uses a packet manager to deploy RPMs or packages of patches.

## Group Policies
+ A set of rules that can be applied to a set of users or computers accounts within the operating systems.
+ Access the group editor by opening the run print and enter gpedit.
+ Each policy acts as security template that apply set of rules to different users. Policies Examples
  + password Complexity Requirements
  + Account Lockout Policies
  + Software Restrictions
  + Application Restrictions

+ Active Directory domain controllers have a more advanced group policy editor
+ Common to create `Security Templates`
  + Predefined rules based on organizations policies

### Security Template
+ A group of policies that can be loaded through one procedure
+ Group Policy Objectives(GPOs) aid the hardening of the operating systems

### Baselining
+ Process of measuring changes into network, hardware, and software environment.
+ establishes what is normal so you can find deviations

## File Systems And Hard drives
+  Security of the systems depends on its file system

### Types
+ **Windows**
  + **NTFS**
    + New Technology File System is default file system format for windows and is more secure because it supports logging, encryption, larger partition sizes, and larger file sizes than FAT32
+ Linux Systems should use `ext4`
+ OSx Should use the `APFS`

### Hard Drive Will Fail
+ To Postpone the failure and ease the recovery
  1. Remove Temporary files 
  2. Periodic System File Checks
  3. defragment your disk drive
  4. Backup your data
  5. Use and practice restoration techniques.
