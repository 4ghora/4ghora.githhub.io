---
title: ISC2 - Chapter 2 Incident Response, Business Continuity and Disaster Recovery Concepts
categories: [Courses,ISC2]
tags: [isc2,certified,cybersecurity,course,courses, notes]     # TAG names should always be lowercase
---
This chapter focuses on the availability part of the CIA triad and the importance of maintaining availability of both human and system resources. These are usually accomplished through the implementation of Incident Response, Business Continuity (BC) and Disaster Recovery (DR) plans.

## Module 1: Understand Incident Response
### Incident Terminology
+ **Breach**
  + The loss of control, compromise, unauthorized disclosure, unauthorized acquisition, or any similar occurrence where: a person other than an authorized user accesses or potentially accesses personally identifiable information; or an authorized user accesses personally identifiable information for other than an authorized purpose.

+ **Event**
  + Any observable occurrence in a network or system.

+ **Exploit**
  + A particular attack. It is named this way because these attacks exploit system vulnerabilities.

+ **Incident**
  + An event that actually or potentially jeopardizes the confidentiality, integrity or availability of an information system or the information the system processes, stores or transmits.

+ **Intrusion**
  + A security event, or combination of events, that constitutes a deliberate security incident in which an intruder gains, or attempts to gain, access to a system or system resource without authorization.

+ **Threat**
  + Any circumstance or event with the potential to adversely impact organizational operations (including mission, functions, image or reputation), organizational assets, individuals, other organizations or the nation through an information system via unauthorized access, destruction, disclosure, modification of information and/or denial of service.

+ **Vulnerability**
  + Weakness in an information system, system security procedures, internal controls or implementation that could be exploited by a threat source.

+ **Zero Day**
  + A previously unknown system vulnerability with the potential of exploitation without risk of detection or prevention because it does not, in general, fit recognized patterns, signatures or methods.

### The Goal of Incident Response

+ organization must be prepared for incidents.
+ adverse events : events with negative consequences 
+ primary goal of incident management is to be prepared
+ Preparation requires having a policy and a response plan
+ if the event has the potential to disrupt the business’s mission, then it is called an incident.
+ incident response plan 
  + documentation of predetermined set of instruction or procedures to detect respond to and limit consequences of malicious cyber attack against an organization


+ incident response process is aimed at reducing the impact of an incident so the organization
+ business continuity management (BCM)

### Components of the Incident Response Plan
+ incident response policy = incident response plan
+ **`Preperation`**
  + Develop a policy approved by management
  + Identify critical data and systems, single points of failure.
  + Train staff on incident response.
  + Implement an incident response team.
  + Practice Incident Identification
  + Identify Roles and Responsibilities.
  + Plan the coordination of communication between stakeholders.

+ **`Detection and Analysis`**
  + Monitor all possible attack vectors.
  + Analyze incident using known data and threat intelligence.
  + Prioritize incident response.
  + Standardize incident documentation.

+ **`Containment`**
  + Gather evidence.
  + Choose an appropriate containment strategy.
  + Identify the attacker.
  + Isolate the attack.

+ **`Post-Incident Activity`**
  + Identify evidence that may need to be retained.
  + Document lessons learned.

  **Retrospective**
  + Preparation
  + Detection and Analysis
  + Containment, Eradication and Recovery
  + Post-incident Activity

### 

### Incident Detection Terms
+ Breach : The loss of control, compromise, unauthorized disclosure, unauthorized acquisition, or any similar occurrence where: a person other than an authorized user accesses or potentially accesses personally identifiable information; or an authorized user accesses personally identify able information for other than an authorized purpose. 
+ Incident : An event that actually jeopardizes the confidentiality, integrity or availability of system or the information the system processes or stores.
+ Exploit : A particular attack. It is named this way because these attacks exploit system vulnerabilities.
+ Intrusion : A security event, or combination of events, that constitutes a deliberate security incident in which an intruder gains, or attempts to gain, access to a system or system resource without authorization.
+ Vulnerability : weakness in an information system, security procedures, internal control, or implementation that could be exploited or triggered by a source.
+ Threat : Any circumstance/event with the poten tial to adversely impact organizationai operations (incuding mission, functio ns, image or reputation), organizationaf assets, individuals, other organizations or the nation through an information system via unauthorized access, destruction, disclosure, mo dification of information andor denialof service.
+ Event : Any observable occurrence in a network or system.

