#Verify  DNS

## Objective
Verify the DNS is installed automatically and  add create a few records. 

----
## Environment
Server Name - DC01
Operating System - Windows Server 2022 Evaluation
Domain - project.local

## Steps
1.Open DNS Manager 
2.Go to forward lookup zones
3.Click on project.local
4.Add records:
  -fileserver 192.168.1.10
  -printer 192.168.1.20
  -internet 192.168.1.30

## Result
DNS was Installed automatically.
3 records( fileserver, printer and internet) were added. 


## Screenshot

<img width="1017" height="801" alt="image" src="https://github.com/user-attachments/assets/af6e1758-1a30-40c2-a729-659225b917b1" />

<img width="1001" height="802" alt="image" src="https://github.com/user-attachments/assets/d59849a3-a6ff-41b9-b525-feb580b99b80" />

