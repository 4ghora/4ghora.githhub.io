---
title: Security Plus Chapter 3 - Security Applications And Devices
categories: [Comptia,Security Plus, Chapter 3]
tags: [comptia,basics,security,notes,firewall,os,operaing,systems,system,]     # TAG names should always be lowercase
---

## 1. Software Firewalls
	
### Software Firewalls: 
+ Personal firewalls AKA Host Based Firewalls: Software applications that protects a single computer from an unwanted internet traffic. These works by applying set of rules on the traffic that is attempting t come into or go out of protected system.
	
### Firewalls In Different Systems:
1. **Windows**: Windows Firewall
	
+ There are 2 types of windows firewalls:
  + Basic Version(Can be found in Control Panel)
  + Windows Firewall with advanced security(can be accessed by tying wf.msc)
	
1. **MacOs X**: PF & IPFW:
+ PF: Packet Filter(Found in osX 10.10 or higher)
+ IPFW: Internet Protocol Firewall
+ Both can be found in free bsd systems.
	
2. **Linux**:   Iptables
	
## 2. Intrusion Detection Systems
	
### IDS -> Intrusion Detection Systems:
+ Devices or software applications that maintain a system or network and analyzes the data passing through it in order to identify an incident or attack.
	    
### 2 Types Of IDS:
1. **HIDS(Host Based IDS)**: Software installed on a system or server & will log everything on a system identify the suspicious things or programs.
	        
2. **NIDS(Network Based IDS)**: Hardware installed in a network and all the traffic goes through switch will be copied and sent to the NIDS will log if something suspicious & alert on it.
	
### How IDS Detect Intrusion:
#### 3 Ways Of Detection:
+ **Signature-Based**: A specific string of bytes of string triggers an alert. This Method will search for a specific string of bytes which trigger an alert.
	        
+ **Policy-Based**: Relies on specific declaration of the security policy. (i.e. No Telnet Authorization)
	
+ **Anomaly-Based**: Analyzes the current traffic against an established baseline and triggers an alert if outside the statistical average.
	
### 4 Types of alerts:
1. **True Positive**: Malicious Activity is identified as an attack.
2. **True Negative**: Legitimate activity is identified a legitimate activity.
3. **False Positive**: Legitimate Activity is identified as an attack.
4. **False Negative**: Malicious Activity is identified an legitimate attack.
	    
	+ IDS can only alert and log suspicious activity.
	
    + IPS(Intrusion Prevention System) can also stop malicious activity fromm being executed.
	
    + HIDS logs are used to recrate the events after an attack as occurred.
	
## 3. Blockers And DLP's
	
### Pop Up Blocker:

+ Most Web browsers have the ability to block javascript created pop-ups.
	
### Content Filters:
+ Blocking of external files containing javascript images and web-pages from loading in a browser.
	
### Data Loss Prevention(DLP):
+ Monitor's the data of a system while in use, in transit or at the rest to detect attempts to steal the data.
	
### End Point DLP System:
+ Software based client that monitor's that data in use on a computer and can stop a file transfer or alert an admin of the occurrence.
	
### Network DLP System:
+ Software or hardware based solution that is installed on the perimeter of the network to detect data in transit.
	
### Storage DLP System:
+ Software installed on system/server in data-center to inspect the data at rest. 
	
## 4. Securing Bios
	
### BIOS(Basic Input And Output System):
+ Firmware that provide the computer instructions for how to accept input and send output.
	
### UEFI(Unified Extensible Firmware Interface)
		 
	
### Securing:
1. Flash the BIOS. 		                 
2. Disable the external ports and devices.
3. Use a BIOS Password 		             
4. Configure the BIOS boot order. 
5. Enable the secure boot option.		
	
	
	
	
	
	
	
	
	
