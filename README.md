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

---------------------------------------------------------------------------------------------------

<h3> Stage 1 - Ticket Submission:<h3></h3>
   <p></p>
The ticket lifecycle starts with the "ticket submission" where a user submits a support ticket filling in their E-mail address, name and then choose a help topic from the drop down list.

![photo1](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto1.png)

The user will then give an "issue summary" to the best of their ability, in this case the online banking system is down and users are unable to access online banking.
![photo2](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto2.png)

The user will then submit the ticket.
![photo3](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto3.png)


---------------------------------------------------------------------------------------------------

<h3> Stage 2 - Logging in as Help Desk Agent (read only):<h3></h3> 
    <p></p>
The Agent, John, will log in with his credentials from the Help Desk Agent Access Portal

   ![photo4](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto4.png)

Once John is logged in, osTicket will show a dashboard of open tickets of varying priority determined by the employer SLA (Service Level Agreement) that need to be worked and resolved. 
<br>
We're going to click on the most recent ticket created by Karen.
![photo5](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto5.png)

After clicking on the ticket, it will show some more detailed information such as its priority level, status, SLA level, topic etc...
<br>
(You'll notice these are just black text and not blue)
<br>
John has read-only access, so he's not able to change these or escalate them, however we're gonna leave a note on the ticket that it needs to be updated.
![photo6](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto6.png)

Once this is submitted, you'll see the ticket thread has been updated.
![photo7](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto7.png)


---------------------------------------------------------------------------------------------------

<h3> Stage 3 - Logging in is as Help Desk Agent to resolve the ticket (Administrator):<h3></h3>
   <p></p>
We're goning to log in as an Administrator now because they have more access to help resolve the ticket.
<br>
We could also give John more access as an alternative option.

   ![photo8](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto8.png)

You'll see mostly the same information with any updates to the ticket that were made. 
<br>
We also as an Administrator have more access so you'll notice the additional option via the Blue colored text that was black text for John.
<br>
We're gonna change some things to help the process of working the ticket starting with the "Priority level".
![photo9](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto9.png)

We'll change it to Emergency Level becuase it's affecting regular day-to-day business operations for employees and most importantly Account holders who are unable to
 access their accounts. 
![photo10](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto10.png)

We're also going to assign it to our Administrator Chase. 
![photo11](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto11.png)

We need to update the priority so the ticket and thus the issue get's resolved as soon as possible.
<br>
We use Sev-A because it will mark it as top priority in the ticket system.
![photo12](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto12.png)

We're going to add a note as to why it was escalated. 
![photo13](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto13.png)

We are then going to return to the dashboard as Chase and update Karen letting her know we're working diligently on the issue and we'll notify her of any updates or progress.
<br>
We do this to keep our users up to date on a time-line or any issues that may arise in our investigation. 
<br>
We'll head back to the dashboard...
![photo14](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto14.png)

On the dashboard you'll see the update to the information posted successfully, along with all updates made during the working of the ticket to resolution.
![photo15](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto15.png)


---------------------------------------------------------------------------------------------------

<h3> Stage 4 - Ticket Resolution:<h3></h3>
   <p></p>
Here we update Karen that our team has isolated the issue and are working on making an update to fix the issue

![photo16](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto16.png)

After we have fixed the issue, we let Karen know that we'll be pushing an update out and the steps needed to apply the update to the system as well. 
![photo17](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto17.png)


---------------------------------------------------------------------------------------------------

<h3> Step 5 - Ticket Closure:<h3></h3>
<p></p>
We're going to close the ticket now by clicking "status" and then changing the staus to "closed"

![photo18](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/fa3e02b82847459fd7d189e9baa70ec21f173d1c/projectphoto18.png)

We click "closed" to close the ticket
![photo19](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto19.png)


A confirmation will show up and you can add a reason as to why the ticket was closed. 
<br>
In this case the issue was resolved with an update restoring opperations.
<br>
(This should be done in professional enviroments)
<br>
![photo20](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto20.png)


---------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------
Side note - Mistakes I made and thought may need fixed: 
 
I felt I hadn't gone into enough depth in the resolution and updated the message with a edit to the message
<br>
![photo21](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto21.png)

Added as an update as I changed the closure type from "resolved" to "closed"
![photo22](https://github.com/Chase-A-C/LifeCycle-osTicket-Project/blob/20241c4ad2e7d2fae4865bfbd542b5446e16914a/projectphoto22.png)
