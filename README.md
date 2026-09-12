# osTicket Configuration and Administration

<br>

## Overview

This project documents the post-installation configuration and administration of the osTicket help desk environment deployed in Part 1.

The help desk was organized with roles, departments, teams, agents, users, SLA policies, and help topics to support user access, ticket assignment, and service-level management.

This is Part 2 of a three-part osTicket help desk project.

### Project Navigation

[Part 1: Installation](https://github.com/AGZ2789/osticket-installation) → [Part 2: Configuration](https://github.com/AGZ2789/osticket-configuration) → [Part 3: Ticket Lifecycle](https://github.com/AGZ2789/osticket-ticket-lifecycle)

<br>

## Environments and Technologies Used

- Microsoft Azure
- Windows 10
- Remote Desktop Protocol (RDP)
- osTicket v1.15.8

<br>

## Role Configuration

A Supreme Admin role was created to define administrative permissions within the help desk environment.

<img width="1718" height="715" alt="Snipaste_2024-05-16_18-37-18" src="https://github.com/user-attachments/assets/1124fbd5-5c5e-419c-b3a9-a5f5af93a171" />

<br><br>

## Departments and Teams

Departments and teams were configured to organize support responsibilities and separate administrative functions within osTicket.

A dedicated System Administrators department was configured alongside the existing Support and Maintenance departments, while teams provided another method for grouping support personnel.

<img width="1718" height="1391" alt="Snipaste_2024-05-16_19-34-40" src="https://github.com/user-attachments/assets/8dbca23a-c140-4ea8-a4ff-e4f7fe2b091e" />

<br><br>

## User Registration Settings

The user registration settings were configured so end users could submit support requests without being required to register and log in first.

<img width="1718" height="1391" alt="Snipaste_2024-05-16_19-46-45" src="https://github.com/user-attachments/assets/268bf47c-0b3b-4e4a-9d06-46eb74564cb2" />

<br><br>

## Agent and User Configuration

Help desk agents were created and assigned to their appropriate departments. Jane Doe was assigned to System Administrators, while John Doe was assigned to Support.

<img width="961" height="445" alt="Snipaste_2024-05-17_21-21-25" src="https://github.com/user-attachments/assets/d33718db-633b-48b9-b848-0f1b8a7e20aa" />

<br><br>

End users were also added to the user directory to support ticket creation and lifecycle testing.

<img width="960" height="430" alt="Snipaste_2024-05-17_21-23-13" src="https://github.com/user-attachments/assets/372a1995-5700-4a12-a6e8-80852a0f4f7e" />


<br><br>

## Service Level Agreements

SLA policies were configured to establish different response windows based on ticket severity.

SEV-A was configured with a 1-hour grace period and a 24/7 schedule.

<img width="1765" height="1360" alt="Snipaste_2024-05-17_21-34-11" src="https://github.com/user-attachments/assets/20545c5c-a633-45d1-8766-a579bb5ab9e3" />

<br><br>

Additional policies included SEV-B with a 4-hour grace period and SEV-C with an 8-hour grace period using a business-hours schedule.

<img width="958" height="1322" alt="Snipaste_2024-05-17_21-42-26" src="https://github.com/user-attachments/assets/a96cf594-f20b-4abb-aa78-ccdad367ff00" />

<br><br>

## Help Topics

Help topics were configured to categorize incoming support requests. Examples included Business Critical Outage, Equipment Request, Password Reset, and Personal Computer Issues.

<img width="1765" height="1391" alt="Snipaste_2024-05-17_21-56-07" src="https://github.com/user-attachments/assets/ba8bbe6b-38f4-45a0-97da-c364ba99f0a2" />

<br><br>

## Challenges and Troubleshooting

One configuration detail that required careful validation was the end-user registration setting. The Registration Required option was left unchecked so users could create tickets without mandatory account registration.

<br>

## Key Takeaways

- Configured administrative roles and permissions
- Organized support responsibilities using departments and teams
- Configured end-user ticket registration behavior
- Created and assigned help desk agents
- Added end users for ticket lifecycle testing
- Created severity-based SLA policies
- Configured help topics for support-request categorization
