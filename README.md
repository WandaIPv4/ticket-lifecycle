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

<p> 
<h3>Example 1</h3>
  
<img width="500" alt="Creating a ticket" src="https://github.com/user-attachments/assets/d3d8aa3f-da67-4810-92b8-55c4090e227a" />
</p>
<p>
</p> As an end-user, create the following ticket
</p> "entire mobile/online banking system is down"
</p> 
<img width="500" alt="Before SLA Change" src="https://github.com/user-attachments/assets/e72b38e2-0b45-492f-837d-2d1406b4f136" />
<img width="400" alt="Update SLA Plan" src="https://github.com/user-attachments/assets/a47f8f76-3fe7-4bca-980b-95f6799963d4" />
<img width="500" alt="How to Assign to Team" src="https://github.com/user-attachments/assets/251eb9e5-30cf-4e34-81ec-f4ff2636454b" />

As a Help Desk Agent (John), observe the ticket's properties: 
* Priority 
* Department
* SLA
* Assigned To


Set Properties to the ticket:
* Sev-A (1 hour, 24/7)
* Online Banking Department
</p> 
</p> <img width="500" alt="Sign into Jane   Assign to Jane specifically" src="https://github.com/user-attachments/assets/dafbb768-25fa-4965-896e-2a92732f26bf" />
<img width="506" alt="Updating ticket until completion" src="https://github.com/user-attachments/assets/bbb55cd6-d9ad-472f-b220-a52412a910d6" />
</p> 
<img width="408" alt="Changing the ticket status" src="https://github.com/user-attachments/assets/920f19b3-bad0-4f95-bdac-4e5e25ff7c44" />

</p> 
</p> Since its assign to the online banking department , Help Desk Agent (Jane) will work ticket until completion
<p></p> 
</p> 
<h3>Example 2</h3>

<img width="400" alt="Example 2 - ticket" src="https://github.com/user-attachments/assets/d00205d2-1ae9-4083-819e-fa05f4107b32" />

</p> As an end-user, create the following ticket:
<p> "accounting department needs adobe upgrade, broken"
</p>
<img width="501" alt="Updated SLA after finding out only 2 cannot access adobe" src="https://github.com/user-attachments/assets/686dce7d-0b9d-4ff0-b8c7-7b8a577f5e6c" />
<p> After more investigation you realize its only a couple of people who cannot access adobe. 
<p> Therefore the Properties Sev-C will suffice. 
<p> The priority will be set to Normal.
<p>
<img width="500" alt="Assign to John issue 2" src="https://github.com/user-attachments/assets/00a6ef80-ec73-483e-a59e-ab38130979f2" />
<p> Help Desk Agent John will assign this ticket and work it until completion. 
</p>
<p> <img width="450" alt="Close the ticket after posting and issue is fixed (2)" src="https://github.com/user-attachments/assets/30742cee-a148-4f08-8e1e-11fd56df9a17" />
<p> Make sure to complete and close out the ticket and leave notes if applicable. 
<br />
<h3>Example 3</h3>
<p> 
<img width="450" alt="Example 3" src="https://github.com/user-attachments/assets/5596129d-dd26-44a2-99fd-5854edd23650" />
</p>
<p>
<p> As an end-user, create the following ticket:
<p> "CFO’s laptop will no longer turn on"
<p>
<p> <img width="500" alt="Update SLA   PRiority accoring to CEO" src="https://github.com/user-attachments/assets/2c73d384-dcd9-4a70-a7cc-9e557000c7da" />
<p>
<p> Since this ticket is involving the CFO the priority is Emergency but since it isn't detrimental to the company or business the SLA Plan is going to be set as Sev-B.
<p>
<p> <img width="456" alt="Closed ticket for CFO laptop 3" src="https://github.com/user-attachments/assets/98b4c22d-d491-4d52-bd54-db585c4c27e0" />
<p> 
<p> Make sure to complete ticket and mark as closed or resolved.
</p> 
</p>
<br />

<h2>Extra Tips</h2>

* Make sure to set properties to all tickets & solve them according to the SLA properties. 
* Tickets intake in real life may not always come from the end user submitting a ticket. Sometimes tickets get created via phone, chat app, email or even in passing. Its best to create tickets for EVERYTHING you do. 
* Make sure to gather as much information as you can before troubleshooting a ticket. 
