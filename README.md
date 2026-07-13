<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Utilizing Virtual Machines within Azure)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> 

<h2>Ticket Lifecycle Stages</h2>

End Users can submit tickets to the helpdesk, for example, a portion of the office network is down.
A user submits a ticket to the helpdesk using osticket.
* Ticket is created and usually automatically assigned by the SLA (service level agreement)
* Assigned to an agent to be investigated if necessary, the agent and the end user communicate
* Ticketed Issue is resolved or escalated
* Ticket is closed and the solution is logged for future issues 

<h2>Lifecycle Stages</h2>

<p>
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0bbb331a-f1b5-4a9f-bee6-8ee2fe971192" />
</p>
<p>
Heres an example of the various tickets you can see in a day-to-day scenario

</p>
  *
<br />
<img width="1391" height="790" alt="image" src="https://github.com/user-attachments/assets/7b139690-5e11-4810-b707-256289710c91" />
Enduser/Customer ticket creation example
<p>

</p>
<p>
Ticket creation form used by the customer or end user
  This is the ticket as described by the user. With this, you should have enough information on the issue. If not, please contact the person who issued the ticket and communicate with them to better understand the issue.
  Once you've corrected the issue, you're able to close out the ticket by listing it as resolved. If you are unable to correct the issue, you can escalate the ticket further. Remember to keep the customer or user apprised of the progress of the ticket as well. Good communication helps immensely with customer-facing relations.

  Tickets are submitted by the customer or end user. They will fill out a contact information form with their name and phone number, and select a topic from a drop down list. Note that they may select the wrong topic when submitting, but this is something that you can fix while triaging the ticket.
  there will be an internal note section where you'll be able to add a note to the ticket as you make changes and updates. The notes will be for you and other agents to be able to see and interact with; customers will not be able to view them.
  First, log in to the OS ticket agent panel. Then, you'll select an open ticket from the ticket queue in the dashboard. Once you've opened that newly created ticket, you'll see the following information: a ticket number, the user who submitted the ticket's name and contact information, the subject, a description of the issue, and the date and time of submission, as well as a priority level if it has already been assigned by another agent.
  
</p>
<br />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/9f6ea9d9-1de5-4ea6-99a2-9719d7aff01a" />
<p>
The process from start to finish

 using OSticket you can assign SLA's to a ticket. This determines its severity, scaling from something unserious to a business critical outage that should be fixed as soon as possible.
</p>
<p>
Once the issue has been resolved, add a final response that summarizes what you did to arrive at the solution and how you implemented it. Ensure that you've already spoken to the end user who sent the ticket originally and inform them that the issue is resolved.
</p>
<br />
