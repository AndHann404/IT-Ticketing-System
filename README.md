# Ticketing System Lab (using Spiceworks)
## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Intro to Ticketing Systems](#intro-to-ticketing-systems)
- [Getting started with Spiceworks](#getting-started-with-spiceworks)
- [Practice Scenarios](#practice-scenarios)
- [Conclusion](#conclusion)
- [Resources](#resources)
  
---
## Overview
This an IT Lab that simulates a Tier 1 Support Environment using the Spiceworks Cloud Help Desk platform. It provides a structured approach to the lifecycle of incident management, focusing on professional documentation, and systematic troubleshooting of common workplace technical issues.

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

This ensures:
- Clear and comprehensive documentation
- Proper request/ticket routing 
- Efficient communication with users
- Visibility and tracking of troubleshooting activities
- Accountability and ownership
- Knowledge sharing


**Examples of Common Ticketing Systems:** Zendesk, Freshdeck, ServiceNow
---
## 2. Key Components of a Ticketing System
#### Ticket ID number
A unique reference number for each issue, this helps IT teams to track the tickets progress and maintain records.

#### Requester
The person who is reporting the issue. This ensures we are communicating with the right person for toubleshooting and follow ups.

#### Category
The Classifcation of an issue. Used for the organization and management of different tickets.
Examples:
- Hardware Issue (Laptop not booting, Hard Drive failure, Overheating)
- Software Issue (Application crashes, Faulty Updates)
- Network Issue (Wi-Fi Connectivity Issues, Slow Internet)
- Account Access (Account Lockout)

#### Assigned To
The Technican who is repsonsible for handling the ticket. 
They are also responsible for providing updates to the user.

#### Priority Level
Defining the urgency of an Issue. Used to define the order support requests are resolved.

| Priority | Meaning | Impact | Example |
|---------|---------|--------|---------|
| **Critical (P1)** | Network outage | High | The main internet connection for the building is down |
| **High (P2)** | Department-level issue | High | Ransomware detected on Payroll Server - Files encrypted |
| **Medium (P3)** | Single-user issue | Low | Employee's desktop is running slow |
| **Low (P4)** | Minor request | Minimal | Request for a new Webcam |
  

#### Status
Tracks the progress of a Ticket 

| Status | Meaning |
|--------|---------|
| **New** | Ticket created, not yet reviewed by anyone |
| **In Progress** | Technician is actively working on it |
| **Pending User Response** | IT needs more information from the user |
| **Escalated** | Moved to higher-level technician/Support Team |
| **Resolved** | Issues has been fixed, waiting on user confirmation |
| **Closed** | User confirms issue is resolved, ticket is now archived |

## 3. How to Properly Log Tickets
#### Gather User Information
- Full Name  
- Email  
- Contact number  
- Department  
- Location (if applicable)

#### Gather System Information
- Device type  
- Operating System 
- Software Version  
- Network type (Wi-Fi/Ethernet)

#### Categorize the Issue
Examples:  
- Software issue  
- Hardware issue  
- Network issue  
- Account Access
- Other   

#### Determine Priority Level

- Critical, High, Medium, or Low.

The level is based on impact and urgency of the issue.

- Ex: If there was a Power issue for an entire floor, then the priority level would be High or Critical.

#### Ask Follow up Questions 
- When did the issue start?
- Did you download something prior to this issue occuring?
- Have you noticed any error messages or crashes?
- Is this issue happening to anyone else or any other departments?
- Are other applications also slow, or just Word doc?

#### Assign to Techncian 
Assigning the issue to the right technican
- If the issue isn't resolved, you can escalate it to level 2 or level 3. Make sure to inculde changes and troubleshooting methods used within the notes.


#### Status
Update the ticket status whenever there are changes.

- Ex: In progress, Resolved, Closed


### Service Level Agreement (SLA) for Ticketing Systems

- This defines the expected response and resolution times for different types fo technical issues.

| Key components of SLA | Meaning |
|--------|---------|
| **Repsonse Time** | The time it takes for IT Support/Helpdesk to respond to a Ticket |
| **Resolution Time** | The time within the issue should to be resolved |
| **Ticket Pirortization** | Piroritizing Ticket levels based on the impact of the issue |
| **Escalaction Process** | Defines when and how a Ticket should be esalaction to a level 2/3 Technician if not resolved within the SLA |
| **Service Availablilty** | Classifies Support Hours |
| **Penalties and Breach Consequences** | Defines what happens when SLA's aren't met |


---
## Getting started with Spiceworks 
1. Sign up for a Free Account
2. Log into Spicework Helpdesk Dashboard
3. Explore ticketing system:
   - Creating tickets/Resolving tickets
   - Updating status
   - Adding Notes
   - Creating Help Desk Scenarios 


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

### Scenario 3 (Software Issue (escalation))
User Problem: Malcom reports that the office on the 3rd floor can’t connect to the network. 

Note: In this scenario, I am unable to compelete the task and must escalate so the ticket will not be closed.

- Category: Network
- Priority: High (P2)
- Actions: Ask questions about the status of the device/gather information, suggest a troubleshooting method, escalated the issue to a level 2, provide details of what I did so far.

  <img width="592" height="595" alt="Malcom Ticket " src="https://github.com/user-attachments/assets/4a147292-3b8d-4304-9669-318f6d6386cc" />

  <img width="1059" height="453" alt="Network issue ask questions" src="https://github.com/user-attachments/assets/f8257a97-8630-4283-9d75-56f8f6cafa42" />

  <img width="745" height="543" alt="Troubleshooting" src="https://github.com/user-attachments/assets/51cca9ee-a6b2-47ba-b125-85436f1380a5" />

  <img width="1063" height="537" alt="Escalation" src="https://github.com/user-attachments/assets/12fc891c-045d-43f8-8342-417781074cd9" />


#### Scenario 4 (Printer Issue)
User Problem: Jason More reports that him and his team aren't able to print out documents.
- Category: Printer Issue
- Priority: Medium (P2)
- Actions: Respond to user and ask multiple follow up questions, Instruct them to check to see if they are connected to their Printer, re - establish network connection to printer, test out printer and confirm with user

  Note: In this scenerio there will be an SLA time line needed to be followed.

  <img width="600" height="644" alt="Printer Issue Ticket" src="https://github.com/user-attachments/assets/188e1238-f907-4f98-b410-2f49d6cae9d9" />
 
<img width="744" height="542" alt="Printer Issue part 1" src="https://github.com/user-attachments/assets/f25780dd-c9d6-4259-b6a7-9f8da63a8650" />

<img width="742" height="538" alt="Printer Issue part 2" src="https://github.com/user-attachments/assets/84a81481-7841-4ba0-a6a0-901ef4f87034" />

<img width="743" height="540" alt="Printer issue part 3" src="https://github.com/user-attachments/assets/537bc246-df85-47da-9ca4-aad06381b791" />

<img width="1060" height="543" alt="Printer issue part 4" src="https://github.com/user-attachments/assets/05d72285-d338-4eeb-a8d4-a08f30419623" />

<img width="1064" height="543" alt="Printer Issue Closing" src="https://github.com/user-attachments/assets/9fca2268-81e9-452c-b66f-ef6241b047be" />

<img width="718" height="431" alt="Screenshot 2026-04-05 at 2 29 41 PM" src="https://github.com/user-attachments/assets/b910f1a8-c275-4ea7-b190-3c1280194759" />


## Conclusion
This project demonstrates the creation and management of IT support tickets across different scenarios. It has equipped me with practical skills for a Help Desk or IT Support role, including resolving issues and escalating tickets appropriately. Completing this lab provided hands-on experience in managing tickets effectively within a simulated IT environment.


## Resources
- [East Charmer YouTube tutorial](https://youtu.be/g1AZ-EtD6Nw?si=RBNATHl_1-PKMU4R)

---
