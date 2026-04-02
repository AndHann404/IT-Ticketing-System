# IT-Ticketing-System
## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Intro to Ticketing Systems](#intro-to-ticketing-systems)
- [Getting started with Spiceworks](#getting-started-with-spiceworks)
- [Practice Scenarios](#practice-scenarios)
- [Resources](#resources)
  
---
## Overview
An IT Helpdesk Lab that simulates a Tier 1 Support Environment using the Spiceworks Cloud Help Desk platform. It provides a structured approach to the lifecycle of incident management, focusing on professional documentation, and systematic troubleshooting of common workplace technical issues.

---
## Objective
To Learn the fundamentals of an IT ticketing system, including:
- How to properly log a ticket  
- How to classify and prioritize issues  
- Ticket statuses and workflow  
- Hands-on experience using Spiceworks Ticketing system in a HelpDesk setting
---
## Intro to Ticketing Systems
## 1. What is a Ticketing System?
A ticketing system is a software interface used by IT teams to track, manage and resolve user issues effciently. It serves as a central hub that converts various communication channels into a single, organized list of tickets.

It Ensures:
- Clear documentation  
- Proper routing  
- Efficient communication with user
- Traceability of troubleshooting steps  


**Examples of Common Ticketing Systems:** Zendesk, Freshdeck, Spiceworks, Zohodesk, ServiceNow
---
## 2. Key Components of a Ticketing System
#### Ticket ID number
A unique reference number for each issue, this helps IT teams to track the tickets progress and maintain records.

#### Requester
The person who is reporting the issue. This ensures we are communicating with the right person for toubleshooting and follow ups.

#### Catergory
The Classifcation of an Issue. Used for organization and management of different tickets.
Examples:
- Hardware Issue (Laptop not booting, Hard Drive failure, Overheating)
- Software Issue (Application crashes, Faulty Updates)
- Network Issue (Wi-Fi Connectivity Issues, Slow Internet)
- Account Access (Account Lockout)

#### Priority Level
Defining the urgency of an Issue. Used to define the order support requests are resolved.

| Priority | Meaning | Impact | Example |
|---------|---------|--------|---------|
| **Critical (P1)** | Network outage | High | The main internet connection for the building is down |
| **High (P2)** | Department-level issue | High | Ransomware detected on Payroll Server - Files encrypted |
| **Medium (P3)** | Single-user issue | Low | Employee's desktop is running slow |
| **Low (P4)** | Minor request | Minimal | Request for a new Webcam |
  
#### Assigned To
The Technican who is repsonsible for handling the ticket. 
They are responsible for providing updates to the user.

#### Status
Tracks the progress of a Ticket 

| Status | Meaning |
|--------|---------|
| **New** | Ticket created, not yet reviewed |
| **In Progress** | Technician is actively working on it |
| **Pending User Response** | IT needs more information from the user |
| **Escalated** | Moved to higher-level technician/Support Team |
| **Resolved** | Issues has been fixed, waiting on user confirmation |
| **Closed** | User confirms issue is resolved, ticket is archived |

## 3. How to Properly Log Tickets
#### Gather User Information
- Full Name  
- Email  
- Contact number  
- Department  
- Location (if applicable)

#### Gather System Information
- Device type  
- Operating system  
- Software version  
- Network type (Wi-Fi/Ethernet)

#### Categorize the Issue
Examples:  
- Software issue  
- Hardware issue  
- Network issue  
- Account Access  

#### Determine Priority Level

- Critical, High, Medium, or Low.

Based on impact and urgency of the Issue.

#### Ask Followup Questions 
- When did the issue start?
- Did you download something prior to this issue occuring?
- Have you noticed any error messages or crashes?
- Are other applications also slow, or just Word doc?

#### Assign to Techncian 
Assigning the issue to the right technican
- If the issue isn't resolved, you can escalate it to level 2. Make sure to inculde changes you made.


#### Status
Update the ticket status whenever there are changes.

- Ex: In progress

---
## Getting started with Spiceworks 
1. Sign up for a Free Account
2. Log into Spicework Helpdesk Dashboard
3. Explore ticketing system:
   - Creating tickets/Resolving tickets
   - Updating status
   - Adding Notes


Spiceworks Signup Page <img width="1089" height="672" alt="Creating Spicework Account" src="https://github.com/user-attachments/assets/c55dec1f-880a-4dea-b1bc-7e832f901f86" />

Signing up for Cloud HelpDesk <img width="1440" height="412" alt="Cloud Helpdesk" src="https://github.com/user-attachments/assets/ecd8cf2d-ba97-4b6a-92ab-97dccc4ea353" />

Spiceworks Ticketing Dashboard Interface <img width="1438" height="692" alt="Explorepage" src="https://github.com/user-attachments/assets/95615500-bfed-46e4-bed1-259a57c0bfcc" />

---
## Practice Scenarios

#### Creating Tickets
When creating tickets in very important to provide as much detail as possible.
So in this ticket:

- It provided a detailed description of what the problem was and what they did so far to resolve it
- Mentioned that its only happening to them
- Provided contact information
- Catergorzied Pirority
- Provided an attachment for the Technician

Ticket Creation Process:

<img width="601" height="649" alt="Ticket Creation 1" src="https://github.com/user-attachments/assets/e4ce6056-0753-477d-984d-f8554c0094e1" />

 <img width="598" height="648" alt="Ticket Creation 2" src="https://github.com/user-attachments/assets/52bfc5d0-7abe-4f42-9910-15a2bca02c7a" />

#### Scenario 1 (Network Issue)
User Problem: Jason More reports that he’s experiencing connectivity issues.
- Category: Network Issue
- Priority: Medium (P3)
- Actions: Respond to user, Research inspect the workstation, go on the CLI and use these commands (Ipconfig, Ipconfig/release, Ipconfig/renew).

<img width="1064" height="539" alt="My response" src="https://github.com/user-attachments/assets/5ed509ed-7c0f-4157-b96e-f80e95b005f9" />

<img width="1065" height="543" alt="My description of the issue " src="https://github.com/user-attachments/assets/718464b8-f612-40b6-9573-25365205226f" />

### Scenario 2 (Application Issue)
User Problem: Jemma Lao reports that she is unable to open the application Microsoft teams. 

- Category: Other
- Priority: Medium (P3)
- Actions: Ask her questions about any changes to her computer/gather info (messages popping up, etc), ask her to restart her computer; if that doesnt work tell her to check for application updates.

<img width="594" height="647" alt="ApplicationIssue" src="https://github.com/user-attachments/assets/0d42f4f8-b491-40d3-ad61-0c3b3216c6b6" />

  <img width="1065" height="545" alt="Gathering info from Jemma" src="https://github.com/user-attachments/assets/06d61a91-2418-4679-ad8f-62da2f8c604e" />

  
<img width="1065" height="536" alt="Resolved Application issue" src="https://github.com/user-attachments/assets/77e7c6fb-6b08-4771-926f-85c46d1edcac" />


<img width="720" height="69" alt="Screenshot 2026-04-01 at 4 34 01 PM" src="https://github.com/user-attachments/assets/5bd05c29-2253-4b91-af10-41253b6d46ec" />




## Resources
- [East Charmer YouTube tutorial](https://youtu.be/g1AZ-EtD6Nw?si=RBNATHl_1-PKMU4R)

---
