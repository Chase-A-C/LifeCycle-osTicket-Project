<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3> Stage 1: Ticket Submission
 

---------------------------------------------------------------------------------------------------
   
The ticket lifecycle starts with the "ticket submission" where a user submits a support ticket filling in their E-mail address, name and choosing a help topic from the drop down list.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/c94c42d5c20397e85ab22bfd1a34216383f17193/projectphoto1.png)

The user will then give an "issue summary" to the best of their ability, in this case the online banking system is down and users are unable to access online banking.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto2.png)

The user will then submit the ticket.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto2.5.png)


---------------------------------------------------------------------------------------------------

<h3> Stage 2: Logging in as Help Desk Agent (read only)
 
The Agent, John, will log in with his credentials from the Help Desk Agent Access Portal
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/35b773ae6e643f4a097d7d70a2976f193d6dc2c8/projectphoto3.png)

Once John is logged in, osTicket will show a dashboard of open tickets of varying priority determined by the employer SLA (Service Level Agreement) that need to be worked and resolved. We're going to click on the most recent ticket created by Karen.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto3.5.png)

After clicking on the ticket, it will show some more detailed information such as its priority level, status, SLA level, topic etc... 
(You'll notice these are just black text and not blue) 
John has read-only access so he's not able to change these or escalate them, however we're gonna leave a note on the ticket that it needs to be updated.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto4.png)

 Once this is submitted, you'll see the ticket thread has been updated.
 ![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto4.5.png)


---------------------------------------------------------------------------------------------------

<h3> Stage 3: Logging in is as Help Desk Agent to resolve the ticket (Administrator)


We're goning to log in as an Administrator because they have more access to help resolve the ticket; we could also give John more access as another option.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto5.png)

You'll see mostly the same information with any updates to the ticket that were made. 
We also as an Administrator have more access so you'll notice the additional option via the Blue colored text that was black text for John.
We're gonna change some things to help the process of working the ticket starting with the "Priority level".
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto5.5.png)

We'll change it to Emergency Level becuase it's affecting regular day-to-day business operations for employees and most importantly Account holders who are unable to
 access their accounts. 
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto6.5.png)

We're also going to assign it to our Administrator Chase. 
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto6.png)

We need to update the priority so the ticket and thus the issue get's resolved as soon as possible.
 We use Sev-A because it will mark it as top priority in the ticket system.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto7.png)

We're going to add a note as to why it was escalated. 
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto7.5.png)

We are going to return to the dashboard as Chase and update Karen letting her know we're working diligently on the issue and we'll notify her of any updates or progress.
 We do this to keep our users up to date on any time-line or issues that may arise in our investigation.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto8.png)

 n the dashboard you'll see the update to the information posted successfully along with all updates made during the working to resolution of the ticket.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto8.5.png)


---------------------------------------------------------------------------------------------------

<h3> Stage 4: Ticket Resolution:

Here we update Karen that our team has isolated the issue and are working on making an update to fix the issue
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto9.png)

After we have fixed the issue, we let Karen know that we'll be pushing an update out and the steps needed to apply the update to the system as well.
We also let Karen know if anyother issues arise or persist that she can open a new ticket.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto9.5.png)


---------------------------------------------------------------------------------------------------

<h3> Step 5: Ticket Closure:


We're going to close the ticket now by clicking "status"
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/4f55eb2f997ee4b15376c0cee78682e98c66ee05/projectphoto10.png)

We click "closed" to close the ticket
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/67b8ddab2d82b1205f12fb39d22213c6a71904ee/projectphoto10.5.png)

A confirmation will show up and you can add a reason as to why the ticket was closed. 
This should be done in professional enviroments)
We add "Account Holder Issue Resolved" because account holders are able to access online banking again.
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/67b8ddab2d82b1205f12fb39d22213c6a71904ee/projectphoto11.png)


---------------------------------------------------------------------------------------------------

Side note: Mistakes I made and thought may needed fixed
 
I felt I hadn't gone into enough depth in the resolution and updated the message with a edit to the message
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/67b8ddab2d82b1205f12fb39d22213c6a71904ee/projecthoto11.5.png)

Added as an update as I changed the closure type from "resolved" to "closed"
![image alt](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/67b8ddab2d82b1205f12fb39d22213c6a71904ee/projectphoto12.png)
