<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Resolution Examples:</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows Server 2025 Datacenter X64 Gen2</b> 

<h2>Ticket Resolution Examples</h2>

- This project demonstrates how IT support tickets are prioritized, categorized, resolved, and escalated based on severity and impact.
- 
<h2>Ticket Resolutions</h2>

<p>
<img width="2403" height="1216" alt="LAB2A-TicketTriage" src="https://github.com/user-attachments/assets/c3d2853f-e7a5-4878-9136-e10683d3bd28" />
</p>
<p>

- This ticket simulates a business critical outage affecting a bank’s online and mobile banking systems. The end user Karen reports that both services are down.
  
- Tier 1 support would start initial troubleshooting by confirming the issue scope such as who and what is affected, verifying whether the outage is isolated or affecting multiple users, checking basic connectivity, and reviewing any recent service changes or known incidents. After follow-up, it is confirmed that the issue impacts the entire branch, indicating a system-wide outage.

- Based on the ticket severity and business impact, this ticket is upgraded to an Emergency priority level with a high severity SLA classification, and is escalated to the SysAdmin team for further troubleshooting due to being out of tier 1 scope.

</p>
<br />

<p>
<img width="2403" height="1216" alt="LAB2A-TicketResolve2" src="https://github.com/user-attachments/assets/8af717cd-92e1-4b0a-8935-a20785f9e25e" />
</p>
<p>

- This ticket simulates an application failure affecting the Accounting department. End user Ken reports Adobe Reader does not launch and that 10 out of 12 of his coworkers cannot access it.

- Initial scope analysis confirms that 10 of 12 users are unable to launch Adobe Reader, coinciding with an ongoing internal audit, which increases business impact. Based on the scope and severity of the issue, the ticket is classified as High Priority with a Medium SLA.

- Tier 1 troubleshooting includes observing how the application behaves, confirming the issue persists after restarts and trying to launch it in safe mode.

- Further investigation shows that an Adobe Reader update deployed overnight has caused the application to stop launching. A resolution is provided by the SysAdmin team, offering the end users either manual installation via the software catalog or waiting for a network-wide redeployment of a fixed package.

- The end user chooses to do a manual installation across the affected workstations, resolving the issue. Adobe Reader functionality is verified with the end user, and the ticket is closed.

</p>
<br />

<p>
<img width="2403" height="1216" alt="LAB2A-TicketResolve5" src="https://github.com/user-attachments/assets/d655e5b3-4bad-4135-bec6-d33dfe07fd5c" />
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
