# Join CLIENT01 to the Domain

## Objective

The LabClient1 computer joined the project.local Active Directory domain.

----

## Environment

Computer Name: LabClient1
Operating System: Windows 11
Domain: project.local

----

## Steps 
1. Opened Windows System settings and go to About.
2. Select domain or workgroup and then click change.
3. Entered: project.local
4. Entered domain administrator credentials.
5. Successfully joined LabClient1 to the domain.
6. Restarted the computer.

----

## Result
LabClient1 successfully joined the domain and the computer restarted

----
## Screenshot

<img width="1025" height="767" alt="image" src="https://github.com/user-attachments/assets/6b931871-4e06-4bec-a872-96c06e98da6e" />



## Troubleshooting

While trying to join the LabCLient1 to the DC01 server/ Domain, the client computer would join and I would get an error message.

<img width="600" height="447" alt="image" src="https://github.com/user-attachments/assets/1a268ab9-66f8-4832-9778-93275c182b1b" />

In VirtualBox application in the network settings for both VMs set 'Attached to' to internal network. This fixes the joining domain issue.

<img width="947" height="515" alt="image" src="https://github.com/user-attachments/assets/545a2650-af0f-4b15-9a87-70bba5cf34cc" />
