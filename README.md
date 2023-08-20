![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/98aaf6d2-d730-4075-b3fd-319decff4f3c)

<h1>osTicket Post-Installation</h1>

This lab shows how we can set up different aspects for the ticketing system to work like creating departments and roles and adding people to the teams

<h1>Environment</h1>

- Microsoft Azure
- osTicketing

<h1>Configuration</h1>

With osTicket installed, it is time to set up the ticketing system by adding new roles, service levels, and different topics.

First things first, we would be adding in a new role, which we call Supreme Admin with access to all permissions (example below) for the ticketing system. To do so, we access the Admin Panel and go to "Agents" and head over to "Roles" to add the new admin role

![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/748788c7-d6d8-4494-9fd7-90b1df9d5c40)

Next, we will be adding a new department called System Administrators. This again is also in the "Agents" section under "Department"

![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/541a33df-7553-4402-93cb-a4e257488a09)

Similar to the department, we can add new teams to handle different types of support that may come through.

![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/9844dad8-5955-4517-b350-33c4c7f30211)

For the ticketing, we need to allow access for someone to create tickets. This is done in the Admin Panel in Settings -> User Settings

![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/ca855f1b-7511-413e-bb21-d529d4166fd6)

Moving on, we will be adding different Service Level Agreements (SLAs) to help categorize tickets according to the level of impact and importance. You can categorize these for instance in the example and these will need to be resolved either within 1 hour, 4 hours, and 8 hours respectively

![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/a195eb5e-5fe2-4feb-9e2f-37a32ebb235c)

Finally, we can finish the setup with Help Topics. These are created to help users to select from different categories that fit their problem and give the agents a clear idea of what the problem is in the ticket.

![image](https://github.com/Zues4366/osticket-post-installation/assets/33434045/862dcd83-1afd-41a6-aa6b-3c930fbaeef5)

<h1>Complete</h1>
Now the configuration is complete, we can utilize the osTicket system to simulate a ticketing system where tickets can come in and we can interact, respond and work on the tickets coming in.
