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
<img src="https://i.imgur.com/VgAOIig.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is possible that the IP address would change if you've log out of your VM or lost connection in the installation stage, so login to Azure portal to copy a new VM IP address. Reconnect to VM as follows: Open RDP and paste the VM IP address -> enter default username and password generated when creating VM -> ok to remotely gain access to VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/H1fisZm.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Remote access gained succefully.
</p>
<br />

<p>
<img src="https://i.imgur.com/LCapVvB.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Copy and paste end users URL on your VM browser -> login with admin user name and password created from the installation stage. end users osticket page will load as shown in the above image. 
  
 End Users URL- http://localhost/osTicket/ 
</p>
<br />

<p>
<img src="https://i.imgur.com/cAKWova.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Intake: One of the user created 'karen@osticket.com' in post installation stage will login as a user as follows:
  
Open a New Ticket -> User filled contant details -> Select Help Topic -> Create Ticket -> Issues summary -> provide Details of the issue -> Create Ticket. Ticket created and user received a notification that the ticket has been created as shown in the above image. Note: Any user in the list of configured users can create ticket as long as his/her email has been configured by the admin. 
</p>
<br />

<p>
<img src="https://i.imgur.com/QaVJ359.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> 
Assgnment and Communication: Use Admin URL to login as one of the help desk professionals who goes about troubleshooting and solving help desk tickets, and this should display all the users tickets as shown above. 
</p>
<br />

<p>
<img src="https://i.imgur.com/WaPeV1Y.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Usually this is the stage where various users ticket will can be assigned to agents (help desk professionals) by the Team Lead or the  person in-charge depending on the organisation SOP. The help desk professionals with the right permission logged in using the admin URL to assign and communicate ticket to agents (other help desk professionals) for resolution. Here  a whole lot of thing can be done like: assign priority, assign department, assign SLA plan, assign ticket to a specific help desk professional and so on. Click the ticket and fill out the appropriate information to assign and communicate, the page where ticket can be assigned shown in the above image.
</p>
<br />

<p>
<img src="https://i.imgur.com/uEfgL0v.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above ticket has been assigned to an help desl professional name 'jane.doe' you can also noticed that the priority has chnaged from 'Normal' to 'Emergency' frome the above image. These are examples of what assignment and communication looks like.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
