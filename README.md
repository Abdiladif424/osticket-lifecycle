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

1. Log in as an end-user, create the following ticket

-The entire mobile/online banking system is down

-My employees are reporting that users are no longer able to access the online banking portal. The ones who can occasionally access it cannot log in. 

<img width="2550" height="1439" alt="Screenshot 2025-07-17 164705" src="https://github.com/user-attachments/assets/4647cb9f-d32c-4718-90a4-61b6eb4d3527" />

2. As a Help Desk Agent (John), observe the ticket’s properties
	
 -Priority
	
 -Department
	
 -SLA
	
 -Assigned To

Set Properties for the ticket
- Sev-A (1 hour, 24/7)  - wide impact. Customers are unable to do online banking. 
- Online Banking Department - Customers unable to access the online banking portal; assigning to the online banking team. 

<img width="2559" height="1439" alt="Screenshot 2025-07-17 172337" src="https://github.com/user-attachments/assets/af736d61-c014-42bc-a465-608aed22d38a" />

3. Work the ticket to completion as Jane
   
-Reassign to a team - I will be taking this ticket

- Notes - I suspect the problem might be related to the recent updates. We have tested them sufficiently, but I will look into it further and roll back if I determine that was the case.
It was determined that the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should be up and running. 

<img width="2559" height="1439" alt="Screenshot 2025-07-17 173440" src="https://github.com/user-attachments/assets/bfe67474-73cf-474a-a763-43c43c56be2d" />

4. As an end-user, create the following ticket

-The accounting department needs an Adobe upgrade, broken

-It looks like many people in the accounting department can’t use their Adobe software. 

<img width="2559" height="1439" alt="Screenshot 2025-07-17 174035" src="https://github.com/user-attachments/assets/09070363-449c-4622-9d31-efd65dae0421" />

5. As a Help Desk Agent (John), observe the ticket’s properties
	-Priority

	-Department

	-SLA - only 2 people are unable to open the Adobe Reader, classifying as sev c 
	
 	-Assigned To

	-Notes - Cx states that only 2 people in the accounting department are unable to open and use Adobe Reader. Cx testing restart, will call back after lunch.
	Cx states that the restart fixed the issue, closing out the ticket. 

<img width="2559" height="1439" alt="Screenshot 2025-07-17 175320" src="https://github.com/user-attachments/assets/1241e3b7-7a4c-4a57-aeca-d914200dd1c8" />

6. As an end-user, create the following ticket
   
-CFO’s laptop will no longer turn on

-Notes - laptop won't power on, despite pressing the button.

<img width="2559" height="1439" alt="Screenshot 2025-07-17 180059" src="https://github.com/user-attachments/assets/f51a4c8f-d68c-4fea-8382-471131856cbb" />


7. As a Help Desk Agent (John), observe the ticket’s properties
   
	-Priority

	-Department

	-SLA - may reclassify after getting more info

	-Assigned To

Set Properties for the ticket

-Sev-B (4 hours, 24/7)

-Support

Work the ticket to completion as John

-Notes - Cfo’s laptop was not charging due to a broken charger, now successfully charging.

<img width="2559" height="1439" alt="Screenshot 2025-07-17 180930" src="https://github.com/user-attachments/assets/2248678b-f789-4f22-9a7c-367ffd98a958" />

8. All of the completed tickets!

<img width="2559" height="1439" alt="Screenshot 2025-07-17 181035" src="https://github.com/user-attachments/assets/6a616f78-e52a-4e35-8857-f902847c34d1" />







