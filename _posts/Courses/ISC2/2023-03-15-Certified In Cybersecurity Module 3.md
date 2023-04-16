---
title: ISC2 - Chapter 3 Access Control Concepts
categories: [Courses,ISC2]
tags: [isc2,certified,cybersecurity,course,courses, notes]     # TAG names should always be lowercase
---
Let’s take a more detailed look at the types of access control that every information security professional should be familiar with.  We will discuss both physical and logical controls and how they are combined to strengthen the overall security of an organization. 

## Module 1: Understand Access Control Concepts
### What is Security Control?
+ A **`control`** is a safeguard or countermeasure designed to preserve Confidentiality, Integrity and Availability of data. This, of course, is the CIA Triad.  
+ **`Access control`** involves limiting what objects can be available to what subjects according to what rules.
+ example of a control is a firewall

### Controls Overview
+ Access is based on three elements:  
#### Subjects
+ Generally an individual process or device causing information to flow among objects or change to the system state.
+ entity that requests access to our assets.
+ entity requesting access may be a user, a client, a process or a program
#### Objects
+ Passive information system related entity containing or receiving information.
+ anything that a subject attempts to access is referred to as an object.
+ object is a device, process, person, user, program, server, client or other entity that responds to a request for service.
+ objects do not contain their own access control logic.

+ **An Object**
  + Is a building, a computer, a file, a database, a printer or scanner, a server, a communications resource, a block of memory, an input/output port, a person, a software task, thread or process.
  + Is anything that provides service to a user.
  + Is Passive
  + Responds to requests
  + maybe have a classification

#### Rules
+ An instruction developed to allow oe deny access to a system by comparing the validated identity of the subject to an access control list.
+ compare multiple attributes to determine appropriate access
+ allows access to object
+ define how much access is allowed
+ deny access to an object
+ apply time-based access.

### Control Assessments
+ Risk reduction depends on the effectiveness of the control

### Defense in Dearth
+ Layered Defense
  + The Use of multiple controls arranged in series to provide several consecutive controls to protect an asset; also called defense in depth.

+ Defense in depth
  + Information security strategy integrating people, technology and operations capabilities to establish variable barriers across multiple layers and missions of the organization.

+ Defense in depth should be implemented to prevent or deter a cyber attack, but it cannot guarantee that an attack will not occur.

### Example
+ Consider the multiple layers of access required to get to the actual data in a data center. 
+ First, a lock on the door provides a physical barrier to access the data storage devices.
+ Second, a technical access rule prevents access to the data via the network.
+ Finally, a policy, or administrative control defines the rules that assign access to authorized individuals.

### Principle of Least Privilege
+ Principle that users and programs should have only have the minimum privileges necessary to complete complete their tasks

### Example
+ only individuals working in billing will be allowed to view consumer financial data, and even fewer individuals will have the authority to change or delete that data.
+ This maintains confidentiality and integrity while also allowing availability by providing administrative access with an appropriate password or sign-on that proves the user has the appropriate permissions to access that data.  

### Privileged Access Management
+ Privileged Accounts
  + account with approved authorization of a privileged user.

+  These accounts have elevated privilege based and are used by many different classes.
   +  Systems administrators | who have the principal responsibilities for operating systems, applications deployment and performance management. 
   +  Help desk or IT support staff | who often need to view or manipulate endpoints, servers and applications platforms by using privileged or restricted operations. 
   +  Security analysts | who may require rapid access to the entire IT infrastructure, systems, endpoints and data environment of the organization.

+  **Typical measures used for moderating the potential for elevated risks from misuse or abuse of privileged accounts include the following:** 
   +  More extensive and detailed `logging` than regular user accounts.
   +  More stringent access control than regular user accounts.
   +  Deeper trust verification than regular user accounts.
   +  More auditing than regular user accounts.

### Segregation of Duties 
+ The practice of ensuring that an organizational process cannot be completed by a single person
+ Segregation of duties breaks the transaction into separate parts and requires a different person to execute each part of the transaction.
+ Another implementation of segregation of duties is dual control.

### Two-Person Integrity 
+ The two-person rule is a security strategy that requires a minimum of two people to be in an area together, making it impossible for a person to be in the area alone.

### Authorized Versus Unauthorized Personnel
+ Subjects are authorized access to objects after they have been authenticated.

### Roles and Permissions
+ Which role would get Regular Account permissions?
Part-time Employee | Remote Employee | Full-time Employee | Temporary Employee | Manager/Team Lead

### Privileged Access Management
+ A Privileged User Account:
  + Has access to interact directly with servers and other infrastructure devices.
  + Should require the use of MFA.
  + Uses the most stringent access control.
  + Has the highest level of logging associated with actions.
  + Often has the ability to create users and assign permissions.

### The Benefits Of Multiple Control
+ physical | Technical | Administrative Control

## Module 2: Understand Physical Access Controls
### What Are Physical Security Controls? 
+ **`Physical access controls`**
  + Controls implemented through a tangible mechanism. Like Walls, fences, guards

