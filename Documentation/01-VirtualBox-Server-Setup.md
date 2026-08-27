# VirtualBox  Virtual Machine (VM) Setup for Windows sever

## Objective
Set up the VM to install Windows server 2022

-------
## Environment

VM Name: DC01 
Operating System: Windows Server 2022 Evaluation 
Base Memory: 4096 MB
CPU: 2
Disk: 25 GB Dynamic 


## Steps
1.Click new in Oracle VirtualBox Manager 
2. Enter these details:
  Name-DC01
  OS ISO-Windows Server 2022 Evaluation ISO Image 
  Base Memory: 4096 MB
  Disk: 25 GB Dynamic 
3.Click  finish
4. Install Windows Server Desktop Experience
5.When installation finishes rename the computer -DC01

-------
## Result

A VM is made with Windows Server 2022 Evaluation installed 

## Screenshot
The server VM Settings


#<img width="1041" height="802" alt="image" src="https://github.com/user-attachments/assets/0e01655d-1700-4bcd-a9b9-065d84665630" />

-------
## Troubleshooting
When researching how to do this project it was recommended to have 150+ GB disk space available and I didn't have enough space in my SSD so I had to use less disk space and unchecked the Pre-allocate Full Size setting so the disks are dynamically allocated to fit the amount of space I have on my laptop when making the VM.

  
