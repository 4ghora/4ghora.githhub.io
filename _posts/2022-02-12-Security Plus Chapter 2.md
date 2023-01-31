---
title: Security Plus Chapter 2 - Malwares
categories: [Comptia,Security Plus, Chapter 2]
tags: [comptia,basics,security,notes]     # TAG names should always be lowercase
---
## 1. What Is Malware And Types
	
### Malware:
	
Software's designed to infiltrate a computer system and possibly damaged it without the users knowledge or consent.
	
### Types Of Malware:
	
1. **Worm**: Malicious software, like a virus, but it is able to replicate itself without user interaction. worms self-replicate and spread without a user's consent or action. Worms cause disruption to normal network traffic and computing activities.
	    
2. **Trojan Horse**: Malicious software that is designed as a piece of harmless or desirable software. Trojans perform desired functions as well as malicious functions.
	    
3. **Remote Access Trojan**: Provides the attackers with remote control of a victim computer and is the most commonly used type of trojan.
	    
4. **Ransomware**: Malware that restricts access to a victim's computer system until a ransom is received. Ransomware uses vulnerability in your software to gain access anf then encrypts your files.
	    
5. **Spyware**: Malware that secretly gather's information about the user without their consent.
	    
6. **Grayware**: software that isn't good nor malicious, it tends to behave improperly without any serious consequences. AKA: Jokeware. Like: Crazy Mouse
	    
7. **RootKits**: Software designed to gain administrative level control over a system without destruction. 
   DLL injection is commonly used by rootkits to maintain their perspective control.
	
	**DLL injection**: Malicious code is inserted into a running process on a windows process on a windows machine by taking advantage of Dynamic like libraries that are loaded at runtime.
	            
	**Driver Manipulation**: An attacker that relies on compromising.
	            
	**Shim**: Software which is placed between 2 components to intercept calls and redirects them.
	            
	Rootkits are activated before booting the operating systems and are difficult to detect.
	
8. **Spam**: Activities that abuse electronic messaging systems most commonly through email. Spammers often exploit a company's open mail relays to send their message's.
	        SPIM: Spam Over Instant Messaging.
	
## 2. Virus
	
### What Is A Virus:
A computer virus is a type of computer program that, when executed, replicates itself by modifying other computer programs and inserting its own code. When this replication succeeds, the affected areas are then said to be "infected" with a computer virus. Virus require a user action i order to reproduce and spread.
	
### Types Of Virus: 
1. **Boot Sector**: These virus are stored in the first sector of a hard drive and are loaded into memory upon boot. Very hard to detect because it installs during the booting of the system. system's antivirus only starts after the booting of the system. To detect these kind of viruses use antivirus which looks specifically looks for boot sector viruses. Modern 3rd party antivirus are capable enough nowadays.
	 
2. **Macro**: Virus embedded into a document and is executed when the document is opened by the users.
	
3. **programs**: infect a executable or application.
	    
4. **Multipartite**: This virus combines with boot and programs virus to first attach itself to the boot sector and system files before attacking other files on the computer.
	    
5. **Encrypted**: This virus uses cypher to encrypt the contents of itself to avoid detection from any antivirus software.
	    
6. **Polymorphic**: Advanced version of encrypted virus that changes itself every time it is executed by altering the decryption module to avoid detection.
	    
7. **Metamorphic**: Virus which is able to rewrite itself entirely before it attempts to infect a file.(Advanced Version of Polymorphic Virus)
	    
8. **Stealth**: Technique by which virus protects itself. Uses Encryption, Metamorphic and
	        Polymorphic techniques.
	    
9. **Armored**: Armored virus have a layer of protection to confuse a programmer or person
	        analyzing it.
	    
10. **Hoax**:   Not a virus, Social Engineering technique.
	
## 3. Malware Injection
	
### Malware Injection:

1. **Threat Vector**: Method used by an attack to access a victim's machine. example: Unpatched software. Infected USB Drive etc.
	    
2. **Attack Vector**: Method used by an attacker to gain access to a victims machine in order to infect it with malware.
	
### Common Delivery Methods:
1. **Botnets & Zombies**:
    
    **Botnet**: A collection of compromised computer's under the control of a master node. Botnets can be utilized in other processor intensive functions and activities.
	
	**Zombies**: Node which is being used by mater node in order to utilize the computing/processing power of a system for DDoS or Mining etc.
	
2. **Active Interception**: Occurs when a computer is placed between the sender and receiver and is able to capture capture or modify the traffic between them.
	    
3. **Privilege Escalation**: Occurs when you are able to exploit a design flow or bug in a system to gain access to resource that a normal user isn't able to access.
	    
4. **Backdoor**: It is used to bypass normal security and authentication functions. RAT is placed by an attacker to maintain persistent access.
	    
5. **Logic Bomb**: Malicious code that has been inserted inside a program and will execute only when certain condition have been met.Logic Bombs and Easter Eggs should be used accordingly to secure coding standards.
	
### Symptoms Of Injections:
1. Slow Processing                 		
2. New Files & Folder have been created or files and folder are missing or corrupted.
3. Frequent System Crashing
4. Frequent BSOD (Blue Screen Od Death)
5. Strange Noises Occurs
6. Hard Disks, files and applications not accessible anymore
7. Display Looks Strange
8. Unusual Error Messages
9. Unsuccessful Virus Scans
10. Jumbled Printouts
11. System Restore not Functioning. 		
12. New unusual icon's appearing & disappearing.
	    
	-> Malware hiding technique: Double file extension are being displayed, such as textfile.txt.exe
	-> Computer might have been infected if it being to act strangely.
	    
## 4. Defense's
	
### Removing Malware:
1. Scan the system
2. Take backup of the current system.
3. Identify symptoms of a malware injection.
4. Quarantine the infected system. (disconnect the system from the network, so that malware will not spread in the network)
5. Disable system restore (if using windows system)
6. Remediate the injected systems.
7. Schedule automatic updates and malware scans.
8. Re-Enable System Restore and create a new restore point.
9. Provide end user security awareness training.
	
	-> If a boot sector virus is suspected reboot the computer from and external device and scan it or remove the hard drive from the computer & plug it to a different clean system as a secondary drive & then scan the hard drive.
	
### Preventing Malware From Injection Systems:
1. **Viruses**: Use Antivirus software.
2. **Worms, Trojans & Ransomware** are best detected with anti-malware solution(Regularly Update Anti-Malware Software)
3. **Spyware**: Use Antivirus And Brain.
4. **Rootkits**: Scanners can't detect a file containing a rootkit before it is installed. Removal of a rootkit is difficult and the best practice is to re-image the machine.
5. **SPAM**: Use filter's & SPAM security.
	-> Verify your email server's aren't configured as a open mail relay or SMTP open relay
	    -> Remove email address from website.
	    -> Use whitelist and blacklists. (Who can and cannot send you information).
	    -> Train and educate end user.
	
### Main Points:
1. Let your anti-malware software update and scan your computer system automatically.
2. Update and patch the operating system and applications regularly.
3. Educate and train end users on safe internet surfing practices.
	