+ Physical access controls are necessary to protect the assets of a company, including its most important asset, people.

### Why Have Physical Security Controls?
+ prevent unauthorized individuals from entering a physical site, such as a workplace.
+ protect not only physical assets such as computers from being stolen, but also to protect the health and safety of the personnel inside. 

### Types of Physical Access Controls
+ **`Badge Systems and Gate Entry`**
  + controls for human traffic are often done with technologies such as turnstiles, mantraps and remotely or system-controlled door locks.
  + A range of card types allow the system to be used in a variety of environments. These cards include:
    + Bar Code
    + Magnetic Stripe
    + Proximity
    + Smart
    + Hybrid

+ **`Environmental Design`**
  + **`Crime Prevention through Environmental Design (CPTED)`**
    + architectural approach to the design of building and spaces which emphasizes passive features to reduce the likelihood of criminal activity.
    + CPTED provides direction to solve the challenges of crime with organizational (people), mechanical (technology and hardware) and natural design (architectural and circulation flow) methods.

+ **`Biometrics`**
  + To authenticate a user’s identity, biometrics uses characteristics unique to the individual seeking access. A biometric authentication solution entails two processes.
    + Enrollment | during the enrollment process, the user’s registered biometric code is either stored in a system or on a smart card that is kept by the user.
    + Verification | during the verification process, the user presents their biometric data to the system so that the biometric data can be compared with the stored biometric code.

  + Biometrics takes two primary forms, physiological and behavioral.
    + **`Physiological systems`**
      + measure the characteristics of a person such as a fingerprint, iris scan (the colored portion around the outside of the pupil in the eye), retinal scan (the pattern of blood vessels in the back of the eye), palm scan and venous scans that look for the flow of blood through the veins in the palm.

    + **`Behavioral systems`** 
      + measure how a person acts by measuring voiceprints, signature dynamics and keystroke dynamics.

  + Biometric systems are considered highly accurate, but they can be expensive to implement and maintain because of the cost of purchasing equipment and registering all users.

### Monitoring
+ physical access controls and monitoring personnel and equipment entering and leaving as well as auditing/logging all physical events are primary elements in maintaining overall organizational security. 

#### Monitoring Examples
+ **`Cameras`**
+ **`Alarm Systems`**
+ **`Logs`**
  + A log is a record of events that have occurred. Physical security logs are essential to support business requirements. 

+ **`Security Guards`**

### Physical Access Controls
+ Which of the following is NOT a source of biometric data?
  + `Badges`
  + Badges are not a source of biometric data. All other options presented are considered unique identifiers that are commonly accepted by biometric authentication systems.

### Users’ Credentials
+ When using physical access control tokens, how are the user’s credentials read so they can be transmitted to a logical access control system?
  + Swiped (magnetic stripe) | Inserted (smart card or proximity) | Placed on or near a reader (proximity)
  + Swiped, inserted and placed on or near a reader are all ways the user’s credentials are read so they can be transmitted to a logical access control system.

## Module 3 : Understand Logical Access Controls
### What are Logical Access Controls?
+ logical access controls are electronic methods that limit someone from getting access to systems, and sometimes even to tangible assets or areas.
+ Types of logical access controls include:
  + Passwords
  + Biometrics
  + Badge/token

### Discretionary Access Control (DAC)
+ **`Discretionary access control (DAC)`**
  + specific type of access control policy that is enforced over all subjects and objects in an information system.
  + **policy specifies that a subject who has been granted access to information can do one or more of the following:**
    + Pass the information to other subjects or objects 
    + Grant its privileges to other subjects
    + Change security attributes on subjects, objects, information systems or system components
    + Choose the security attributes to be associated with newly created or revised objects
    + Change the rules governing access control

+ Most information systems in the world are DAC systems
+ Rule-based access control systems are usually a form of DAC. 
+ Discretionary access control systems allow users to establish or change these permissions on files they create or otherwise have ownership of.

### DAC in the Workplace
+ In a DAC system, a user who has access to a file is able to share that file with or pass it to someone else.
+ It is at the discretion of the asset owner whether to grant or revoke access for a user.

### Mandatory Access Control (MAC)
+ access control that erquires the system itself to amanage access controls in accordance with the organizations security policies.
+ the organization assigns a subset of total privileges for a subset of objects, such that the subject is constrained from doing any of the following:
  + Passing the information to unauthorized subjects or objects
  + Granting its privileges to other subjects 
  + Changing one or more security attributes on subjects, objects, the information system or system components 
  + Choosing the security attributes to be associated with newly created or modified objects
  + Changing the rules governing access control 

### Role-Based Access Control (RBAC)
+ An access control system that sets up users permissions base on roles
+ Each role represents users with similar or identical permissions

### RBAC in the Workplace
+ provides each worker privileges based on what role they have in the organization. 
+ Monitoring these role-based permissions is important
+ It is recommended that standard roles are established, and new users are created based on those standards rather than an actual user. 