### Incident Response Team
+ Security Operations Center : A centralized organizational function fulfilled by an information security team that monitors detects analyzes events on the network to prevent and resolve issues before the result in business disruptions.
+ organizational need to establish a Security Operations Center (SOC)
+ **Incident Response Team members include the following**
  + Representative(s) of senior management
  + Information security professionals
  + Legal representatives
  + Public affairs/communications representatives
  + Engineering representatives (system and network)

+ **computer incident response teams (CIRTs)** or **computer security incident response teams (CSIRTs)**. 
+ Response team has four primary responsibilities:
  + Determine the amount and scope of damage caused by the incident.
  + Determine whether any confidential information was compromised during the incident.
  + Implement any necessary recovery procedures to restore security and recover from incident-related damage.
  + Supervise the implementation of any additional security measures necessary to improve security and prevent recurrence of the incident.

## Module 2: Understand Business Continuity (BC)
### The Importance of Business Continuity
+ intent of a business continuity plan is to sustain business operations while recovering from a significant disruption.
+ Organizations will go through their procedures and checklists to make sure they know exactly who is responsible for which action.

### Components of a Business Continuity Plan
+ **Business continuity planning (BCP)**
  + proactive development of procedures to restore business operations after a disaster or other significant disruption to the organization.

+ in order to safeguard the confidentiality, integrity and availability of information, the technology must align with the business needs.

#### common components of a comprehensive business continuity plan:
+ List of the BCP team members, including multiple contact methods and backup members
+ Immediate response procedures and checklists
+ Notification systems and call trees for alerting personnel that the BCP is being enacted
+ Guidance for management, including designation of authority for specific managers
+ How/when to enact the plan
+ Contact numbers for critical members of the supply chain

### Common Business Continuity Components
+ Is the following statement true or false? An important component of the business continuity plan details how and when the plan is enacted.
  + **`True`**
  + It's important to include when and how the plan will be used.

### Know Your Business Continuity Plan
+ How often should an organization test its business continuity plan (BCP)?
  + **`Routinely`**
  + Each individual organization must determine how often to test its BCP, but it should be tested at predefined intervals as well as when significant changes happen within the business environment. 

### Business Continuity in Action
+ **Business Impact Analysis(BIA)**
  + an analysis of an information systems requirements, functions, and interdependencies used to characterize system contingency requirements and priorities in the event of significant disruptions.

## Module 3: Understand Disaster Recovery (DR)
### The Goal of Disaster Recovery
+ **`Disaster Recovery`**
  + activities necessary to restore IT and communications services to an organization during and after ana outage disruption or disturbance of any kind or scale.

+ **`Disaster Recovery Plan(DRP)`**
  + processes, policies and procedures related to preparing for recovery or continuation of an organization's critical business functions, technology infrastructure, systems and applications after the organization experiences disaster.

+ Disaster recovery refers specifically to restoring the information technology and communications services and systems needed by an organization, both during the period of disruption caused by any event and during restoration of normal services.
+ **`Business Continuity`** planning is about maintaining critical business functions, **`Disaster Recovery`** planning is about restoring IT and communications back to full operations after a disruption.

### Components of a Disaster Recovery Plan
+ following list includes various types of documents worth considering :
  + Executive summary providing a high-level overview of the plan
  + Department-specific plans
  + Technical guides for IT personnel responsible for implementing and maintaining critical backup systems
  + Full copies of the plan for critical disaster recovery team members
  + Checklists for certain individuals:
    1. Critical disaster recovery team members will have checklists to help guide their actions amid the chaotic atmosphere of a disaster.
    2. IT personnel will have technical guides helping them get the alternate sites up and running
    3. Managers and public relations personnel will have simple-to-follow, high-level documents to help them communicate the issue accurately without requiring input from team members who are busy working on the recovery. 


### Components of Disaster Recovery
+ Which of the following is unlikely to be a member of the disaster recovery team?
+ Executive Management | Public Relations | Billing Clerk | IT Personnel
  + **`Billing Clerk`**
  + Executive management should approve the plan and should be provided with a high-level summary of the plan.
  + Public Relations should be a member of the disaster recovery plan to handle communications to all stakeholders.
  + `A billing clerk is not typically part of the disaster recovery team.`
  + IT Personnel are primarily responsible for the disaster recovery team.

